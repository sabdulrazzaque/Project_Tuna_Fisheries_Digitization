# Interactive Data Analysis Dashboard

This repository contains an interactive dashboard for analyzing Total Sheets data using Python, Pandas, and Panel with Plotly visualizations. The dashboard allows users to filter data dynamically, view key performance indicators (KPIs), and explore data through various charts.

---

## Features

- **Interactive Filters**: Filter data by registration numbers, years, and total sheets.
- **Dynamic Visualizations**: Includes scatter plots, bar charts, line charts, histograms, box plots, heatmaps, and cumulative charts.
- **Theme Toggle**: Switch between light and dark mode for enhanced viewing experience.
- **Reset Filters**: Quickly reset all filters to start fresh.
- **Real-Time KPIs**: Displays metrics like total registrations, total sheets, average sheets per registration, and more.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sabdulrazzaque/Project_Tuna_Fisheries_Digitization.git
   cd Project_Tuna_Fisheries_Digitization
Install the required Python packages:

bash
Copy code
pip install -r requirements.txt
Ensure the data file is accessible at the specified path or adjust the file_path in the code:

python
Copy code
file_path = r'D:\Project_Tuna_Fisheries_Data_Entry\Data\Python\TFDF File Main database_09-12-2024.xlsx'
Run the dashboard:

bash
Copy code
panel serve Dashboard_v2.ipynb

**Dependencies**
Python: 3.8 or later
Panel: For interactive UI components
Plotly: For dynamic visualizations
Pandas: For data manipulation
OpenPyXL: For working with Excel files
Install all dependencies using the command:

bash
Copy code
pip install panel plotly pandas openpyxl


**How to Use**
Launch the dashboard using panel serve.
Use the provided filters to narrow down the dataset.
Explore KPIs and visualizations in real time.
Toggle between light and dark themes for your preference.
Reset filters if needed to start fresh.

**Dashboard Overview**

Filters: Select specific registration numbers, years, or total sheets to filter data.
KPIs: Displays:
Total Registrations
Total Sheets
Average Sheets per Registration
Median Sheets per Registration
Maximum Sheets by a Registration
Standard Deviation of Sheets

**Charts:**

Scatter Plot
Histogram
Bar Chart
Line Chart
Box Plot
Heatmap
Cumulative Chart

**Data Requirements**

The data file should be an Excel sheet with at least the following columns:

Reg No.: Unique registration number.
Year: Year of data entry.
Total sheets: Number of total sheets.
If any required columns are missing, the program will raise an error.

**Error Handling**
If the specified file is not found or is invalid, a sample dataset is used for demonstration purposes.
Missing or invalid columns in the dataset will raise an appropriate error.
An empty dataset after filtering prompts the user to reset filters or adjust their selections.


**Acknowledgments**
This project leverages the power of Python's data manipulation and visualization libraries to create an interactive and insightful dashboard for data analysis.

**Screenshots**
![image](https://github.com/user-attachments/assets/00d9f9de-af5b-4183-a4d5-3d2cebd47a92)

![image](https://github.com/user-attachments/assets/320b4bd2-cc23-4fb6-b6d6-df92ebb54a0d)

![image](https://github.com/user-attachments/assets/ccc770c8-337c-4243-b050-c058b6e0c685)

![image](https://github.com/user-attachments/assets/7c1afc42-a643-4de4-8382-25d13c4e4bc4)

![image](https://github.com/user-attachments/assets/038a2f82-69c4-4a39-8ffb-241f71c7f51f)

![image](https://github.com/user-attachments/assets/f364a748-bf77-40f9-9baa-bb8a859dc0fa)

![image](https://github.com/user-attachments/assets/c397db4c-0d3c-48f9-9651-27159dcbd059)

![image](https://github.com/user-attachments/assets/d430e9af-427d-4525-9707-85f9869069b1)












