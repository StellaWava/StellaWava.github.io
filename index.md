## PROJECT PORTIFOLIO- ENGINEERING, GIS & APPLIED SCIENCE (ML)
---

##  DATA PROCESSING

### Web Scraping
In this project,I exploited the web crawling frameworks of scrapy, and requests packages to create custom pipelines to extract Airquality geospatial data from the EPA AirNow AirQuality monitoring website. The site host a vast amount of data, but the pipeline utilises the simplest workflow to collect and store data including FeatureClasses for data science investigation taks.
All code and processing were executed with Vscode IDE.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Vscode)](#)

[View request approach on Github](https://github.com/StellaWava/web-scrapping/blob/main/AirNow1.py)
[View scrapy approach on Github](https://github.com/StellaWava/web-scrapping/blob/main/dpgis/dpgis/spiders/sample.py)

---

## BIG DATA SYSTEMS & ARCHITECTURE

#### COVID-19 Data Engineering System: How efficient were lock-down policies towards mitigating deaths?
The COVID-19 pandemic remains the pandemic of the century claiming over 7 million lives and leaving mostly many countries in devastating economic recessions.  In this project, I designed and implemented a comprehensive data engineering system to analyze post COVID-19 incident records and evaluate the efficiency of [lockdown policies](https://ourworldindata.org/metrics-explained-covid19-stringency-index) to mitigate deaths during through the period. Designed using GCP cloud resources, the system combined real-time and batch data processing to create advanced analytics and visualizations for actionable insights. Results indicated that only *China* total lockdown policy was effective in cubbing death rates. 
Tools used: *Apache Kafka*,*Hadoop HDFS, Apache Spark*, *Cloud Storage and BigQuery*, *Looker Studio*, and *Vertex AI* for autoML(boosted_trees).

US vs China 

<img src="https://github.com/user-attachments/assets/b3f6fff8-659a-4a8d-9666-fc667ef83deb" width="300"> <img src="https://github.com/user-attachments/assets/78deed0f-b599-4f28-922b-c1e7ba357ac4" width="300">

Code and processing were executed with Vscode IDE, GCP UI & CLI.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Vscode)](#)

[View code and other results on Github](https://github.com/StellaWava/CSC-525-Project/tree/main)

---
## DATA ENGINEERING & MINING 

### What about Alternative fuel Stations and fuel Distribution in USA, North America?

The Alternative Fuels Data Center (AFDC) maintains collects and stores data on alternative fueling stations near you or on a route, and more. In this project, I explore this data and derive meaningful information through a using cluster algorithm that can provide you insights to inform your car fuel model purchase or driving decisions, not excluding business cases.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#)
[View code on Github](https://github.com/StellaWava/StellaWava.github.io/blob/core/projects/fuels.ipynb)


### What Level of Charging do Electric (ELEC) StationS provide?: A deep dive into the types of charging and connectors the electric vehicles have access to. 

The ELEC stations provide EV Connector Type J1772 with 2740 Level 2 charging hence the modest EV connector type used by these fuel stations.  Figure 3 displays the distribution of EV charging stations across the contiguous United States. Los Angeles, California has the highest record of EV level 2 charging stations. See Figure 3.

<img src="images/ev2.jpg?raw=true" />
 

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/pandas-white?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMIAAAEDCAMAAABQ/CumAAAAeFBMVEX///8TB1QAAEb/ygDnBIgPAFLNzNYTAFnQ0NgMAFcAAETb2eP39/oUBlfV1N7/xwDmAID/9tfLydcjG17/4Yz//vbCwM3ykcL61OfoBIwyKmgAADYAAE0AAErx8PTIxdT/+un/34T85/Lyir/lAHv50eX+9fkpH2Ma8J+4AAACEklEQVR4nO3dzVIaQRSAUYNCEIGoiYmJivnP+79hFrmLVHELZ6pnmG483xqaPruh5lb32ZkkSZIkSZIkvb52z7dZU2+rT4uH2X6rx6m31afF7M1+87dTb6tPCDWEUEMINYRQQ5MS1tu0nqtMSrhKn26e1v1WmZawyn58g4DQL4QIoSyECKEshAihLIQIoSyECKEshAihLIQIoSyECKEshAihLIQIoSyECOFA6cvM5a4nYb29yjoO4WmVvM58WPQkbF8e+RqPcDlPVp4t+xLS/W0QEBCqI8yTLpsizN8n/WmJ0CEEBAQEBAQEBIT2CF+/fci6a4hw8y7rvC3CeRYCAgICAgICAgICAgICwlCEtJYIdzdp/3+kdkKHToFQ+RjJMCEcCKF7CAdC6B7CgRC6Nylh9zGtJUJ6uNCsnsOFhhkvPAHC9x+fsloi/Pp5nXTREuH++iLpMwICAgICAgICAgICAgKC/87R7/u0lggdQkBAQEBAQEB4dYQON67UTqh9KuwkDlRBQED4R8gOF5o3Rdh8yepLGO0ez6MNPO+WQ9w3NilhvBAihLIQIoSyECKEshAihLIQIoSyECKEshAihLIQIoSyECKEshAihLIQIoSyEKJt+lL0SNeADUR4TG9cGWXHew10AkPP4aRBO9ohEuOFUEMINYRQQwg1dAKEDvd41t5t2u7lL0qSJEmSJEnSyfUXeomSFq0EzbkAAAAASUVORK5CYII=)](#) 

### Examining and Predicting Trend of ELEC Fuel Stations: What is the future trend on ELEC Fuel Stations? 
A larger volume of stations was established starting in 2010. As shown in Figure 4, the growing preference for electric vehicles (EVs) led to a significant increase in the number of electric vehicle (ELEC) stations, which began soaring from that year. Using the _Prophet Model_, I forecasted the future trends in the opening of ELEC stations, as these stations have experienced a notably higher volume of openings since 2010.

**Figure 4 indicates that there will be reletively a low establishment trend compared to the historic establishment trend.** 

<img src="images/elecforecast.png?raw=true" width="300">

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/sklearn-white?logo=scikit-learn)](#) [![](https://img.shields.io/badge/Anaconda-white?logo=anaconda)](#) [![]

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
