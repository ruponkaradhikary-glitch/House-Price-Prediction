# House Price Prediction using Machine Learning

An educational Streamlit dashboard that predicts an estimated house price from property features and compares regression models.

## Features
- House price prediction from area, bedrooms, bathrooms, location, age, parking and floor.
- Data analysis charts and downloadable demo CSV.
- Model comparison using MAE, RMSE and R².
- Linear Regression, Random Forest and Gradient Boosting models.
- Responsive Streamlit interface.

## Important data note
The application generates a **synthetic demonstration dataset** at startup. It is not real estate market data, and predictions should not be used for an actual purchase or sale. For real-world use, replace `make_dataset()` with a verified and appropriately licensed dataset, and validate the model for the target region.

## Requirements
- Python 3.10 or newer recommended
- pip

## Installation and run
1. Install Python.
2. Open a terminal in this project folder.
3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Start the app:

   ```bash
   streamlit run app.py
   ```

5. Open the local URL shown in the terminal (usually `http://localhost:8501`).

## Project files
- `app.py` — Streamlit app, dataset generation, model training, prediction and charts.
- `requirements.txt` — Python dependencies.
- `Project_Report.pdf` — project report.
- `README.md` — project overview and instructions.

## Models and evaluation
A held-out test split is used to compare Linear Regression, Random Forest and Gradient Boosting. The dashboard reports:
- **MAE:** average absolute prediction error (lower is better).
- **RMSE:** error measure that penalizes larger errors more (lower is better).
- **R²:** proportion of target variation explained by the model (closer to 1 is better).

## Suggested future improvements
- Add a real, documented local housing dataset.
- Validate on a separate external test set.
- Add data validation and model persistence.
- Deploy the app with Streamlit Community Cloud or another hosting service.

## GitHub submission
Create a new repository on GitHub, upload these project files, and paste the repository's URL into the submission form. Do not paste a URL until the repository has actually been created and made accessible.
