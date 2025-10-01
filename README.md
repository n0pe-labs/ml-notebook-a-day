# ml-notebook-a-day

One small machine-learning experiment per day — mostly scikit-learn, pandas and
matplotlib, Kaggle-notebook style. Each notebook is self-contained: it generates
(or loads) its own data, runs an experiment, and records the takeaways.

## Layout

- `notebooks/YYYY-MM-DD_<topic>.ipynb` — one notebook per day
- `requirements.txt` — Python dependencies

## Run a notebook

```bash
pip install -r requirements.txt
jupyter notebook notebooks/<file>.ipynb
```

Every notebook pins its random seed, so re-running reproduces the numbers.
