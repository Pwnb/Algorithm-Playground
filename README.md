# Algorithm Notes (rename this repo however you like)

A clean structure for recording algorithm problem-solving notes with Jupyter Notebooks.

## Structure
```
algorithm-notes/
  README.md
  .gitignore
  notebooks/
    arrays/
    dp/
    graph/
    string/
    sliding-window/
    two-pointers/
    tree/
    greedy/
    backtracking/
    heap/
  templates/
    notebook_template.ipynb
```

## Naming Convention
- One problem per notebook, e.g. `0001-two-sum.ipynb`.
- Place any images under `img/` inside the problem folder and reference with Markdown: `![](img/prompt.png)`.

## VS Code + Git Quick Workflow
1. Open folder in VS Code. Install the **Python** and **Jupyter** extensions.
2. Use the **Source Control** tab → **Initialize Repository** (if needed).
3. After edits: **Source Control** → write a message → **Commit** → **Publish Branch / Sync Changes** to GitHub.

## Notebook Sections (recommended)
- Problem Info (title, link, image, constraints)
- Intuition / Patterns
- Approach 1 (brute force) + complexity
- Approach 2 (optimized) + complexity
- Correctness reasoning & edge cases
- Tests
- Notes / Pitfalls
```
