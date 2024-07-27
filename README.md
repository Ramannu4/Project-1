# Project-1
Redbus Data Scraping with Selenium &amp; Dynamic Filtering using Streamlit
Project description:
The "Redbus Data Scraping and Filtering with Streamlit Application" aims to revolutionize the transportation industry by providing a comprehensive solution for collecting, analyzing, and visualizing bus travel data. By utilizing Selenium for web scraping, this project automates the extraction of detailed information from Redbus, including bus routes, schedules, prices, and seat availability. By streamlining data collection and providing powerful tools for data-driven decision-making, this project can significantly improve operational efficiency and strategic planning in the transportation industry.
Business Use Cases:
The solution can be applied to various business scenarios including:
Travel Aggregators: Providing real-time bus schedules and seat availability for customers.
Market Analysis: Analyzing travel patterns and preferences for market research.
Customer Service: Enhancing user experience by offering customized travel options based on data insights.
Competitor Analysis: Comparing pricing and service levels with competitors.
Approach:
Data Scraping:
Use Selenium to automate the extraction of Redbus data including routes, schedules, prices, and seat availability.
Data Storage:
Store the scraped data in a SQL database.
Streamlit Application:
Develop a Streamlit application to display and filter the scraped data.
Implement various filters such as bustype, route, price range, star rating, availability.
Data Analysis/Filtering using Streamlit:
Use SQL queries to retrieve and filter data based on user inputs.
Use Streamlit to allow users to interact with and filter the data through the application.
My Approach:
Firstly I used selenium tool to scrap data which one of HTML tool from dynamic website and my project is about scrapping data from redbus which is a dynamic website like route name,link,departing time,arrival time,duration,seatsavailability details from the website.
with a basic knowledge of selenium tool  i scrapped the data and converted into dataframe and stored into MySQL 
In MySQL i stored ten different state buses info into single tables and using that stored data i made streamlit interface
In streamlit interaface i made queries to display the info of different state buses and converted into dataframe then displayed like table format 

