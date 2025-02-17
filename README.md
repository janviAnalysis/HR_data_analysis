# HR Data Analysis Dashboard

This project analyzes HR data to gain insights into employee demographics, service years, promotion status, and distance from the workplace. The interactive dashboard provides a comprehensive overview of key HR metrics and trends.

## Project Overview

The dashboard is designed to provide HR professionals and stakeholders with a user-friendly tool for exploring employee data. Key features include:

- **Total Employee Count and Gender Distribution:** Displays the total number of employees and the percentage distribution of male and female employees.
- **Promotion Status:** Shows the number and percentage of employees due for promotion and those not due.
- **Service Year Analysis:** Visualizes the distribution of employees across different service year ranges.
- **Distance from Workplace:**  Categorizes and displays the number and percentage of employees based on their distance from the workplace (Very Far, Very Close, Close).
- **Job Level Distribution:** Shows the distribution of employees across different job levels.

## Data Source

The data used for this analysis is stored in an Excel file available on GitHub: [HR Data.xlsx](https://github.com/janviAnalysis/HR_data_analysis/blob/main/HR%20Data.xlsx)

## Data Transformation and Cleaning

The HR data was processed to ensure data quality and consistency. This included:

- **Data Type Conversion:**  Converting relevant columns to appropriate data types (e.g., numeric for service years, job levels).
- **Categorical Encoding:**  Encoding categorical variables (e.g., gender, distance) into numerical representations using one-hot encoding for analysis and visualization.
- **Handling Missing Values:** Missing values, if any, were assumed to be minimal and handled by dropping rows with missing data for simplicity.

## Exploratory Data Analysis (EDA)

Exploratory data analysis was conducted to understand patterns and trends in the HR data:

- **Descriptive Statistics:**  Calculating summary statistics for relevant variables (e.g., mean, median service years, job level distribution).
- **Data Visualization:** Creating visualizations using bar charts for job levels, pie charts for gender distribution, and potentially scatter plots or histograms for service year analysis and distance.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Streamlit

## Setup and Installation

1. Clone the repository: `git clone https://github.com/janviAnalysis/HR_data_analysis.git`
2. **Set up the environment:**
   - Ensure you have Python 3.7 or higher installed.
   - Create a virtual environment (recommended): `python3 -m venv venv` (Windows: `python -m venv venv`)
   - Activate the environment: `source venv/bin/activate` (Windows: `venv\Scripts\activate`)
   - Install dependencies: `pip install -r requirements.txt` (Create `requirements.txt` with `pandas`, `matplotlib`, `seaborn`, `streamlit` inside).

## Usage

1. Navigate to the project directory: `cd HR_data_analysis`
2. Run the dashboard: `streamlit run your_dashboard_script.py` (Replace `your_dashboard_script.py` with your actual script name)
3. Interact with the dashboard:
   - Explore the different visualizations and metrics displayed.
   - The dashboard likely features interactive elements (filters, dropdowns, etc.) to allow users to explore specific aspects of the data.  Experiment with these to gain deeper insights.
   - The visualizations are designed to highlight key trends in employee demographics, service years, promotion status, and distance from the workplace.  Pay attention to the titles and labels to understand what each chart represents.

## Contributions

Contributions are welcome! Please feel free to submit pull requests or open issues for any suggestions or improvements.

## Contact

Janvi Ambazhakan - janviambazhakan@gamil.com
