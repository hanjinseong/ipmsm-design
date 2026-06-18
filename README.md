# IPMSM Design Optimization — Multi-Agent Console

A multi-agent system for IPMSM design optimization via an FEA-AI hybrid approach.

Interactive dashboard visualizing three LLM agents:

- **Design Agent** — defines the optimization problem through chat (objective / design variables / constraints)
- **Training Agent** — fills the dataset via adaptive resampling and trains a UQ-aware deep-ensemble surrogate
- **Optimization Agent** — an LLM sets a switching threshold τ on the total predictive std σ (W) to route each evaluation to FEA or the AI surrogate

Single self-contained file (`index.html`, HTML/CSS/JS inline). KO/EN toggle.

## View

Published with GitHub Pages: open `index.html` (the site root).
