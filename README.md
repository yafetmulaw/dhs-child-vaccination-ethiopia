# Child Vaccination in Ethiopia: DHS Analysis

> **Summary:** [Add one sentence describing your main finding after completing the analysis. Do not write results before calculating and checking them.]

## Research question

[What aspects of child vaccination coverage in Ethiopia will this project examine? Why does the question matter for public-health programs and monitoring and evaluation (M&E)?]

## Data

- **Source:** Demographic and Health Surveys (DHS) Program
- **Country:** Ethiopia
- **Survey:** [Enter survey name and year after obtaining the approved dataset]
- **File:** Children's Recode (KR)
- **Analytical sample:** [Report the final eligible sample size after applying your inclusion criteria]
- **Access:** https://dhsprogram.com/data/

The DHS data are not included in this repository. See [`data/README.md`](data/README.md) for access and setup instructions.

## Methods

### Outcome and indicators

[Define each vaccination indicator precisely. State which doses/antigens and age-eligibility rules are included, and identify the DHS variables used.]

### Survey design and weighting

[Document the sampling weight, strata, and cluster/primary sampling unit variables used. Explain how you account for the complex survey design. DHS weights are commonly stored with six implied decimal places; document the exact rescaling and implementation used.]

### Analysis

[Describe the descriptive estimates, subgroup comparisons, and any statistical model. Explain why the model is appropriate and how missing data are handled.]

## Key results

**Do not fill this section with estimates until the analysis has been run and validated.**

- [Result 1: e.g., weighted national coverage with confidence interval]
- [Result 2: e.g., regional range and relevant comparison]
- [Result 3: e.g., important associated factors, if supported by the model]

### Visualizations

- [Link to figure in `outputs/figures/`]
- [Link to results table in `outputs/tables/`]
- **Tableau dashboard:** [Add your Tableau Public URL when published]

## Limitations

[Discuss relevant limitations, such as vaccination information recorded from cards versus caregiver recall, missing vaccination records, cross-sectional design, age eligibility, and survey-design/model assumptions. Include only limitations that apply to your analysis.]

## Reproducibility

### Requirements

- Python [version]
- Packages listed in [`requirements.txt`](requirements.txt)

### Setup

1. Obtain the approved Ethiopia Children's Recode (KR) dataset from the DHS Program. See [`data/README.md`](data/README.md).
2. Place the permitted local data file in `data/`. Do not commit or share it.
3. Create and activate a virtual environment.
4. Install dependencies:

   ```bash
   python -m pip install -r requirements.txt
   ```

5. Run the notebooks in numerical order:

   1. `notebooks/01_cleaning.ipynb`
   2. `notebooks/02_indicators.ipynb`
   3. `notebooks/03_modeling.ipynb`

[Document any required configuration, file names, and commands here. Ensure notebooks run from top to bottom before publishing results.]

## Author

**[Your name]**

- LinkedIn: [Your LinkedIn URL]
- Email: [Your public contact email]
