# QuadraticHQ_SupplyChainAnalytics

Thrilled to have worked on the project - Data Analytics using AI tools in Supply Chain Domain.
Thrilled to built an end-to-end Data Analytics projects using AI tools in Supply chain Domain.

Tools used : 
N8N - AI workflow automation tool 
Supabase -Postgress development platform
Excel
Quadratic - AI powered spreadsheet 
Python 


Project Outline:
A Gujarat based imaginary company AtliQ Mart - organic food Manufacturer specialize only in few products, operate in 2 cities and opened in another city in USA.
Though performing well the Supply Chain is immature and COO has noticed that some of the customers are dissatisfied with their order management.

Automated the migration of data in excel files directly from the emails to the Postgress via the N8N - workflow tool.
Connecting the Postgress database to the Quadratic - AI powered spreadsheet

Used N8N to migrate the data directly from the emails - retrieved the data and loaded the data to the Postgress database.
Used Quadratic - AI powered spreadsheet to connect to the Postgress database and retrieve the data to the spreadsheet.
-Prompted to create a date table in the Chat box
-Prompted to create a rate exchange table -using a API request sample to fetch historical exchange rates.
-Prompted for - Data cleaning and summarizing required data in one table
-Prompted to retrieve the Business KPI's via Chat box in the spreadsheet.
	Create the following KPIs
		1. Total Order Lines
		2. Line Fill Rate
		3. Volume Fill Rate
		4. Total Orders
		5. On Time Delivery %
		6. In Full Delivery %
		7. On Time In Full %

	Create the following KPIs - Top Customers
		Show me top 5 customers based on order value and their OTIF %, IF %, OT %.
		Also add the customer name, customer ID and city in the table
	Use this Prompt: Top Customers (India)
		Show me top 5 customers in India based on order value and their OTIF %, IF %, OT %.
		Also add the customer name, customer ID and city in the table
	
	Use Quadratic AI to answer these business questions:
		• Quantify the revenue loss attributed to undelivered orders.
		• Identify customers with the most significant On-Time, In Full (OTIF) discrepancies.
		• Determine product categories that exhibit low 'In Full' delivery rates.
		• Calculate the average delay time for late deliveries.
		• Identify product categories with the lowest 'In Full' delivery rates. What could this indicate 		   about supply chain bottlenecks?
