# Data Analyst — Udacity

Repository with projects developed during the **[Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002)** by Udacity.

## Projects

| # | Project | Description | Techniques |
|---|---------|-------------|------------|
| 1 | [Investigate a Dataset](project_1/) | Exploratory data analysis on a no-show medical appointments dataset to identify factors that influence patient attendance | Exploratory Data Analysis (EDA) |
| 2 | [Data Wrangling](project_2/) | Gathering, assessing, and cleaning U.S. inflation (CPI) and S&P 500 datasets to explore the relationship between inflation and stock market performance | Data Wrangling, FRED API, Data Cleaning, Data Merging |

## Technologies

- Python 3.x
- NumPy · Pandas · Matplotlib · Seaborn · fredapi
- Jupyter Notebook

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/marcosquant/data-analyst.git
   cd data-analyst
   ```

2. Install the dependencies (recommended via [Anaconda](https://www.anaconda.com/)):
   ```bash
   pip install numpy pandas matplotlib seaborn jupyter fredapi
   ```

3. Before running Project 2, set your FRED API key as an environment variable:

   ```powershell
   $env:FRED_API_KEY="your_api_key"
   ```

   Keep the real value only in your local environment. Never add it to a
   notebook, source file, or Git commit.

4. Navigate to the project folder and open the notebook:
   ```bash
   cd project_1
   jupyter notebook Investigate_a_Dataset.ipynb
   ```

## Author

**Marcos Roberto Souza** — [Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002), Udacity.
