# Interactive Dashboard Instructions

## Overview
The interactive dashboard provides a Power BI-like experience for exploring and visualizing your data. It includes features like dynamic filtering, multiple chart types, KPI cards, data summaries, and AI-powered data classification.

## How to Launch the Dashboard

There are three ways to launch the dashboard:

### Option 1: Using the Excel Converter Application
1. Run `excel_converter.py`
2. Convert an Excel file to JSON
3. Click the "Launch Interactive Dashboard" button

### Option 2: Using the Batch File
1. Double-click `launch_dashboard.bat`
2. The batch file will automatically find and use the most recent JSON file

### Option 3: Using the Command Line
1. Open a command prompt
2. Navigate to the project directory
3. Run: `python launch_dashboard.py path/to/your/data.json`

## Accessing the Dashboard

Once launched, the dashboard will be available at:
**http://localhost:8050**

You can access it from any web browser on your computer.

## Dashboard Features

### 1. Chart Controls
- **Chart Type**: Choose from bar charts, line charts, scatter plots, pie charts, and box plots
- **X-Axis**: Select the column to use for the X-axis
- **Y-Axis**: Select the numeric column to use for the Y-axis
- **Category Filter**: Filter data by a categorical column

### 2. Key Metrics
- **KPI Cards**: Shows average, median, and range for the selected numeric column
- **Data Summary**: Provides an overview of the dataset including record count and feature types

### 3. AI Classification Results
- **Cluster Visualization**: Shows data clusters identified by the AI
- **Classification Info**: Provides details about the clusters and their characteristics

### 4. Data Preview
- **Data Table**: Shows a preview of the data with adjustable number of rows

## Troubleshooting

If the dashboard doesn't appear:
1. Make sure you have all required packages installed (`pip install -r requirements.txt`)
2. Check that the JSON file exists and is valid
3. Try accessing the dashboard URL directly in your browser: http://localhost:8050
4. If using the Excel Converter, make sure you've converted a file first

## Closing the Dashboard

To close the dashboard:
1. Press `Ctrl+C` in the terminal/command prompt where the dashboard is running
2. Close the browser tab

---

For more information or support, please refer to the project documentation.