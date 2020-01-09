
#  Predicting Technology Trends
**Using Natural Language Processing and Deep Learning to predict upcoming technology trends based on web-scraped data and a growing database of jobs posted from LinkedIn/Indeed.**

## Motivation

This project seeks to create opportunities and solve challenges for:
* Recruiting Firms: Solving the Pipeline Frustration
* Growing Companies: Planning Accurate Tech Roadmaps
* Job Seekers: Acquiring Emerging Tech Skills


## Tech Framework 

* Data Mining: Python, Pandas, BeautifulSoup, HTML/CSS. 
* Data Storage: SQLite, BigQuery.
* Visualizations: Plotly, DeckGL, Mapbox, [Streamlit](https://www.streamlit.io/). 
* Machine Learning: Natural Language Processing (Trigrams), LSTM/Softmax, Time-Series; Keras and NLTK.

![Methodology](Methodology.png)

## How-to Guide

This is a 'demo' version of the original project. I have removed the web scraping applications to avoid overloading LinkedIn/Indeed servers but I'm happy to share that code as well. 

Streamlit is an exciting and user-friendly platform built for Data Scientists who seek a professional avenue to display projects without the need to learn additional programming skills. I am not associated with or endorsed by Streamlit but suggest others try it out to experience it as well. With that said, this project will not work as intended without first installing [Streamlit](https://www.streamlit.io/). 

**The rest is simple:**
#### Enter a position of interest (limited to tech positions for now).* 
![Search Bar](Search_Bar.png)
#### Examine the database results from previous data mining as well as the real-time web scraping of current results. 
![Results](First_Results.png)
#### Explore the locations of the random samples across the US. 
![Random Sampling](Location_Map.png)
#### Examine the emerging technologies identified by the NLP/Deep Learning algorithm. 
![Emerging Tech](Emerging_Tech.png)
#### Notice the trends over time for particular skills related to the position of interest. 
![Skill Trends](Skill_Trend.png)

 

