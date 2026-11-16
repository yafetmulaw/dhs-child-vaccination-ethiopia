# Data access and local setup

This repository does not contain DHS microdata. DHS datasets are subject to access conditions and must not be redistributed.

1. Register or sign in at the [DHS Program website](https://dhsprogram.com/data/).
2. Submit a data request for the **Ethiopia Children's Recode (KR)** dataset for the survey selected for this project. Follow the DHS Program's current application and access instructions.
3. After approval, download the relevant file and place it in this local `data/` directory.
4. Keep the original downloaded file unchanged. Record its survey name, year, file name, and access date in your private project notes if useful.
5. Do not upload the dataset, screenshots containing respondent-level records, or other restricted microdata to GitHub or any public service.

The analysis notebooks should refer to a documented local file path. If the downloaded file name differs from the one used in the notebooks, update the path in the configuration cell.

Files in this directory are excluded by `.gitignore`, except for this README.
