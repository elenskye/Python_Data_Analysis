# Python Data Analysis Portfolio

A collection of six self-directed Python exercises covering data cleaning, exploratory analysis, statistical testing, visualisation, data organisation, and regression modelling. Each project keeps its original notebook and source material together so it can be reviewed independently.

## Projects

| Project | Focus | Main tools |
|---|---|---|
| [Iris Species Analysis](<projects/01-iris-species-analysis/Analyzing Iris Species Data.ipynb>) | Compare iris measurements through exploratory analysis and statistical testing | pandas, SciPy, Seaborn, Matplotlib |
| [UK E-commerce Data Cleaning](<projects/02-uk-ecommerce-data-cleaning/Evaluation and Clean-up of UK E-commerce Company Sales Data.ipynb>) | Assess missing, duplicate, inconsistent, and invalid transaction data before cleaning | pandas |
| [Netflix Data Organisation](<projects/03-netflix-data-organisation/Organizing Netflix Movie Actor Rating Data.ipynb>) | Combine title and credit data to organise actor ratings by genre | pandas |
| [Housing Price Prediction](<projects/04-housing-price-linear-regression/Predicting Housing Prices Using Linear Regression.ipynb>) | Prepare housing attributes and fit a linear regression model for price prediction | pandas, Seaborn, Matplotlib, statsmodels |
| [Titanic Survival Prediction](<projects/05-titanic-logistic-regression/Predicting Titanic Survival Using Logistic Regression.ipynb>) | Clean passenger data, explore survival patterns, and fit a logistic regression model | pandas, NumPy, Seaborn, Matplotlib, statsmodels |
| [Palmer Penguins Visualisation](<projects/06-palmer-penguins-visualisation/Visualizing Palmer Archipelago Penguin Data.ipynb>) | Explore penguin measurements through statistical visualisation | pandas, NumPy, Seaborn, Matplotlib |

## Repository Structure

```text
projects/
├── 01-iris-species-analysis/
├── 02-uk-ecommerce-data-cleaning/
├── 03-netflix-data-organisation/
├── 04-housing-price-linear-regression/
├── 05-titanic-logistic-regression/
└── 06-palmer-penguins-visualisation/
```

Each folder contains one analysis document and its original data archive or material file when available.

## Running the Analyses

1. Clone the repository and enter the folder for the project you want to run.
2. Extract that project's data archive into the same folder as the notebook.
3. Install Jupyter and the libraries used across the portfolio:

   ```bash
   python -m pip install jupyter pandas numpy scipy seaborn matplotlib statsmodels
   ```

4. Start Jupyter and open the notebook:

   ```bash
   jupyter notebook
   ```

## Data and Format Notes

- The UK e-commerce notebook expects `e_commerce.csv`; the dataset is not included in the repository.
- On case-sensitive systems, rename the extracted Palmer Penguins dataset from `penguins.csv` to `Penguins.csv` before running the analysis.
- The Palmer Penguins analysis is an HTML export retained under its original `.ipynb` filename; open it in a browser rather than Jupyter.
- Notebook and data-file contents are preserved as originally authored; this update changes only repository organisation and documentation.
