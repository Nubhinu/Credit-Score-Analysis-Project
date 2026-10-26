This project includes the end-to-end data pipeline using raw data from a loan-application dataset derived from a simulated
lending risk portfolio to the final interactive BI dashboard that outlines clear KPIs and respective visuals for real-time
credit risk modelling.

The dataset includes 20,000 records of consumers including credit scores and histories, risk factors, and probability of default
(PD) across 7 UK regions (London, Manchester, Birmingham, Liverpool, Leeds, Glasgow, and Sheffield). 

There are four main stages across this risk analytics workflow: 
1. ETL Data Pipeline (basic data transformation & validation on raw dataset before SQL analysis)

2. Python EDA (investigation of shapes and distributions of key features linked to default risk)

3. SQL Analysis (structured analysis of the different methods to slice loan data using SQL to create custom binned variables
   for future analysis)

4. BI Dashboard (interactive dashboard that includes KPIs and custom visuals based on three filters [credit risk tier, 
   region, years of employment] to determine the trends and major groupings linked to higher rates of default) 
