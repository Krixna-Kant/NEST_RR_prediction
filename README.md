# Recruitment Rate Prediction in Clinical Trials

This project aims to predict recruitment rates (RR) for clinical trials using advanced machine learning models. The solution benchmarks recruitment rates, providing key insights to aid clinical trial planning and resource allocation.

## Project Overview

- **Problem Statement**: Recruitment challenges in clinical trials often lead to prolonged timelines and financial losses. This project develops a precision predictive model to enhance recruitment planning and reduce uncertainty.
- **Key Features**:
  - Internal and external feature engineering.
  - Advanced machine learning models for prediction (Random Forest, Gradient Boosting, XGBoost).
  - Benchmarking and visual insights using Streamlit and Plotly.
  - SHAP-based feature interpretability.

## Methodology

### Data Preprocessing
- Filling missing values and transforming categorical data.
- Feature engineering:
  - Internal Factors: Study Phases, Study Type, Log Enrollment, and more.
  - External Factors: Competition Index, Disease Rarity Index, and Geographical Distribution.

### Models and Techniques
- **Random Forest Regression**: Baseline model.
- **Gradient Boosting Machines (GBM)**: Iterative learning for improved accuracy.
- **XGBoost**: Best-performing model with robust feature handling and interpretability.
- **Evaluation Metrics**: RMSE, MAE, R².

## Results
- XGBoost achieved the best performance with:
  - RMSE: 3.02
  - MAE: 1.21
  - R²: 0.58

## Visualization
- Recruitment rate distribution and benchmarks visualized via:
  - Correlation matrix.
  - Scatter plots and bar charts.
  - SHAP summary for feature impact.

## How to Run

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd recruitment-rate-prediction

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the Streamlit app for dynamic benchmarking:
   ```bash
   streamlit run app.py

4. For model training and prediction:
   ```bash
   squirtle_rr_prediction.ipynb

# Files

- **`squirtle_rr_prediction.ipynb`**: Core script for data preprocessing, model training, and evaluation.
- **`app.py`**: Streamlit-based app for dynamic benchmarking and predictions.
- **`requirements.txt`**: List of dependencies.
- **Sample dataset**: Ensure the dataset (`usecase_4_.xlsx`) is placed in the project directory.

---

# Tools and Frameworks

- **Libraries**: Pandas, NumPy, Scikit-learn, XGBoost, SHAP, Matplotlib, Seaborn, Plotly.
- **Environment**: Python 3.10, Google Colab, Streamlit.
- **Visualization**: Interactive benchmarking dashboards.

---

# Contributors

- **Krishna**
- **Ashish K Choudhary**

**Contact**: [kant19krishna@gmail.com](mailto:kant19krishna@gmail.com)
