# PySpark Learning Notes

A collection of notebooks documenting my hands-on learning of Apache Spark's Python API. This repository is a learning notebook collection, not a production data pipeline.

## Topics covered

### Getting started
- [01 — Spark session](./getting_starting/01-spark-session.ipynb)
- [02 — Spark DataFrame](./getting_starting/02-spark-dataframe.ipynb)
- [03 — Transformations and actions](./getting_starting/03-transformations-and-actions.ipynb)
- [04 — Exploring transformations](./getting_starting/04-exploring-transformations.ipynb)
- [05 — Creating DataFrames](./getting_starting/05-creating-dataframe.ipynb)

### Data types and schemas
- [Schema on read](./datetypes_and_schemas/01-schema-on-read.ipynb)

## Environment

The notebooks include examples originally authored in a Databricks notebook environment; some cells reference Databricks-specific objects, sample tables, or display helpers. Those cells may need adaptation in a local Jupyter environment.

For local practice, use a compatible Java installation and install PySpark in a Python environment:

```bash
python -m pip install pyspark jupyter
jupyter notebook
```

Open the notebook you want to study and run cells in order. If a notebook uses a Databricks table such as `dev.spark_db.diamonds`, replace that example with a dataset available in your own environment.

## Current focus

- Creating Spark sessions and DataFrames
- Understanding transformations versus actions
- Defining schemas and working with data types
- Practicing distributed-data-processing fundamentals

## Scope

These notebooks are learning exercises. A notebook being present in the repository does not imply that every cell has been tested in a fresh local environment.
