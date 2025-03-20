# cars24-price-analysis

This project analyzes data from Cars24, a popular online marketplace for buying and selling used cars in India, to identify key factors affecting used car prices.

## Key Findings

- Engine capacity is the strongest predictor of car price
- Newer cars command significantly higher prices (each year reduces value by ~₹38,000)
- Automatic transmission adds a premium of about ₹51,000
- Each 10,000 km driven reduces price by approximately ₹3,600
- The model explains approximately 83% of price variation (R² = 0.83)

## Dataset

The dataset contains information on 1,445 used cars including:
- Model and manufacturing year
- Price and kilometers driven
- Engine capacity and fuel type
- Transmission type
- Ownership history
- Physical condition metrics

## Requirements

- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- statsmodels

## Usage

1. Clone this repository
2. Install the required packages: `pip install -r requirements.txt`
3. Run the analysis: `python cars24_analysis.py`

## Visualizations

