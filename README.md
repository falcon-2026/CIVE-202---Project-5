# CIVE202_Project#5_INFRA0209
---
Team: Gabriela Gonzalez Ng, Madalynne George, Macy Falconer

---

Risk Averse, LLC asked us to continue analyzing natural hazard risk across six states—Nebraska, Iowa, Illinois, Kansas, Michigan, and South Dakota—using NRI Census Tract data. We will assess the risk of tornadoes using NRI or custom definitions and include population impact based on NRI and SVI data.

---
## Repository Structure

### Raw Data

- [Notebook(Project_5_Code)](CIVE202_Spring2026_GroupINFRA0209_Project5_PythonCode.ipynb)
  
`All other raw data files used in the code were too large of a file size to upload here. The data sets can be found within the code.`
  
---
## User Guide

### 1. Program Overview
The Python Code goes through the following tasks: 
- loading, organizing, filtering, and sorting data as needed
- Creating a summary plot showing data from hazard across different states
- Analyzing in a table or plot indicating the relationship between natural hazard risk and population

**Example:**
This example will go through how to sort and filter data, eliminating NA or missing values, and creating a summary plot with the filtered data.

### 2. Methods
1. Load in all necessary files and libraries before starting the code
2. After loading in the NRI data, load the SVI dataset and check that the data has loaded correctly by using the ".head()" function.
3. Filter your loaded data by the states of interest. In our case, we chose Nebraska, Iowa, Illinois, Kansas, Michigan, and South Dakota. Filter these selected states and make a copy of the dataset using the ".copy()" function. Filter and keep only the relevant columns and drop any missing values using the ".dropna" function.
4. Now, to make a summary plot with your filtered data, start by aggregating the data. Do this by combining the ".groupby", ".mean()", and ".sort_values()" functions.
5. Create the plot. Choose the colors, figure size, what kind of plot, titles, and labels. These can all be done with the "plt." function, followed by what you want to add. For example, if you wanted to make a title, it would look likt "plt.title()" followed by what the title will be in the parenthesis.
6. Lastly, add a custom legend. Pull it from the "matplotllib" library and import Patch. Assign the legend elements, such as colors and labels. Then, plot the summary table as a tight layout and use the command "plt.show()" to show the summary plot.

---
## Project Goals
The goals of this project were outlined with the use of a Gantt Chart. The link is here:

- [Gantt Chart](CIVE202_Spring2026_GroupINFRA0209_Project5_GanttChart.xlsx)

---
## Project Documentation
`Links:`

The project deliverables were planned and tracked using an engineering time sheet to ensure organized progress throughout the project.

- [Time Sheet](CIVE202__Spring2026_INFRA0209_Project5_EngineeringTimeSheet.xlsx)

Additional project documentation:

- [Scope of Work](CIVE202_Spring2026_GroupINFRA0209_Project5_SOW.pdf)
- [Written Report](CIVE202_Spring2026_INFRA0209_Project5_WrittenReport.pdf)
- [Annotated Code Document](CIVE202_Spring2026_INFRA0209_Project5_ACD.xlsx)
