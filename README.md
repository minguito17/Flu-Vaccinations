
# Predicting the 2024 US Presidential Election

## Description / Overview

This project uses historical US presidential election data to model and predict the likely outcome of the 2024 presidential election. By analyzing voting patterns from 1976 to 2020, the team built models to classify state-by-state results and visualize electoral vote projections.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)
- [Authors / Credits](#authors--credits)
- [Contact Information](#contact-information)
- [References / Acknowledgments](#references--acknowledgments)

## Installation

1. Clone the repository:  
   ```
   git clone <YOUR_REPO_URL>
   cd <YOUR_REPO_DIRECTORY>
   ```

2. Install required Python libraries (example):  
   ```
   pip install pandas numpy scikit-learn seaborn matplotlib plotly geopandas xgboost imbalanced-learn
   ```

## Usage

- Load the dataset files:  
  - `Presidents.csv` for historical presidents  
  - `1976-2020-president.csv` for election results  
- Run the provided Python notebooks or scripts to:  
  - Clean and preprocess the data  
  - Group results by state and year  
  - Build classifiers (e.g., Random Forest, Logistic Regression, SVM)  
  - Generate plots of winners by state and party  
  - Visualize electoral maps for 2020 and projected 2024

## Features

- Historical timeline of US presidents from 1977–2024  
- State-level winner prediction tables  
- Class imbalance handling with SMOTE  
- Visualizations with matplotlib, seaborn, and plotly  
- Choropleth maps of state-by-state election results

## Contributing

Pull requests are welcome. Please open an issue first to discuss major changes or improvements.

## License

This project is for academic and educational use only.

## Authors / Credits

- Marinela Inguito
- Katie Mears
- Sadaf Sadegh Vaziri

## Contact Information

- minguito@sandiego.edu

## References / Acknowledgments

- US Presidential election data via Kaggle
- Python libraries: pandas, scikit-learn, seaborn, plotly
- Modeling methods adapted from scikit-learn tutorials and class resources
