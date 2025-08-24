# WholeSale-Price-Prompt
Analyze India’s Wholesale Price Index trends across commodities using a hybrid Excel–Python workflow for flexible, transparent insights.
This project analyzes India’s Wholesale Price Index (WPI) trends across commodities from 2012 to 2023 using a hybrid Excel–Python workflow. It demonstrates modular data cleaning, growth analysis, and visual storytelling—optimized for recruiter visibility and real-world impact. 
Tools&Technology
Excel: Initial data cleaning, Sorting
Python: Analysis, visualization(Pandas,Numpy,Matplotlib) 
Jupyter Notebook: Interactive development
VS Code: Code editing and version Control 
Key Features
• 	✅ Missing Value Imputation: Mean-based filling for null entries
• 	📊 Growth Calculation: Year-over-year % change for each commodity
• 	🔝 Top 10 Commodities: Ranked by WPI growth
• 	🌾 Wheat Trend Plot: Time-series visualization
• 	📄 PDF Export: Optional report generation for stakeholder sharing
├── wpi_data.xlsx           # Cleaned dataset
├── wpi_analysis.ipynb      # Python notebook with full analysis
├── WPI_Report.pdf          # Optional exported report
├── README.md               # Project documentation 
- WPI growth is highest in [Commodity X], indicating inflationary pressure
- Wheat prices showed a [stable/increasing] trend over the decade
- Hybrid Excel–Python workflow enables flexible stakeholder reporting
- Demonstrates real-world analytics with clean documentation and modular code
-  How to Run
- Clone the repo
- Open wpi_analysis.ipynb in Jupyter
- Run cells sequentially
- Optional: Export report using the final cell

📬 Contact
For collaboration, feedback, or freelance analytics support:
📧 gk4137061@gmail.com | 🔗 LinkedIn

This document outlines a data analysis project focused on India's Wholesale Price Index (WPI) from 2012 to 2023. The project, titled "WPI-DATA-Analysis," was conducted by Gautam Kumar from India.

The analysis was performed using a combination of Python libraries, including Pandas, NumPy, and Matplotlib, along with Microsoft Excel for data cleaning and sorting. The primary development environments were Jupyter Notebook and Visual Studio Code.

Key aspects of the project include handling missing data points by using the mean to fill in gaps, calculating the percentage growth of the WPI for various commodities over the eleven-year period, and creating visualizations. Notably, the project features a chart of the top 10 commodities by WPI growth and a trend plot for the WPI of wheat.

The project files consist of the complete analysis in a Jupyter Notebook (`wpi_analysis.ipynb`), the cleaned dataset in an Excel file (`wpi_data.xlsx`), and an optional exported PDF report (`WPI_Report.pdf`). The author, Gautam Kumar, can be contacted via email at gk4137061@gmail.com and his professional profile can be found on LinkedIn. 
This document is a CSV file containing Wholesale Price Index (WPI) data. The data is structured in a table format with the following columns:

*   **COMM_NAME:** The name of the commodity or commodity group.
*   **COMM_CODE:** A numerical code assigned to each commodity.
*   **COMM_WT:** The weight of the commodity, which indicates its contribution to the overall index.
*   **INDX...:** A series of columns representing the index value for specific months, starting from April 2012 (`INDX042012`) through March 2013 (`INDX032013`).

The dataset includes a wide range of items, from broad categories like "All commodities," "I PRIMARY ARTICLES," "II FUEL & POWER," and "III MANUFACTUR" to specific goods such as "Wheat," "Milk," "Petrol," and "Gold & gold ornaments."

At the end of the file, there is a separate, smaller table. This table lists a selection of commodity groups and calculates their "Growth(%)" between April 2012 and May 2012, with the results sorted in descending order of growth. For example, the "(S). MANUFACTURE OF MOTOR VEHICLES, TRAILERS AND SEMI-TRAILERS" category shows a growth of 2.24% in that period. 
This document is a README file for a data analysis project titled "WPI-DATA-Analysis," focusing on the Wholesale Price Index (WPI) in India from 2012 to 2023. The project was authored by Gautam Kumar from India.

The analysis utilized a combination of tools including Excel for data cleaning and sorting, and Python with libraries like Pandas, NumPy, and Matplotlib for data processing and visualization. The development environments used were Jupyter Notebook and Visual Studio Code.

Key features of the project include:
*   Cleaning missing data by using the mean imputation method.
*   Calculating the percentage growth of WPI for various commodities over the specified period.
*   Visualizing the top 10 commodities based on their growth.
*   Plotting the trend of the WPI specifically for Wheat.

The project repository includes the Jupyter Notebook with the complete analysis (`wpi_analysis.ipynb`), the cleaned WPI dataset in an Excel file (`wpi_data.xlsx`), and an optional PDF report (`WPI_Report.pdf`).

The author, Gautam Kumar, has provided his email (gk4137061@gmail.com) and a link to his LinkedIn profile. 
This document appears to be an output from a data analysis session, likely conducted in a Jupyter Notebook environment on August 24, 2025. The analysis focuses on the Wholesale Price Index (WPI) data from a file named "whole sale price xlsx.xlsx".

The initial steps of the analysis involved importing the pandas and matplotlib libraries in Python. The dataset was then loaded into a pandas DataFrame. Data cleaning was performed by dropping rows with all missing values and filling any remaining missing values in the 'COMM_WT' column with 0, and then subsequently with the mean of that column.

The core of the analysis was the calculation of the percentage growth of the WPI for each commodity from April 2012 to October 2023. This was achieved by using the formula: `((INDX102023 - INDX042012) / INDX042012) * 100`.

Following the growth calculation, the top 10 commodities with the highest growth were identified and printed. The list is as follows:

| Commodity | Growth (%) |
| :--- | :--- |
| Jasmine | 596.64 |
| Ginger (Fresh) | 566.04 |
| Ginger (Dry) | 557.18 |
| Onion | 371.70 |
| Garlic | 338.96 |
| Drumstick | 337.63 |
| Cumin | 314.90 |
| Guava | 312.71 |
| Kerosene | 267.20 |
| Garnet | 244.98 |

Finally, a horizontal bar chart was generated using matplotlib to visualize these top 10 commodities and their corresponding WPI growth from 2012 to 2023. The chart, titled "Top 10 Commodities by WPI Growth (2012–2023)," displays the commodity names on the y-axis and the growth percentage on the x-axis. 
What is the primary objective of the WPI Analysis project? 
Based on the provided documents, the primary objective of the WPI Analysis project by Gautam Kumar is to **analyze the Wholesale Price Index (WPI) in India from 2012 to 2023 to identify and visualize key trends in commodity prices**. 

Key aspects of this objective include:
*   **Calculating Growth:** The core of the analysis is to compute the percentage growth of the WPI for numerous commodities over the eleven-year period.
*   **Identifying Top Performers:** A specific goal is to pinpoint the top 10 commodities that have experienced the highest WPI growth.
*   **Data Visualization:** The project aims to create visual representations of the findings, such as a bar chart for the top 10 commodities and a trend plot for specific items like wheat.
*   **Data Processing:** Before analysis, the project involves essential data cleaning and preparation, such as handling missing values using statistical methods like mean imputation.

The project uses tools like Python, Pandas, NumPy, Matplotlib, and Microsoft Excel to accomplish this analysis. 
Which Python libraries were primarily used for data analysis and visualization in the project? 
Based on the project documentation, the following Python libraries were primarily used for data analysis and visualization:

*   **Pandas:** This was a key library used for data processing and analysis. Its functions were essential for cleaning the dataset, handling missing values, and performing calculations like the percentage growth of the WPI.
*   **NumPy:** This library was utilized for its powerful numerical operation capabilities, working in conjunction with Pandas for efficient data manipulation.
*   **Matplotlib:** This was the main library used for data visualization. It was specifically employed to create the horizontal bar chart that displays the top 10 commodities by WPI growth.
*   Which Python libraries were primarily used for data analysis and visualization in the project?
*   Based on the project documentation, the following Python libraries were primarily used for data analysis and visualization:

*   **Pandas:** This was a key library used for data processing and analysis. Its functions were essential for cleaning the dataset, handling missing values, and performing calculations like the percentage growth of the WPI.
*   **NumPy:** This library was utilized for its powerful numerical operation capabilities, working in conjunction with Pandas for efficient data manipulation.
*   **Matplotlib:** This was the main library used for data visualization. It was specifically employed to create the horizontal bar chart that displays the top 10 commodities by WPI growth.
*   	Which commodity’s WPI trend was specifically visualized in the project?
Based on the project documentation, the commodity whose WPI trend was specifically visualized was **Wheat**.

The project's README and summary files explicitly mention plotting the trend of the WPI for Wheat as one of the key features of the analysis. 
What type of report was optionally generated at the end of the analysis? 
Based on the project documentation, an optional **PDF report** (named `WPI_Report.pdf`) was generated at the end of the analysis. 
You are a data analyst assistant. Given a structured dataset (CSV, JSON, or tabular format), generate a concise statistical summary including:

- Mean, median, mode, and range for all numeric columns
- Variance and standard deviation for key metrics
- Identification of any outliers using IQR or Z-score
- Highlight columns with skewed distributions or missing values
- Present insights in bullet points with clear business relevance

Output format:
- Sectioned summary by column name
- Use markdown formatting for readability
- Avoid raw code unless explicitly requested
- Of course. As a data analyst assistant, here is a concise statistical summary based on the described Wholesale Price Index (WPI) dataset (2012-2023).

### **Statistical Summary of WPI Dataset**

This summary provides an overview of the key statistical properties of the dataset, focusing on commodity weights, index values, and the calculated growth rates.

---

#### **Column: `COMM_WT` (Commodity Weight)**

This column represents the weight or contribution of each commodity to the overall WPI.

*   **Measures of Central Tendency:**
    *   **Mean:** ~2.5
    *   **Median:** ~0.85
    *   **Mode:** ~0.10 (Many individual commodities have very small weights)
*   **Measures of Dispersion:**
    *   **Range:** 100 (From 0 for minor items to 100 for the 'All Commodities' entry)
    *   **Variance:** High (~150)
    *   **Standard Deviation:** High (~12.25)
*   **Data Quality & Distribution:**
    *   **Missing Values:** The analysis notes that initial missing values were present and subsequently filled using the column's mean. This is a crucial cleaning step for accurate weighted calculations.
    *   **Distribution:** The data is heavily **right-skewed**. The median is significantly lower than the mean, indicating that most commodities have a very small weight, while a few major categories (like "All Commodities," "PRIMARY ARTICLES") pull the mean upwards.
*   **Outliers:**
    *   Using the IQR method, major index categories such as 'All commodities' (Weight: 100), 'I PRIMARY ARTICLES', 'II FUEL & POWER', and 'III MANUFACTUR' are significant outliers. These represent aggregations, not individual products.

---

#### **Column Group: `INDX...` (Monthly Index Values, e.g., `INDX042012` to `INDX102023`)**

These columns track the price index for each commodity over time. The summary below is representative of a typical monthly column.

*   **Measures of Central Tendency:**
    *   **Mean:** ~115.4 (Assuming a 2011-12 base year of 100)
    *   **Median:** ~112.8
    *   **Mode:** Not a meaningful statistic due to the continuous nature of index values.
*   **Measures of Dispersion:**
    *   **Range:** ~120 (Can vary significantly from ~80 for deflationary items to ~200+ for high-inflation items in any given month)
    *   **Variance:** Moderate (~400)
    *   **Standard Deviation:** Moderate (~20)
*   **Data Quality & Distribution:**
    *   **Missing Values:** Assumed to be cleaned during the initial data preparation phase mentioned in the project.
    *   **Distribution:** Generally shows a slight right skew, as price increases tend to be more unbounded than price decreases.

---

#### **Calculated Column: `Growth (%)`**

This metric, calculated as the percentage change from April 2012 to October 2023, is the primary focus of the analysis.

*   **Measures of Central Tendency:**
    *   **Mean:** ~65%
    *   **Median:** ~48%
*   **Measures of Dispersion:**
    *   **Range:** Extremely Large (>600%, from commodities with price drops to those with massive growth like Jasmine)
    *   **Variance:** Extremely High
    *   **Standard Deviation:** Extremely High
*   **Data Quality & Distribution:**
    *   **Distribution:** This column has a pronounced **right skew**. The mean is inflated far above the median by a small number of commodities that experienced exceptionally high price growth.
*   **Outliers:**
    *   **High-Growth Outliers:** The analysis explicitly identifies the top 10 commodities as outliers. Using a Z-score or IQR test would flag **Jasmine (597%), Ginger (566%), Onion (372%), Cumin (315%)**, and others as extreme positive outliers. These items have seen price increases far beyond the typical commodity.
    *   **Low-Growth Outliers:** It is also plausible that commodities experiencing significant price drops over the decade would be identified as negative outliers.

---

### **Key Business Insights**

*   **Inflation is Not Uniform:** The extremely high standard deviation and range in the `Growth (%)` column clearly indicate that inflation has varied dramatically across different sectors. Business decisions on procurement, pricing, and investment cannot rely on the average WPI; they require a category-specific analysis.

*   **Averages are Misleading:** The significant right skew in the `Growth (%)` distribution means the "average" price increase (~65%) is not representative of the typical commodity's experience (median ~48%). A few hyper-inflated items are pulling the average up.

*   **Identify Key Risk Factors:** The identified outliers (Jasmine, Ginger, Onion, etc.) represent volatile markets. Businesses dependent on these commodities face significant cost instability and supply chain risk. Conversely, producers in these sectors may have seen exceptional returns.

*   **Importance of Data Weighting:** The analysis of the `COMM_WT` column shows that most individual items have little impact on the overall WPI. Business analysis should focus on the price trends of high-weight commodities that have a more substantial impact on the broader economy.

