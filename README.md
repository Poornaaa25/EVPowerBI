# Electric Vehicle Sales Analysis (India) | Power BI Dashboard

This project provides a comprehensive analysis of electric vehicle (EV) sales across Indian states from 2021 to 2024 using Power BI. The visualizations offer insights into sales trends, market penetration, category performance (2-wheeler vs 4-wheeler), and top manufacturers contributing to the EV ecosystem.

## Dashboard Highlights

- State-wise sales and penetration rate
- Category-wise EV sales (2W vs 4W)
- Maker performance (Tata, MG, Mahindra, etc.)
- Year-over-year trends and CAGR
- Cost comparison: EVs vs petrol/diesel
- Peak months and seasonal trends
- Top subsidy-providing states
- Top and bottom performing regions

## Data Sources

The analysis is based on cleaned and structured data from the following files:

### electric_vehicle_sales_by_state.csv
- Date-wise state-level EV sales (2W/4W)
- Total vehicle sales and penetration rate

### electric_vehicle_sales_by_makers.csv
- Monthly sales by EV manufacturers
- Category-specific (2-wheeler or 4-wheeler) sales

### dim_date.csv
- Provides fiscal year and quarter mapping for all dates

For detailed column descriptions, see `meta_data.txt`.

## Key Metrics Used

- Penetration Rate  
  (Electric Vehicles Sold / Total Vehicles Sold) * 100

- Compound Annual Growth Rate (CAGR)  
  CAGR = [(EVs Sold in Final Year / EVs Sold in Initial Year) ^ (1/n)] - 1

## Tools Used

- Power BI Desktop for dashboard creation and DAX modeling
- Power Query for data transformation
- CSV/Excel as the primary data source

## Insights and Findings

- Kerala and Delhi lead in EV penetration
- Tata Motors is the top EV manufacturer
- 4-wheelers dominate the EV market in metro regions
- EVs are significantly cheaper to run than petrol or diesel vehicles
- Government policies like FAME II significantly drive adoption

## Getting Started

1. Clone the repository
2. Open `Electric Vehicle.pbix` in Power BI Desktop
3. Refresh the data or connect your own dataset
4. Explore dashboards and export insights

## License

This project is released under the MIT License.

## Acknowledgments

- Data inspiration from open government sources and mobility reports
- Built as a capstone/data visualization project to explore India's EV ecosystem
