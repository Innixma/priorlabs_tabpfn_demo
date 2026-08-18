# Prior Labs TabPFN Demo

Hands-on demos of [TabPFN-3](https://priorlabs.ai/technical-reports/tabpfn-3) and its
[thinking mode](https://docs.priorlabs.ai/capabilities/thinking-mode). The notebooks run
on the TabPFN API — no GPU required — with a free access token from
[ux.priorlabs.ai](https://ux.priorlabs.ai).

## Notebooks

| Notebook | What it covers | Open in Colab |
|---|---|---|
| [`01_thinking_mode.ipynb`](notebooks/01_thinking_mode.ipynb) | TabPFN-3 thinking mode wins on gradient boosting's home turf: XGBoost vs TabPFN-3 with and without thinking on a wide high-cardinality categorical dataset -- one switch flips the outcome | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Innixma/priorlabs_tabpfn_demo/blob/main/notebooks/01_thinking_mode.ipynb) |
| [`02_bring_your_own_data.ipynb`](notebooks/02_bring_your_own_data.ipynb) | Thinking mode on your own dataset: classification or regression, demo datasets or your own CSV, with the full thinking-mode option surface (`thinking_effort`, `thinking_metric`, `thinking_timeout_s`) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Innixma/priorlabs_tabpfn_demo/blob/main/notebooks/02_bring_your_own_data.ipynb) |
