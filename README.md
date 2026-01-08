# Transfer Success Predictor

## Description

This project is a comprehensive dashboard for FC Köln (1. FC Köln), a German football club. It provides data analysis, player performance insights, predictive modeling, and visualizations based on historical and current player data. The dashboard is built using Streamlit and incorporates machine learning models for predictions and player similarity analysis.

## Features

- **Player Analysis**: Detailed statistics and performance metrics for FC Köln players.
- **Predictive Modeling**: XGBoost-based predictions for player performance and outcomes.
- **Data Visualization**: Interactive charts and graphs using Matplotlib and Streamlit.
- **Player Similarity**: Find similar players based on attributes using machine learning techniques.
- **Dashboard Interface**: User-friendly web interface for exploring data.

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd fc-koeln-dashboard
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Navigate to the Dashboard directory:
   ```
   cd Dashboard
   ```

2. Run the Streamlit app:
   ```
   streamlit run app_final.py
   ```

3. Open your web browser and go to the provided local URL (usually `http://localhost:8501`).

## Dashboard Link

[Access the live dashboard here](https://transfersuccesspredictor-bvx4pibkt2lnk7ttr4gxcn.streamlit.app/)

## Project Structure

- **Dashboard/**: Contains the main Streamlit application (`app_final.py`) and category mappings (`category_mappings.json`).
- **Data/**: Jupyter notebooks for data preprocessing (`Pre Processing.ipynb`) and analysis (`Capstone Analysis.ipynb`).
- **Model/**: Machine learning models and predictions, including XGBoost model (`XGBoost.ipynb`, `model2.json`) and logistic regression (`Logistic Regression.ipynb`).
- **Docs/**: Documentation files.
- **Graphics/**: Visual assets and images.
- **requirements.txt**: Python dependencies.

## Data

The project uses a final dataset (`final_dataset.csv`) derived from football player statistics. Notebooks in the `Data/` folder detail the preprocessing and analysis steps.

## Models

- XGBoost model for predictions (saved as `model2.json`).
- Logistic regression model.
- Predictions output in `xgboost_predictions_test.csv`.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
