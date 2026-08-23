# LightGBM and SHAP

The application serves precomputed LightGBM results so visitors can explore model outputs immediately without retraining models on every interaction.

## Model structure

- Separate continuous-TTC and severe-conflict classification outcomes.
- Microscopic, policy-lever, and combined feature modes.
- Separate 0.6 s, 0.8 s, and 1.0 s headway datasets plus pooled views.
- Group-aware validation designed to reduce leakage between related observations.
- SHAP summaries used to describe predictive associations rather than causal effects.

Precomputation keeps the public app responsive and limits server cost while preserving a reproducible modelling workflow.

[Open Mobility Safety Intelligence](https://mobility-safety-intelligence.streamlit.app/) · [View the implementation repository](https://github.com/amirhosseintaheri93-collab/mobility-safety-intelligence)
