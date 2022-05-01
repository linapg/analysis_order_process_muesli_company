# Business understanding 
Extracting information from the order process for a Muesli company
____________________________________________________________________
# Exploratory Data Analysis

Objective: Business Understanding and extracting information from customer briefing  
Technical: Combine multiple data sources, perform Exploratory Data Analysis   
Mathematical: Calculate descriptive statistics  
Data: [Google Drive EDA Project Folder](https://docs.google.com/spreadsheets/d/1ccH7wXLnCEQ6p_oprj6eXUR4NinmC4m5zW3qAuQ22H0/edit?usp=sharing)

# Business case
A Muesli distribution company want to understand their delivery process. 
They want to develop KPIs to help them keep track of the health of their business in order to improve the service they offer their customers.

The warehouse manager described the workflow as follows:
Order received (Day 1) - order processed in warehouse and made ready to ship (normally 2 days) - order leaves warehouse in truck following day - order delivered to customer (handled by logistics company).

The company has provided a list of their transactions over the course of the past years. They have full data on Order Date and the ‘On Truck Scan’ date but have limited visibility of what happens in between. They have on occasion sent some interns into the warehouse to record the ‘Ready to Ship’ date for as many orders as they could. The warehouse manager says they have not changed their processes much in the past year so they think it should be a good estimate. 

Customers can send orders every day but the warehouse only works Monday to Friday so any orders received on the weekends wait until Monday to be actioned.

Trucks Leave the warehouse on Mondays, Wednesdays and Fridays.
Orders leave on trucks the day after they are made ready for shipping (or two days later if there is no truck).
Customers can pay for Express Processing that means the orders leave on the truck the day the order is ready for shipping.

The logistics company has said they have on average 3 day delivery times to all locations. They transport goods on weekends but only deliver to customers from their local distribution centers on weekdays. The Muesli company has some data about exact delivery dates for a number of shipments that was gathered via marketing promotions they ran where customers scanned a QR code on the package in order to register for a prize. (We assume customers always scanned the code on the day of arrival).

____________________________________________________________________

### Workflow:   
**Understanding the business problem and potential solution**  
1- Understand the order process *``(see 1.orders_process_flowchart)``*  
2- Propose KPIs that would be useful for tracking the performance processes overall and at each stage *``(see 2.kpis)``*  
  
**Exploring the data**  
3- Perform an EDA to describe what data exists including descriptive statistics, identifying missing values and any outliers.  
4- Preparing data by combining and plotting to generate the data needed to validate the assumptions and measure the KPIs.     
  
**Validating the solution**  
5- Further exploratory data analysis to understand the time taken in each step in the order process and the range of values for each KPI.   
6- Evaluate whether the data align with the explanations of the processes given by the company and identify any steps that have ‘concerning’ levels of reliability.    
  
**Visualise and Communicate**   
7- The Jupiter Notebook contains findings, code, and visualisations that can be delivered to the customer *``(see 3.muesli_V.2.ipnyb)``*  
8- Slides for stakeholders presentation *``(see 4.slides_findings)``*
  







