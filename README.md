# Superstore EDA Dashboard

This project is a Streamlit-based dashboard for exploratory data analysis (EDA) on Superstore sales data. The dashboard allows users to upload datasets, filter data by date and region, and visualize key sales metrics using interactive charts and graphs.

## Features
- **Data Upload**: Upload datasets in CSV or Excel format.
- **Date Range Filtering**: Filter data by selecting a custom date range.
- **Regional Filtering**: Filter data based on region, state, and city.
- **Interactive Visualizations**:
  - Bar charts for category-wise sales.
  - Pie charts for region-wise and segment-wise sales.
  - Time series analysis for monthly sales trends.
  - Treemap for hierarchical sales analysis.
  - Scatter plot for visualizing the relationship between sales, profit, and quantity.
- **Data Download**: Download filtered data and summary tables as CSV files.
- **Expandable Views**: View detailed data summaries and tables interactively.

## Tech Stack
- **Python**: Core programming language.
- **Streamlit**: For creating the interactive dashboard.
- **Plotly**: For creating advanced visualizations.
- **Pandas**: For data manipulation and analysis.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/your-username/superstore-eda-dashboard.git
   cd superstore-eda-dashboard
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

3. Run the application:
   ```
   streamlit run dashboard.py
   ```

## Dataset
The dashboard uses the `Superstore.xlsx` dataset, which should be placed in the project directory. Users can also upload their own datasets through the dashboard interface.

## Visualizations
1. **Category-wise Sales Analysis**: Displays sales distribution across product categories using bar charts.
2. **Region-wise Sales Analysis**: Shows sales contribution from different regions using pie charts.
3. **Time Series Analysis**: Plots sales trends over time.
4. **Hierarchical Treemap**: Provides a detailed view of sales by region, category, and sub-category.
5. **Scatter Plot**: Illustrates the relationship between sales, profits, and quantities sold.

## Future Enhancements
- Add support for more file formats like JSON.
- Incorporate machine learning for sales predictions.
- Allow users to customize charts and metrics dynamically.
- Add user authentication to save and load filters or custom settings.

## Contribution
Contributions are welcome! Please create a pull request with detailed information about the changes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---
