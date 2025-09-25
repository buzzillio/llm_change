# LeaderMatrix

An interactive Jupyter notebook for quickly building a **“leader change” matrix**—a table and heatmap that compare who/what leads across categories (or over time) and highlights changes in leadership. Typical uses include tracking **LLM model or provider leadership** (e.g., accuracy, price, speed, context window), SOTA shifts on benchmarks, or any project where you want to see **who wins each category and how those wins shift** between snapshots.

> Notebook: `LeaderMatrix.ipynb` (root of this repo)

---

## What it does

- **Ingests simple tabular inputs** (e.g., CSVs, pasted tables, or lists/dicts in cells) representing entities (rows) and metrics (columns).
- **Constructs a “leader matrix”** that marks the winner per category and counts wins per entity.
- **Compares two snapshots** (e.g., “then” vs “now”) to show **gains/losses in leadership** by entity and by category.
- **Visualizes** the results (table and heatmap) and can **export** summary CSVs/PNGs for sharing.

## Quickstart

### Option A — Run in Colab (no setup)
1. Open the notebook directly in Colab:  
   https://colab.research.google.com/github/buzzillio/llm_change/blob/main/LeaderMatrix.ipynb
2. Run cells top-to-bottom.  
3. When prompted (or in the “INPUT” section), paste your tables or upload CSVs.

### Option B — Run locally
1. Clone the repo:
   ```bash
   git clone https://github.com/buzzillio/llm_change
   cd llm_change
