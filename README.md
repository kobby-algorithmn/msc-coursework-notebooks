# MSc coursework notebooks

Analysis notebooks from MSc Computer Science modules, kept with their executed
outputs so the results can be read without re-running anything.

## Contents

| Folder | Notebook | Status |
|---|---|---|
| `nyc-taxi-dask/` | `nyc_taxi_fare_dask_workflow.ipynb`: an end-to-end big-data workflow on the Kaggle NYC Taxi Fare Prediction dataset using Dask (loading, cleaning, feature engineering, exploratory analysis, model training and evaluation) | Complete; executed in Google Colab, all outputs saved |
| `lending-club/` | Lending Club machine-learning notebook | Planned. Not yet added |

## How to run

The taxi notebook was run in Google Colab. It looks for the dataset's
`train.csv` (about 5.7 GB) under `/content` or `/content/drive/MyDrive`.

1. Download the dataset from the Kaggle competition
   "New York City Taxi Fare Prediction".
2. Put `train.csv` in your Colab session or Google Drive.
3. Install the dependencies (`pip install -r requirements.txt`) if you are not on Colab.
4. Run the notebook from top to bottom.

The dataset itself is not included in this repository.

## Folder layout

```
msc-coursework-notebooks/
├── nyc-taxi-dask/
│   └── nyc_taxi_fare_dask_workflow.ipynb
├── requirements.txt
└── README.md
```

## Notes

- Assessment briefs, coversheets and submitted reports are deliberately not included.
- All figures and metrics are the notebook's own saved outputs; nothing has been
  added or edited after execution.
- Developed with AI assistance (Claude).

## Licence

All rights reserved. This is coursework and is shared for reference only.
