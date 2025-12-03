# ifood-case

Case study analysis for iFood data science challenge.

## Project Structure

```
ifood-case/
├── data/                          # Datasets
│   ├── raw/                       # Dados originais
│   └── processed/                 # Dados processados
├── notebooks/                     # Jupyter notebooks
│   ├── 1_data_processing.ipynb    # Data processing and EDA
│   └── 2_modeling.ipynb           # Model training and evaluation
├── presentation/                  # Slides para stakeholders
├── src/                           # Código fonte (opcional)
├── README.md                      # Project documentation
└── requirements.txt               # Python dependencies
```

## Getting Started

### Prerequisites

- Python 3.10+
- pip
- PySpark

### Installation

1. Clone the repository:
```bash
git clone https://github.com/castroisabel/ifood-case.git
cd ifood-case
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

### Running the Notebooks

1. Start Jupyter:
```bash
jupyter notebook
```

2. Open the notebooks in order:
   - `notebooks/1_data_processing.ipynb` - Data processing and exploratory analysis
   - `notebooks/2_modeling.ipynb` - Model training and evaluation

## Data

- Place raw data files in `data/raw/`
- Processed data will be saved to `data/processed/`

## Features & Highlights

- Development of a propensity model to predict the probability of offer success.

- Generation of user-offer combinations and ranking based on predicted success.

- Model evaluation using metrics such as ROC AUC, precision, recall, and F1-score.

- Feature importance analysis with permutation importance.

- Recommendations for next steps including threshold optimization, uplift modeling, and ROI tracking.

## License

This project is for educational purposes.