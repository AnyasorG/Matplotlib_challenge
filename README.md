# Pymaceuticals Anticancer Study

## Overview:

Welcome to the repository for the Pymaceuticals Anticancer Study. This project focuses on a comprehensive exploration of the company's recent study, aiming to uncover key insights into the efficacy of various anticancer treatments, with a specific emphasis on Pymaceuticals' drug of interest, Capomulin.

## Prerequisites:

To run this project, you'll need the following:
- Jupyter Notebook installed on your system.
- The Python programming language and pandas’ libraries.
- Knowledge of Pandas for data analysis.
You should also have the following CSV files available in a directory:
-	`mouse_metadata.csv` 
-	`Study_results.csv`

## How to Use the Jupyter Notebook:

1. Clone this repository to your local machine or download the Jupyter Notebook file and CSV files.
2. Ensure you have the required CSV files (`mouse_metadata.csv` and `Study_results.csv`) in the same directory as the Jupyter Notebook file, or update the file path in the notebook to specify the correct location.
3. Open a terminal or command prompt and navigate to the directory containing the Jupyter Notebook file.
4. Run the Jupyter Notebook to execute it interactively.

## License:

This project is open-source and is made available under the terms of the MIT License. The MIT License is a permissive open-source license that allows you to use, modify, and distribute this software for your own purposes. For the full details of the MIT License, please refer to [MIT License Details](https://choosealicense.com/licenses/mit/).

## Code Source:

The code source can be found here: [https://github.com/AnyasorG/Matplotlib_challenge.git]

### Anticancer Study Data:

- Source: Pymaceuticals, Inc.
- Location: Provided CSV file (`mouse_data.csv` and `Study_results.csv`)
- Description: The data represents the results of an anticancer study conducted on mice with squamous cell carcinoma (SCC). The study aimed to compare the performance of Pymaceuticals' drug of interest, Capomulin, against other treatment regimens. Data analysis was performed using the Python programming language (version 3.10.13 packaged by Anaconda, Inc.) and Pandas library (version 2.0.3). The analysis was conducted in Jupyter Notebook (version 5.3.0), leveraging Pandas for data processing and manipulation. The project followed a structured methodology to ensure the data was well-processed and suitable for analysis.

Feel free to explore the notebooks, figures, and the summary to gain a deeper understanding of the study's outcomes. If you have any questions or need further clarification, please don't hesitate to reach out.

## Report Title:

**Exploring Pymaceuticals' Anticancer Study: Unveiling Treatment Efficacy, Variability, and Correlates in Tumor Response**

## Key Observations and Insights from the Pymaceutical Anticancer Study Data Analysis:

### 1. Effectiveness of Capomulin and Ramicane:
Capomulin and Ramicane stand out as potentially more effective treatments, with significantly lower mean and median tumor volumes compared to other regimens. Ramicane shows higher consistency, indicated by lower standard deviation and standard error, suggesting a more tightly clustered distribution of tumor volumes.

### 2. Treatment Variability:
Ketapril and Naftisol exhibit higher variability in tumor volume, reflected in higher variance, standard deviation, and standard error. This variability may imply a less predictable treatment outcome.

### 3. Gender Distribution:
The dataset has a slightly imbalanced gender distribution, with 51.0% male mice and 49.0% female mice. While the difference is minor, it's essential to consider potential gender-related effects on treatment outcomes.

### 4. Boxplots:
Capomulin and Ramicane showcase consistent and narrow distributions without potential outliers, indicating a more predictable response. Infubinol has one potential outlier at Timepoint 31, suggesting an extreme response in one mouse. Ceftamin, like Capomulin and Ramicane, does not exhibit potential outliers.

### 5. Line Plot (Mouse I509 under Capomulin Regimen):
Mouse I509 treated with Capomulin shows a significant decline in tumor volume from Timepoint 20 to 40, indicating a positive response to the treatment during this period.

### 6. Scatter Plot (Mouse Weight vs. Average Tumor Volume):
The scatter plot suggests a positive correlation between mouse weight and average tumor volume for mice under the Capomulin regimen. As mouse weight increases, there is a tendency for the average tumor volume to increase.

### 7. Correlation and Regression:
The strong positive correlation coefficient of 0.84 and the regression model indicate a robust linear relationship between mouse weight and average tumor volume. The slope (0.95) suggests that, on average, for every unit increase in mouse weight, the tumor volume increases by 0.95 units. The strong correlation and positive slope of the regression line indicate that weight is likely a significant factor influencing tumor volume in this specific treatment scenario.

### These findings provide valuable insights into the effectiveness and variability of different treatment regimens, gender distribution, and specific responses to treatments over time. Further investigation and experimentation may be warranted to deepen our understanding of these trends and their implications for potential therapeutic strategies.

## Full Written Report:

The full written report titled Pymaceuticals_Anticancer_Study.docx is located within the GitHub repository at [https://github.com/AnyasorG/Matplotlib_challenge.git]

Thank you for your interest in the Pymaceuticals Anticancer Study!
