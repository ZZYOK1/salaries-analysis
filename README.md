# Salary Analysis Project

## Project Overview

This project is designed to analyze and visualize salary data based on various parameters such as company size, experience level, geographic distribution, and remote work status. The codebase is structured to handle data import, processing, analysis, and visualization, providing insights into salary trends and distributions. The analysis is based on a dataset stored in an Excel file (`salaries.xls`).

## Project Structure

### Directories and Key Files

- **analyze**: Contains analyzers for different aspects of the salary data.
  - `CompanySizeSalaryAnalyzer.java`: Analyzes salary distributions across different company sizes.
  - `ExperienceLevelSalaryAnalyzer.java`: Provides insights into how experience levels affect salaries.
  - `GeographicDistributionAnalyzer.java`: Examines the geographic distribution of salaries.
  - `RemoteSalaryAnalyzer.java`: Analyzes how remote work influences salary trends.
  - `SalaryRangeAnalyzer.java`: Analyzes salary ranges and their distribution within the dataset.

- **data**: Manages database connections and utilities.
  - `DBConnection.java`: Handles the establishment of database connections.
  - `DBUtil.java`: Provides utility methods for database operations.

- **Excel**: Deals with importing and managing data from Excel files.
  - `ImportExcel.java`: Contains functionality to read and import data from `salaries.xls`.

- **main**: Contains the main entry point for the project.
  - `Main.java`: The main file that integrates all the components and runs the analysis.

- **visualization**: Contains classes for visualizing the analyzed data.
  - `BarChartVisualizer.java`: Generates bar charts to represent different aspects of the salary data.
  - `PieChartVisualizer.java`: Creates pie charts to visualize proportions in the salary data.
  - `Gui.java`: Provides a graphical user interface (GUI) to interact with the visualizations.

- **lib**: Contains any external libraries or dependencies used in the project.

- **bin**: The compiled `.class` files will be located in this directory after compilation.

- **.settings**, **.classpath**, **.project**: Project configuration files for your Java development environment.

- **salaries.xls**: The Excel file that serves as the data source for analysis.

## Features

### Data Analysis

The project analyzes salary data based on various parameters:

- **Company Size**: Analyzes how the size of a company affects salary trends.
- **Experience Level**: Provides insights into salary changes based on different levels of experience.
- **Geographic Distribution**: Explores how salary varies across different geographic regions.
- **Remote Work**: Studies the impact of remote work on salary distributions.
- **Salary Ranges**: Offers a breakdown of salaries across different ranges to identify trends and patterns.

### Data Visualization

The project visualizes the analyzed data through:

- **Bar Charts**: Displays categorical data for easy comparison between different parameters such as company size, experience level, etc.
- **Pie Charts**: Represents data as portions of a whole to show distributions, such as geographic or experience level distributions.
- **Graphical User Interface (GUI)**: Provides an interactive way for users to view and analyze the visualized data.

