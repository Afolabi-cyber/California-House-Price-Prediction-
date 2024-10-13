# California House Price Prediction App

Welcome to the **California House Price Prediction App**! This app is built using **Streamlit** and leverages a **Random Forest Regressor** to predict median house prices in California based on various housing features. Additionally, it provides feature importance insights using **SHAP (SHapley Additive exPlanations)** to explain the predictions in a transparent and interpretable way.

## Features

- **Interactive Input**: Easily adjust housing features such as median income, house age, population, average number of rooms, and more through intuitive sliders in the sidebar.
- **Real-Time Predictions**: Instantly predict the median house value based on user-defined input values.
- **Model Transparency**: Visualize feature importance using SHAP values, which explain how each feature influences the model’s predictions.
- **User-Friendly**: No coding knowledge required—just run the app and start exploring house price predictions!

## Demo

You can run this app locally by following the instructions in the **Installation** section below.

## Installation

### Prerequisites

- Python 3.7 or higher
- Required Python libraries:
  - `streamlit`
  - `pandas`
  - `scikit-learn`
  - `shap`
  - `matplotlib`

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/california-house-price-prediction.git
   cd california-house-price-prediction
