# sql_portfolio
About Me:<br>
Welcome! I'm Andrea, an experienced data analyst who passionate about using data to help people. This portfolio showcases a SQL project working with a churn rate dataset and building visualizations. I selected this project so that I could expand my knowledge of customer-based data.

Objective:<br>
The goal of this project was to identify accounts at risk of churn and detect early indicators of customer disengagement. By analyzing behavioral and support metrics, I aimed to help the business proactively retain valuable customers.<br>

Tools Used:<br>
Database: MySQL (via DBeaver)<br>
Language: SQL<br>
Visualization: Looker<br>

Key Findings<br>
&nbsp;&nbsp;10 High-Risk Accounts Identified<br>
&nbsp;&nbsp;30% of Retail accounts are at high risk of churn, representing $1,032,854 in potential annual revenue loss.<br>

&nbsp;&nbsp;4 Premium Plans at Risk<br>
&nbsp;&nbsp;These accounts represent $2,190,717 in total value and warrant immediate retention strategies.<br>

&nbsp;&nbsp;11 Low-Risk Accounts<br>
&nbsp;&nbsp;The majority of these are on the Basic plan and show healthy engagement patterns.<br>

Methodology<br>
Data Collection:<br>
CSV datasets were sourced using a ChatGPT prompt to simulate realistic customer engagement and support scenarios.<br>

Data Cleaning & Preparation:<br>
Performed exploratory data analysis (EDA) in the CSVs, including profiling and cleaning. After importing into MySQL, I addressed formatting issues, specifically with date fields.<br>

Risk Scoring Approach:<br>
I created a custom point based risk scoring model using the following metrics:<br>
&nbsp;&nbsp;Average CSAT Score (Customer Satisfaction)<br>
&nbsp;&nbsp;Days Since Last Login<br>
&nbsp;&nbsp;Support Ticket Count<br>
&nbsp;&nbsp;Average Resolution Time (Hours)<br>

Each metric contributed to a composite churn risk score, which I used to classify accounts into high, moderate, and low risk tiers.<br>

Links:<br>
SQL Query: [churn_risk_dataset](https://github.com/andrealdata/sql_portfolio/blob/main/churn_risk)<br>
Live Dashboard: [Link to Looker](https://lookerstudio.google.com/reporting/181a230e-15d2-4cf2-9a23-b576f64ee0ea)<br>
This will continue to be updated as Looker is a new tool for me and I have been learning more using it!<br>
<iframe width="600" height="450" src="https://lookerstudio.google.com/embed/reporting/181a230e-15d2-4cf2-9a23-b576f64ee0ea/page/6MvOF" frameborder="0" style="border:0" allowfullscreen sandbox="allow-storage-access-by-user-activation allow-scripts allow-same-origin allow-popups allow-popups-to-escape-sandbox"></iframe>
<br>
Data Sources:<br>
Primary Dataset: customers<br>
Secondary Datasets: product_usage, support_interactions

Contact:<br>
[Connect with me on LinkedIn!](https://www.linkedin.com/in/andrea-lunn-909b2b185/)
<br>
Email: andrea.e.lunn@gmail.com


