# TabArena - Tabular IID Dataset Curation Repository

This repository contains the code and metadata from the curation efforts for TabArena-v0.1.
In detail, the curation efforts were focused on IID tabular data.

**Note:** This repository is archived; all future data curaiton is done in: https://github.com/TabArena/tabarena_dataset_curation

## Contributing Data - New Dataset or Feedback

If you want to contribute a new dataset or provide feedback on the currently included dataset, **please open an issue**!
They issue templates will further guide you. We look forward to work with you to improve the curation of datasets or
integrate new datasets into TabArena.

## Repository Overview

This repository contains the following directories:

* `dataset_collection_scripts`: Scripts to collect datasets from various sources and check for duplicates.
* `dataset_creation_scripts`: Scripts to create datasets, their tasks, and aggregate their metadata.
* `dataset_insight_scripts`: Scripts to obtain insights about our curated datasets collection.

## Install

Assuming you created a virtual environment, you can install the package using:

```bash
pip install uv
uv pip install -r requirements.txt
```

Currently, we are using the `pyproject.toml` only for the ruff configuration.
