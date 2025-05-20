# Integrating Public Transportation and Educational Data for Enhanced Urban Planning

This project demonstrates how to integrate public transportation data with educational institution data in Abu Dhabi to enhance urban planning and development. The integration aims to provide insights into optimizing transportation routes and improving educational access.

## Prerequisites
- Python 3.x
- Pandas library
- Datasets: Abu Dhabi Public Transportation Network Data (CSV), Abu Dhabi Educational Institutions Data 2024 (XLSX)

## Setup
1. Clone the repository:
   bash
   git clone <repository_url>
   cd <repository_name>
   

2. Install the required Python packages:
   bash
   pip install pandas
   

3. Ensure the datasets are available in the repository folder:
   - `abu_dhabi_transportation_data.csv`
   - `student_enrollment_grade_2024_1.xlsx`

## Running the Example
Run the Python script to perform the integration and analysis:
bash
python integrate_data.py


## Explanation
The script performs the following steps:
- Loads the transportation and educational data using Pandas.
- Merges the datasets on a common key, such as location.
- Analyzes the merged data to identify areas with high student populations and limited public transport.
- Outputs the locations that require attention for urban planning.

## Results
The analysis provides a list of locations that have a high number of students but limited public transport routes, helping urban planners and policymakers prioritize these areas for development.

## Contribution
Feel free to contribute by submitting pull requests or opening issues to improve the dataset integration and analysis.

## License
This project is licensed under the MIT License - see the LICENSE file for details.