# kiva-loans-analysis
defining organizational KPIs and owning projects that will markedly improve performance on said metrics.


Project Overview

This repository presents an exploratory data analysis of the Kiva Crowdfunding dataset, focusing on key performance indicators (KPIs) to assess the platform's effectiveness in empowering borrowers through microloans. The primary KPI analyzed is the Loan Repayment Rate (LRR), along with supplementary metrics such as average loan amount, loan term, and lender count.

Dataset:

The analysis utilizes the Kiva Crowdfunding dataset available on Kaggle (https://www.kaggle.com/datasets/kiva/data-science-for-good-kiva-crowdfunding).   

Methodology:

Data Cleaning: Addressed missing values, inconsistencies, and outliers in the dataset.
KPI Calculation: Calculated the Loan Repayment Rate (LRR) and other relevant metrics.
Exploratory Data Analysis (EDA): Conducted univariate and bivariate analysis to understand data distribution and relationships between variables.
Visualization: Utilized various visualization techniques (histograms, bar plots, scatter plots) to explore data patterns.
Correlation Analysis: Calculated correlation coefficients to assess relationships between variables.
Key Findings:

[Analysis of Loan Repayment Rate (LRR)

LRR of 97.85% indicates a high repayment rate among Kiva borrowers. This is a positive indicator of the overall health of the loan portfolio.

Potential Implications:

Strong credit assessment: Kiva's credit assessment processes appear to be effective in identifying low-risk borrowers.

Favorable economic conditions: The overall economic environment might be conducive to loan repayment.

Effective loan management: Kiva's loan management practices (e.g., loan servicing, collection) might be contributing to the high repayment rate. However , we need to anlyse further as this is based on only single metric. We shall check on other metrics which include:

-Analyze LRR by different segments (country, sector, loan amount) to identify variations.

-Calculate other performance metrics (e.g., default rate, average loan term) for a more comprehensive picture.

-Explore factors influencing repayment behavior (e.g., borrower demographics, economic indicators)]

[Interpreting Correlations

Strong positive correlations: Indicate variables move in the same direction.

Strong negative correlations: Indicate variables move in opposite directions.

Weak correlations: Suggest little relationship between the variables.

INSIGHTS

Loan Amount and Repayment Rate: A negative correlation suggest larger loans have higher default rates.

Loan Term and Repayment Rate: A positive correlation indicate longer loan terms lead to higher repayment rates (or vice versa).

Lender Count and Repayment Rate: A positive correlation suggest that loans with more lenders have higher repayment rates.]

[Outliers: A few data points with extremely high loan amounts and relatively short terms are visible. These might represent unusual loan types or data anomalies.

Potential Implications:

Risk Assessment: Larger loans with longer terms might pose higher credit risk.]
Limitations:

The analysis is based on a specific dataset and might not capture all relevant factors influencing loan repayment.
Further exploration with additional data sources and advanced statistical techniques is recommended.
Future Work:

Incorporate time series analysis to study trends over time.
Develop predictive models to forecast loan repayment.
Explore machine learning techniques for deeper insights.
Expand analysis to include borrower-level data (if available).
Code Structure:

[Notebook name]: Contains the main data analysis and visualization code.
[Additional scripts or notebooks]: Include any supplementary code for specific analyses.
Dependencies:

pandas
numpy
matplotlib
seaborn
Usage:

Clone the repository.
Install required dependencies using pip install pandas numpy matplotlib seaborn.
Run the main Jupyter Notebook to reproduce the analysis.
Contributing:

Contributions to improve the analysis or add new features are welcome. Please open an issue or pull request.

License:

[Specify the license for your project, e.g., MIT, Apache, etc.]

Contact:

[Name: Kerich Kibent Mike
Email: mkibekerich14@gmail.com]

Additional Notes:

screenshots of key visualizations within the README 
![image](https://github.com/user-attachments/assets/c9272db4-2993-4d6f-8689-0042c3d83500)


![image](https://github.com/user-attachments/assets/9d958f17-4785-4b92-be44-b3992cdd31c3)



Key Findings:

Loan Amount vs. Loan Term: [Positive Correlation: As the loan amount increases, there's a tendency for the loan term to also increase. Data Concentration: The majority of data points cluster in the lower left corner, indicating a concentration of smaller loans with shorter terms.

Outliers: A few data points with extremely high loan amounts and relatively short terms are visible. These might represent unusual loan types or data anomalies.

Potential Implications:

Risk Assessment: Larger loans with longer terms might pose higher credit risk.

Portfolio Management: Understanding the distribution of loan amounts and terms can help in portfolio diversification.

Outlier Analysis: Investigating the outliers could reveal specific loan types or circumstances influencing loan terms.]

Loan Repayment Rate by Sector: [ Some sectors might exhibit higher repayment rates than others. Identifying these sectors can help focus lending efforts.]

 potential business implications of the findings.
 
 Diversify Lending Portfolio: Given the varying repayment rates across different countries and sectors, Kiva should consider diversifying its lending portfolio to mitigate risks associated with specific regions or industries.

Enhance Borrower Profiling: Improve the collection of borrower-level data to better understand factors influencing repayment behavior. This could involve gathering information on income, education, and household size.

Strengthen Lender Relationships: Explore strategies to encourage increased lender participation, as there might be a correlation between the number of lenders and loan repayment success.
