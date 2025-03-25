# AnalysisApp

## Overview
**AnalysisApp** is a Python-based desktop application that provides various data analysis and visualization tools for transportation and supplier performance evaluation. The application is built using **Tkinter** for the user interface and **Matplotlib, Seaborn, Pandas, and Scikit-Learn** for data processing, machine learning, and visualization.

## Features
- **Distance and Fuel Analysis**
  - Filters data based on date range.
  - Uses predefined fuel consumption values for different vehicle types.
  - Displays total distance and fuel consumption.
  - Generates bar chart visualizations.

- **Supplier Accuracy Classification**
  - Analyzes supplier delivery performance.
  - Categorizes deliveries as "ontime" or "delayed".
  - Generates pie charts for top 10 on-time and delayed suppliers.

- **Trip Classification using Naïve Bayes**
  - Predicts if trips are **Market** or **Regular**.
  - Uses **Naïve Bayes** classification algorithm.
  - Displays classification accuracy and confusion matrix.

- **Material Booking Analysis**
  - Analyzes supplier performance based on material bookings.
  - Determines the most frequent customer, material, and month for bookings.
  - Generates bar graphs for material shipments.

- **Clustering using K-Means**
  - Performs **K-Means Clustering** on supplier and location data.
  - Visualizes clusters using scatter plots.
  - Filters top 15 suppliers for the "Regular" category.

## Installation
### Prerequisites
Make sure you have Python installed. Then install the required libraries using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn tk
```

### Running the Application
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/AnalysisApp.git
   ```
2. Navigate to the project directory:
   ```bash
   cd AnalysisApp
   ```
3. Run the application:
   ```bash
   python analysis_app.py
   ```

## Usage
1. **Upload CSV File:** Choose a dataset to analyze.
2. **Select Analysis Type:**
   - Fuel and Distance Calculation
   - Supplier Accuracy Classification
   - Trip Classification (Market/Regular)
   - Material Booking Analysis
   - K-Means Clustering
3. **View Results:** The application will generate visualizations and reports.

## Example Data Format
Your CSV file should contain columns like:
```csv
BookingID_Date,supplierNameCode,customerNameCode,Material Shipped,Market/Regular,Origin_Location
2024-03-12,SUP123,CUST001,Steel,Market,New York, USA
2024-04-08,SUP456,CUST002,Wood,Regular,California, USA
```

