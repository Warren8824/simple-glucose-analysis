# Personal Glucose Control Analysis Project

## Overview
This project presents an analysis of authentic continuous glucose monitoring (CGM) data from a person with Type 1 Diabetes (myself). It demonstrates data analysis skills using Python, particularly with time-series health data. Additionally, it includes a preprocessing tool for Libre sensor data, making it adaptable for others to use with their own data.

## Data Description
The analysis uses 3 months of:
- Glucose readings (mmol/L) at 5-minute intervals
- Insulin doses (units)
- Carbohydrate intake (grams)

Note: The specific date range has been anonymized for privacy, and this is not current data.

## Project Objectives
1. Showcase data analysis skills with Python and time-series health data.
2. Demonstrate proficiency in data cleaning, preprocessing, and visualization.
3. Apply statistical analysis to derive insights from glucose monitoring data.
4. Explore patterns in diabetes management data.
5. Present findings clearly and visually.
6. Provide a tool for preprocessing Libre sensor data for broader usability.

## Tools and Technologies
- Python 3.x
- Pandas, Matplotlib, Seaborn, Scipy, Statsmodels

## Setup and Installation
1. Clone this repository
2. Create a virtual environment: `python -m venv venv`
3. Activate the virtual environment:
   - Windows: `venv\Scripts\activate`
   - Unix or MacOS: `source venv/bin/activate`
4. Install required packages: `pip install -r requirements.txt`
5. Launch Jupyter Notebook: `jupyter notebook`

## Project Structure
- `glucose_analysis.ipynb`: Main analysis notebook
- `preprocess_libre_data.ipynb`: Notebook for preprocessing Libre sensor data
- `data/`: Directory containing sample data files
- `requirements.txt`: List of required Python packages

## Using the Preprocessing Tool
1. Open `preprocess_libre_data.ipynb`
2. Follow the instructions to input the path to your Libre sensor data
3. Run the notebook to generate two CSV files: glucose data in 5 minute intervals, treatment data containing the sum of all carbs and both bolus and basal insulin doses in the same 5 minute intervals.
4. Use these files as input for the main analysis notebook

Note: If you use a different CGM with xDrip+ or use the sensor manufacturer's software, your file layout might differ. You may need to adjust the preprocessing code accordingly.

## Running the Analysis
1. After preprocessing (or using the sample data), open `glucose_analysis.ipynb`
2. Follow the notebook instructions to load and analyze the data
3. Modify parameters or explore further as desired

## Key Findings
(Summarize your main insights here after completing the analysis)

## Ethical Considerations
This project uses real, personal health data that has been anonymized. Insights are for educational purposes only and should not be considered medical advice. Any application of these insights to diabetes management should be done under the guidance of healthcare professionals.

## Future Work
- Extend preprocessing support for other CGM devices
- Implement automated pattern recognition for glucose trends
- Develop a user-friendly interface for data input and analysis

## Contributing
Contributions to improve the preprocessing tool or extend the analysis are welcome. Please feel free to fork the repository and submit pull requests.

## Contact
Warren Bebbington - Contact me on github.

Project Link: [https://github.com/Warren8824/simple-glucose-analysis](https://github.com/Warren8824/simple-glucose-analysis)

## Acknowledgments
- Libre sensor technology
- Open-source Python community
- Fellow diabetes data enthusiasts
