# patient-perception-income-report

NHS Scotland Patient Perceptions Project
Overview
This R project aims to analyze patient perceptions of healthcare in NHS Scotland using linear and multiple linear regression models. The project utilizes biennial patient health and care experience data linked to datazone level income rankings from the Scottish Index of Multiple Deprivation.

Project Structure
Data: Raw data files, including patient health and care experience data and income rankings from the Scottish Index of Multiple Deprivation.

Scripts:

data_preparation.R: R script for data cleaning and preparation.
regression_analysis.R: R script for conducting linear and multiple linear regression analyses.
visualization.R: R script for creating visualizations of the results.
Point Maps on Overlays: Python script for creating maps of location information.

regression_results.csv: CSV file containing the results of regression analyses.
visualizations/: Directory containing visualizations generated from the analysis.
Usage
Ensure you have R installed on your system.
Clone the repository to your local machine.
Run data_preparation.R to clean and prepare the data.
Execute regression_analysis.R to perform linear and multiple linear regression analyses.
Utilize visualization.R for creating visualizations based on the results.
Dependencies
Ensure you have the necessary R packages installed. You can install them using the following commands:

R
Copy code
install.packages("tidyverse")
install.packages("glmnet")
Results Interpretation
Refer to the generated regression_results.csv file for detailed results. Visualizations are available in the visualizations/ directory.

License
This project is licensed under the MIT License. See the LICENSE file for details.
