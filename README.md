## Quickstart

1. Download the [data](https://drive.google.com/drive/folders/1hGVPjkCnaAxX8XAPr-RMjpDp6KsXeFT5?usp=drive_link), or for the complete dataset you can check out the original [kaggle competition](https://www.kaggle.com/competitions/hms-harmful-brain-activity-classification/overview).
2. Run the `hms_starter.ipynb` notebook.

## Environment Setup
There's a great guide on how to get started [here](https://scikit-learn.org/stable/install.html); I've extracted the most useful snippets in this document.

### Conda install (preferred)
```shell
conda create --name hms_hackathon -c conda-forge --file requirements.txt
conda activate hms_hackathon
```

### Mac/Linux pip install
```shell
python -m venv hms_env
source hms_env/bin/activate
pip install -r requirements.txt
```

### Windows pip install
```shell
python -m venv hms-env
hms-env\Scripts\activate  # activate
pip install -r requirements.txt
```
