# Black Friday Data Analysis

Exploratory analysis and preprocessing of the [Black Friday dataset](https://www.kaggle.com/datasets/sdolezel/black-friday) from Kaggle (~550K purchase records).

## Features

- Explores every column with value counts, histograms, and box plots
- Handles missing values in `Product_Category_2` and `Product_Category_3`
- Answers business questions about purchases by gender, age, city, and marital status
- Prepares the data for ML with encoding, a train/test split, and scaling

## Tech Stack

Python · Pandas · NumPy · Plotly · Matplotlib · Seaborn · Scikit-learn · Category Encoders

## Project Structure

| File | Description |
|------|-------------|
| `black_friday.csv` | Dataset |
| `Analyze_black_friday_kaggle.ipynb` | Data exploration and business questions |
| `preprocessing_on_black_friday_kaggle.ipynb` | Encoding, splitting, and scaling |

## Setup

```bash
git clone https://github.com/yusephbarghash/black_friday_data_analysis.git
cd black_friday_data_analysis
pip install pandas numpy plotly matplotlib seaborn "scikit-learn<1.2" category_encoders jupyter
```

## Usage

```bash
jupyter notebook
```

Run `Analyze_black_friday_kaggle.ipynb` first, then `preprocessing_on_black_friday_kaggle.ipynb`.
