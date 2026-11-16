# Notebook run order

Create the analysis notebooks in this order:

1. `01_cleaning.ipynb` — load the approved local KR file, inspect the data, define the eligible sample, clean variables, and document exclusions.
2. `02_indicators.ipynb` — define vaccination indicators and calculate design-appropriate weighted estimates, including uncertainty.
3. `03_modeling.ipynb` — fit and diagnose the planned model; report estimates with appropriate uncertainty and caveats.

Run each notebook from top to bottom. Keep reusable functions and configuration clear, and avoid embedding restricted respondent-level data in outputs.
