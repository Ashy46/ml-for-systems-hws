# ML for Systems: Homework

Homework for CSMC-25422 (Machine Learning for Systems), University of Chicago.

Each assignment lives in its own folder with its notebook, rubric, and data.

## Assignments

| # | Folder | Topic |
|---|---|---|
| 1 | [`assignment-1/`](assignment-1/) | Video Quality Inference |

## Setup

```
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

Datasets are kept compressed (`.pkl.xz`) in git. `pandas.read_pickle` reads them directly, so there is no need to decompress.
