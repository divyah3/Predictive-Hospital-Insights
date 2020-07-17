# COVID-19 Predictive Hospital Insights
Created by: San Francisco Summit Squad

*********************** To Access Website ***********************
Open the dashboard.HTML file locally on a browser. You must be connected by VPN to the w3 network. 
*****************************************************************
Video Description: https://www.youtube.com/watch?v=vQ75brspO7c

__Identify Real World Problem__

Our country is at war with a pandemic and the ones on the front lines need protection.  The daily average of new coronavirus cases over the past seven days has more than tripled the average reported in mid-June. Healthcare workers and medical professionals are risking their lives every day to save others. The increasing spread of the virus has left healthcare facilities struggling to manage overwhelming amounts of hospitalizations as well as shortages in supplies. This is due to disruptions in supply chain and unexpected spikes in cases. We wanted to focus our efforts on helping these healthcare providers do their jobs while maintaining the protection they not only deserve but need. 

__Describe the Technology__

We developed COVID-19 Predictive Hospital Insights, a dashboard that offers rich visualizations for healthcare facilities to track personal protective equipment and available beds. We leveraged IBM’s Cognos technology to create this business intelligence platform. Using the Watson Artificial Intelligence embedded in Cognos, we were able to visualize relationships between various data points, uncovering insights from a hospital’s inventory database.   

Powered by Cognos’s linear regression model, the plots forecast the expected supply of each hospital item based on local COVID-19 cases. This will allow hospital workers to see into the future in order to determine when an increase in inventory and available beds will be needed. 

__How It Works__ 

We gathered data on Michigan hospitals and integrated inventory data into Cognos (N95 masks, ventilators, ICU beds, surgical isolation gowns, PAPR filters, goggles, etc.) 

This data was then appended with columns containing Covid-19 cases and deaths, based on the hospital’s location 

Plots are shown forecasting COVID-19 case surges and the supply of the above equipment for the next 10 days  

The Relational Data dashboard uncovers insights on the relationship between PPE supplies, COVID-19 Cases/Deaths, and hospital bed availability 

We then integrated these two dashboards onto a website, allowing users to access the dashboards without a Cognos login 

Enables healthcare providers to understand the incoming patient needs ahead of time, and the relevant hospital supplies anticipated, to take action to avoid shortages 

 
__Explain why it’s better than any existing solution__

Predictive Hospital Insights makes it easy for health providers to access, use, and analyze the number of supplies. By having them integrate their inventory into our website, healthcare facilities are guaranteed real-time, predictive insights on expected shortages. The use of real-time data eliminates the need for back-processing therefore ceasing limited data forecasts for users. By helping health providers save the time and energy to monitor their resources, the Cognos dashboard can enable them to be more productive in tending to patient care. 

__Highlight next steps__

With the help of IBM, hospitals around the world can integrate their internal supply databases to our Cognos dashboard. Our goal is to eventually import data from all 50 states and break it down into counties. Plots can then be added to our site, giving them access to the information whenever they need.  The Predictive Hospital Insights potentially has the capability to allow any state to track resources beyond COVID-19, including vaccines, medications, and any other supplies within their database and ours. 
