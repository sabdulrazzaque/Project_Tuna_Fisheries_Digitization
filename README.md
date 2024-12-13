**Tuna Fisheries Data Sheets**

This repository contains an interactive data visualization dashboard for analyzing tuna fisheries data sheets. Built with Pandas, Panel, and Plotly, the dashboard enables dynamic data exploration and visualization.

**Features**
**Dynamic Filtering:**
- Filter data by registration numbers, year range, and total sheets range using intuitive widgets.
- Reset filters to return to the default dataset view.

**Interactive Visualizations:**
Generate charts dynamically, including:
- Scatter Plot
- Histogram
- Bar Chart
- Line Chart
- Box Plot
- Heatmap
- Cumulative Trend

**Key Performance Indicators (KPIs):**
  Automatically updated metrics based on filters:
- Total registrations
- Total sheets
- Average sheets per registration
- Median sheets
- Maximum sheets
- Standard deviation

**Theme Toggle:**
- Switch between dark and light themes for better readability.

**Getting Started**

**Prerequisites**
Ensure you have the following installed:

- Python 3.8+
- Required Python libraries:
- pandas
- plotly
- panel
- openpyxl (for reading Excel files)

**Clone the repository:**
bash
Copy code
git clone https://github.com/sabdulrazzaque/tuna-fisheries-data-sheets.git
cd tuna-fisheries-data-sheets
Place your dataset at the specified path in the file_path variable in the script (dashboard.py). Update the file_path if necessary.

**Run the dashboard:**
bash
Copy code
panel serve dashboard.py --show
The dashboard will open in your default browser. If not, navigate to http://localhost:5006/dashboard in your browser.

**Dataset Requirements**
The dashboard requires an Excel file with the following columns:
- Reg No.: Unique registration numbers.
- Year: Year associated with the records.
- Total sheets: Number of sheets for each record.
If the dataset doesn’t meet these requirements, the dashboard falls back to a sample dataset for demonstration purposes.

**Usage**
- Filter Data: Use widgets to filter data based on registration numbers, year range, and total sheets.
- Explore KPIs: View automatically updated metrics.
- Visualize Data: Navigate through the following charts:
- Scatter Plot
- Histogram
- Bar Chart
- Line Chart
- Box Plot
- Heatmap
- Cumulative Trend
- Reset Filters: Reset filters for a broader dataset view.

**Troubleshooting**
No Data Available: If no data appears:
Adjust the filters to include more data.
Verify the dataset for completeness and format requirements.
Dataset Issues: If the file path is incorrect or the file is missing, the dashboard uses a default sample dataset.
