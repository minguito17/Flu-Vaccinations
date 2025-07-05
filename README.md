
# Predictive Modeling of Patient Preferences for H1N1 and Seasonal Flu Vaccination

## Description / Overview

This project aims to build a predictive model to analyze patient preferences for H1N1 and seasonal influenza vaccine uptake. Using survey data collected during the 2009 H1N1 pandemic, the team applies classification techniques to support public health decision-making, resource allocation, and evidence-based vaccination programs.

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

2. Install required Python packages:  
   ```
   pip install pandas numpy scikit-learn seaborn matplotlib klib PyDP boruta
   ```

3. Use Jupyter Notebook or Deepnote for running notebooks collaboratively.

## Usage

- Load the training and test datasets: `training_set_features.csv`, `training_set_labels.csv`.
- Use Python scripts or notebooks to:
  - Clean and preprocess data (handle missing values, one-hot encode categorical features).
  - Apply feature selection techniques (Boruta).
  - Train classification models (Logistic Regression).
  - Evaluate performance using confusion matrix, prediction accuracy, and recall.
  - Apply Privacy Enhancing Technologies (PETs) to ensure compliance with privacy requirements.

## Features

- Predicts patient likelihood of receiving H1N1 vs seasonal flu vaccine.
- Uses logistic regression and feature selection for robust results.
- Applies differential privacy measures to protect sensitive health data.
- Supports evidence-based vaccine production and distribution planning.
- Provides visualization tools for EDA.

## Contributing

Pull requests are welcome. Please open an issue first to discuss proposed changes.

## License

This project is for academic research and educational use only. All patient data must be handled in compliance with HIPAA and other privacy laws.

## Authors / Credits

- Jose Guarneros Padilla
- Marinela Inguito
- Jeel Patel

## Contact Information

For questions, please contact the project team through your university or course platform.

## References / Acknowledgments

- Centers for Disease Control and Prevention (CDC) H1N1 Public Use Data Files  
- DrivenData Flu Shot Learning Competition  
- Smart Vision Europe: CRISP-DM Methodology  
- PyDP Documentation for Differential Privacy  
- AIMultiple: Privacy Enhancing Technologies  
- Various academic articles and open-source libraries (Boruta, Seaborn, Matplotlib)
