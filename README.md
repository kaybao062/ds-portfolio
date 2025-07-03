# Data Projects Portfolio

## AI Product

#### MULTI-ORCHESTRATED SYSTEM FOR AIRLINE INTELLIGENCE & COORDINATION (MOSAIC)
*June 2025*
(diagram)
(credit)
To enhance internal demand forecasting, our team built an AI-powered analytics dashboard that integrates and visualizes key external signals—including weather, news, and social media trends to explain past demand and predict future demand. Our team won the first place of Generative AI Hackathon hosted by United Airline and University of Chicago. 

We leveraged **Agent-to-agent** framework to create a Multi-Agent tool with an Orchestrater connecting to a range of agents. Each agent is connected to 1-2 **MCP server**, while each server hosted different data sources, including historical/forecasted weather, historical/forcasted flight price, past/future events, Google Trends, Google News, aviation weather and IMF insights, and necessary tools to retrieve all data. For historical data, we created a **text-to-sql agent** under **LangGraph** framework to convert natural language query to SQL command and retrieves data via **Retrival-Augmented-Generation (RAG)** structure. 


#### AI Scraper for Global Calendar of Statistical Events
*March 2025 - Present*
(diagram)
(credit)
The [Global Calendar of Statistical Events](https://unstats.un.org/capacity-development/calendar/all-events/) is a data hub that highlights the capacity-building events related to statistics and geospatial information. For compiling the event data from 50+ sources the Global Calendar relies on 30+ traditional web scraping bots and some manual data collection. The web scraping bots need to be updated regularly to adjust for changes on the source websites and manual data collection is very time consuming. 

The AI Scraper was developed to deal with unstructured data and varied website layouts. By introducing a technical pipeline including pre-processing, AI extracting events and post-processing, the AI Scraper tremendously reduced the time of scraping and attains 95% accuracy, ensured by human verification. To improve accuracy and lower down hallucination, I used **Chain-of-thought (COT)** to effectively do **prompt-engineering**. 
 


