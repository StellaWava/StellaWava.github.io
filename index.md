##  DATA PROCESSING
---
### WEB-SCRAPING
In this project,I am exploiting the web crawling frameworks of scrapy, and requests packages to create custom pipelines to extract Airquality geospatial data from the EPA AirNow AirQuality monitoring website. The site host a vast amount of data, but the pipeline utilises the simplest workflow to collect and store data including FeatureClasses for data science investigation taks.
All code and processing were executed with Vscode IDE.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Vscode)](#)

[View request approach on Github](https://github.com/StellaWava/web-scrapping/blob/main/AirNow1.py)
[View scrapy approach on Github](https://github.com/StellaWava/web-scrapping/blob/main/dpgis/dpgis/spiders/sample.py)

### BIG DATA SYSTEMS & ARCHITECTURE
#### COVID-19Data Engineering System: How efficient were lock-down policies towards mitigating deaths?
The COVID-19 pandemic remains the pandemic of the century claiming over 7 million lives and leaving mostly many countries in devastating economic recessions.  In this project, I designed and implemented a comprehensive data engineering system to analyze post COVID-19 incident records and evaluate the efficiency of [lockdown policies](https://ourworldindata.org/metrics-explained-covid19-stringency-index) to mitigate deaths during through the period. Designed using GCP cloud resources, the system combined real-time and batch data processing to create advanced analytics and visualizations for actionable insights. Results indicated that only *China* total lockdown policy was effective in cubbing death rates. 
Tools used: *Apache Kafka*,*Hadoop HDFS, Apache Spark*, *Cloud Storage and BigQuery*, *Looker Studio*, and *Vertex AI* for autoML(boosted_trees).

US vs UK vs China 

<img src="https://github.com/user-attachments/assets/b3f6fff8-659a-4a8d-9666-fc667ef83deb" width="300">
<img src = "https://github.com/user-attachments/assets/a1f96101-4934-4127-a63e-14566a142661", width="300">
<img src="https://github.com/user-attachments/assets/78deed0f-b599-4f28-922b-c1e7ba357ac4" width="300">

Code and processing were executed with Vscode IDE, GCP UI & CLI.
[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Vscode)](#)
[View code on Github](https://github.com/StellaWava/CSC-525-Project/tree/main)


##  What about Alternative fuel Stations and fuel Distribution in USA, North America?
---
### Project Brief

The Alternative Fuels Data Center (AFDC) maintains collects and stores data on alternative fueling stations near you or on a route, and more. In this project, I explore this data and derive meaningful information through a using cluster algorithm that can provide you insights to inform your car fuel model purchase or driving decisions, not excluding business cases.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#)
[View code on Github](https://github.com/StellaWava/StellaWava.github.io/blob/core/projects/fuels.ipynb)

---

### Examining Fuel Station Distribution by Fuel Code and State, using the clean data
Electric stations(ELEC) indicate the highest record while hydrogen stations(HY) indicate the least number of records in the dataset. States with highest number of Stations include California with  > 800 electric stations
and Minnesota with almost 300 ethanol and gasoline (E85) fuel stations.  

<img src="images/image1fuel.JPG?raw=true" />

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/pandas-white?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMIAAAEDCAMAAABQ/CumAAAAeFBMVEX///8TB1QAAEb/ygDnBIgPAFLNzNYTAFnQ0NgMAFcAAETb2eP39/oUBlfV1N7/xwDmAID/9tfLydcjG17/4Yz//vbCwM3ykcL61OfoBIwyKmgAADYAAE0AAErx8PTIxdT/+un/34T85/Lyir/lAHv50eX+9fkpH2Ma8J+4AAACEklEQVR4nO3dzVIaQRSAUYNCEIGoiYmJivnP+79hFrmLVHELZ6pnmG483xqaPruh5lb32ZkkSZIkSZIkvb52z7dZU2+rT4uH2X6rx6m31afF7M1+87dTb6tPCDWEUEMINYRQQ5MS1tu0nqtMSrhKn26e1v1WmZawyn58g4DQL4QIoSyECKEshAihLIQIoSyECKEshAihLIQIoSyECKEshAihLIQIoSyECOFA6cvM5a4nYb29yjoO4WmVvM58WPQkbF8e+RqPcDlPVp4t+xLS/W0QEBCqI8yTLpsizN8n/WmJ0CEEBAQEBAQEBIT2CF+/fci6a4hw8y7rvC3CeRYCAgICAgICAgICAgICwlCEtJYIdzdp/3+kdkKHToFQ+RjJMCEcCKF7CAdC6B7CgRC6Nylh9zGtJUJ6uNCsnsOFhhkvPAHC9x+fsloi/Pp5nXTREuH++iLpMwICAgICAgICAgICAgKC/87R7/u0lggdQkBAQEBAQEB4dYQON67UTqh9KuwkDlRBQED4R8gOF5o3Rdh8yepLGO0ez6MNPO+WQ9w3NilhvBAihLIQIoSyECKEshAihLIQIoSyECKEshAihLIQIoSyECKEshAihLIQIoSyEKJt+lL0SNeADUR4TG9cGWXHew10AkPP4aRBO9ohEuOFUEMINYRQQwg1dAKEDvd41t5t2u7lL0qSJEmSJEnSyfUXeomSFq0EzbkAAAAASUVORK5CYII=)](#) 


View code on Github

---

### What Level of Charging do Electric (ELEC) StationS provide?: A deep dive into the types of charging and connectors the electric vehicles have access to. 

The ELEC stations provide EV Connector Type J1772 with 2740 Level 2 charging hence the modest EV connector type used by these fuel stations.  Figure 3 displays the distribution of EV charging stations across the contiguous United States. Los Angeles, California has the highest record of EV level 2 charging stations. See Figure 3.

<img src="images/ev2.jpg?raw=true" />
 

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/sklearn-white?logo=scikit-learn)](#) [![](https://img.shields.io/badge/Scikit%20Optimize-white?logo=data:image/png;base64,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)](#) [![](https://img.shields.io/badge/pandas-white?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMIAAAEDCAMAAABQ/CumAAAAeFBMVEX///8TB1QAAEb/ygDnBIgPAFLNzNYTAFnQ0NgMAFcAAETb2eP39/oUBlfV1N7/xwDmAID/9tfLydcjG17/4Yz//vbCwM3ykcL61OfoBIwyKmgAADYAAE0AAErx8PTIxdT/+un/34T85/Lyir/lAHv50eX+9fkpH2Ma8J+4AAACEklEQVR4nO3dzVIaQRSAUYNCEIGoiYmJivnP+79hFrmLVHELZ6pnmG483xqaPruh5lb32ZkkSZIkSZIkvb52z7dZU2+rT4uH2X6rx6m31afF7M1+87dTb6tPCDWEUEMINYRQQ5MS1tu0nqtMSrhKn26e1v1WmZawyn58g4DQL4QIoSyECKEshAihLIQIoSyECKEshAihLIQIoSyECKEshAihLIQIoSyECOFA6cvM5a4nYb29yjoO4WmVvM58WPQkbF8e+RqPcDlPVp4t+xLS/W0QEBCqI8yTLpsizN8n/WmJ0CEEBAQEBAQEBIT2CF+/fci6a4hw8y7rvC3CeRYCAgICAgICAgICAgICwlCEtJYIdzdp/3+kdkKHToFQ+RjJMCEcCKF7CAdC6B7CgRC6Nylh9zGtJUJ6uNCsnsOFhhkvPAHC9x+fsloi/Pp5nXTREuH++iLpMwICAgICAgICAgICAgKC/87R7/u0lggdQkBAQEBAQEB4dYQON67UTqh9KuwkDlRBQED4R8gOF5o3Rdh8yepLGO0ez6MNPO+WQ9w3NilhvBAihLIQIoSyECKEshAihLIQIoSyECKEshAihLIQIoSyECKEshAihLIQIoSyEKJt+lL0SNeADUR4TG9cGWXHew10AkPP4aRBO9ohEuOFUEMINYRQQwg1dAKEDvd41t5t2u7lL0qSJEmSJEnSyfUXeomSFq0EzbkAAAAASUVORK5CYII=)](#) 

View code on Github

---

### Examining the Trend of Establishment: How the number of stations for each type of fuel has changed over time.
These stations have been established since the 1970's. However, a larger volume of stations was established beginning of 2010. According to figure 4. Energy preference is EV hence ELEC stations are seen skyrocketing beginning 2010. 

**Figure 4: Fuel Stations by code over time**
<img src="images/overtime11.png?raw=true" /> <img src="images/overtime22.png?raw=true" />

View code on Github
---

### Optimal Placement Analysis: Using Cluster Analysis
The project purpose is to apply a well known algorithm to understand our data.I used K-Means clustering methods to identify clusters of current stations and then analyze gaps. Additionally, demand prediction was handled using regression models.

**Figure 5: Clusters of Fuel Stations across the Contiguous USA**
<img src="images/station_clusters.png?raw=true"/>

In Figure 6, I determined the areas with low coverage where new fuel stations would very suitable. This prediction however, only relies on the current clusters but inclusion of datasets such as traffic and population would enhance the model to provide more precise locations for station placement. 
**Figure 6: Optimal areas for New Station Placement**
<img src="images/new_station_suggest.png?raw=true"/>

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/Anaconda-white?logo=anaconda)](#) [![](https://img.shields.io/badge/Geopandas-white?logo=Geopandas)](#) [![](https://img.shields.io/badge/Bash-white?logo=GNUbash)](#)

---

### Predicting Establishment trend for ELEC Fuel Stations: Forecasting Future Trends for New Station Openings.
Using the prophet model, I predicted the  future trends in station openings of the ELEC stations since these stations indicate a larger opening volume since 2010. 
**Figure 7 indicates that there will be reletively a low establishment trend compared to the historic establishment trend.** 
<img src="images/elecforecast.png?raw=true"/>

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/sklearn-white?logo=scikit-learn)](#) [![](https://img.shields.io/badge/LIME-white?logo=LIME)](#) [![](https://img.shields.io/badge/SHAP-white?logo=SHAP)](#)

---


<!-- <p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p> -->
<!-- Remove above link if you don't want to attibute -->

<!-- ## 👋 Welcome to my portfolio

Hello! My name is Stellamaris, and I set up this page to showcase my data mining project I've been working on.

In the past 7 years, I've studied at two of the world's best universities and worked in a variety of industries, gaining experience in data engineering, machine learning, strategy, analytics and management. My [CV](Nakacwa Stellamaris_RESUME_ta.pdf) has plenty of information about the professional projects I've worked on, but the purpose of this page is to showcase some of my favourite personal (on-the-side) projects in a more visual way. 

If you have any questions, feel free to drop me an [email](stellamarisus16@gmail.com) or send me a message on [LinkedIn](https://www.linkedin.com/StellaWava/). 

Thanks for reading,

Stellaamaris

---
 -->
 
 -->
