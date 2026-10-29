# airflow-learning

Learning project for Apache Airflow 3.3.

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
airflow standalone
```

## Notes

On Python 3.15 the Airflow CLI prints `FileType is deprecated` warnings (from Airflow's
own argparse usage). They are harmless; silence them with:

```bash
export PYTHONWARNINGS="ignore::PendingDeprecationWarning"
```
