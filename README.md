# ML-based Network Intrusion Analyzer

## Overview

ML-based Network Intrusion Analyzer is a tool designed to process and analyze the ISCX Intrusion Detection Evaluation Dataset. It leverages machine learning techniques to detect and classify network intrusions effectively.

## Features

- Data preprocessing and cleaning
- Feature selection and engineering
- Model training with Random Forest and XGBoost classifiers
- Performance evaluation using metrics like accuracy, precision, recall, and ROC-AUC
- Visualization of results and confusion matrices

## Setup

### Prerequisites

- Python 3.7 or higher
- Required Python libraries:
  - pandas
  - numpy
  - scikit-learn
  - xgboost
  - matplotlib
  - seaborn

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/SanthoshCheemala/ML-based-Network-Intrusion-Analyzer.git
    ```
2. Navigate to the project directory:
    ```bash
    cd ml-network-intrusion-analyzer
    ```
3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Run the Jupyter notebook to start the analysis:
```bash
jupyter notebook ids-fds.ipynb