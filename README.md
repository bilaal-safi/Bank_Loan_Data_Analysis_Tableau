
# Bank Loan Data Analysis in Tableau

This interactive dashboard offers a comprehensive analysis of bank loan data, providing insights into key metrics and trends related to loan applications, approvals, and performance.

# Data Source
The analysis is based on the bank loan data for USA. You can find the dataset file (financial_loan.csv) in the current repository. The data is not directly imported from the csv file, however, I used Mysql connector to import data from Mysql Local Instance. But, .csv file can also be imported directly into Tableau to get insights from it.

# Files
- Bank Loan Analysis Dashboard.pdf represents the final dashboard overview in pdf format, showcasing different views like Total loan applications, toal loan funded, total loan received.
- Banking Loan Dashboard.twb can be downloaded and imported into your Tableau Desktop to play with.

# KPIs
- Total Loan Applications: Track the volume of loan applications over time.
- Total Funded Amount: Monitor the total amount of loans funded.
- Total Amount Received: Analyze the total amount received from borrowers.
- Average Interest Rate: View the average interest rate across all loans.
- Average DTI: Examine the average Debt-to-Income ratio of borrowers.

# Data visualizations
The dashboard includes several visual components:
- Bar charts and maps showing loan applications, funded amounts and amount collected by employee length, purpose and state. 
- Treemap displaying the distribution of loan metrics by purpose
- Line and Area graph showing monthly trends in loan applications, funded amounts and amount collected

# Usage
- Open the dashboard file in your Tableau tool
- Use the Measure, Purpose, Verification Status and Grade filters at the top left to interact with the various charts to explore trends and patterns in the loan data.

# Future Improvements
- Implement more advanced calculations like Month to Date MTD, Previous MTD etc to get more insights from data
- Add more detailed visualizations
- Review and validate the data and calculations periodically to ensure accuracy.
