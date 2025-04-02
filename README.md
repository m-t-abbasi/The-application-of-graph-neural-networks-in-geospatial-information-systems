# Data sets used in the included papers for this review 
In this review, we present a comprehensive list of publicly available datasets that have been referenced in the studies included. This collection highlights the primary data sources used in various papers and serves as a valuable resource for researchers seeking comparable datasets in related fields.

<ul>
    <li><a href="#Traffic sensor data">Traffic sensor data</a></li>
    <li><a href="#Recommender systems">Recommender systems</a></li>
    <li><a href="#Environmental sensors">Environmental sensors</a></li>
    <li><a href="#Crime">Crime</a></li>
    
</ul>

<h2 id="Traffic sensor data">🚗 Traffic sensor data</h2>

🗄️ METR-LA

This dataset contains traffic speed and volume collected from the highway of the Los Angeles County road network, with 207 loop detectors. The samples are aggregated in 5-minute intervals. The most frequently referenced time period for this dataset is from March 1st to June 30th, 2012. 

- [METR-LA Data](https://github.com/liyaguang/DCRNN) 
---

🗄️ Performance Measurement System (PeMS)

This dataset contains raw detector data from over 18,000 vehicle detector stations on the freeway system spanning all major metropolitan areas of California
from 2001 to 2019, collected with various sensors including inductive loops, side-fire radar, and magnetometers. The samples are captured every 30 s and aggregated in 5-minute intervals. Each data sample contains a timestamp, station ID, district, freeway ID, direction of travel, total flow, and average speed. Various subsets of PeMS data have also been used in studies, including:

PeMS-BAY: This subset contains data from 325 sensors in the Bay Area from January 1st to June 30th, 2017.
PeMSD3: This subset uses 358 sensors in the North Central Area. The frequently referenced time period for this dataset is September 1st to November 30th, 2018.
PeMSD4: This subset uses 307 sensors in the San Francisco Bay Area. The frequently referenced time period for this dataset is January 1st to February 28th, 2018.
PeMSD7: This subset uses 883 sensors in the Los Angeles Area. The frequently referenced time period for this dataset is May to June, 2012.
PeMSD8: This subset uses 170 sensors in the San Bernardino Area. The frequently referenced time period for this dataset is July to August, 2016.


- [PeMS Data and its Subsets](http://pems.dot.ca.gov/) 

The dataset is readily accessible on the EPA’s official website, available in CSV format for download or through an API for seamless integration. To explore and utilize the data, visit the [EPA Air Quality Data Portal](https://www.epa.gov/outdoor-air-quality-data).

---

🗄️ Seattle Loop

Seattle Loop5: This dataset was collected by inductive loop detectors deployed on four connected freeways (I-5, I-405, I-90, and SR-520) in the Seattle area, from January 1st to 31st, 2015. It contains the traffic speed data from 323 detectors. The samples are aggregated in 5-minute intervals.

- [PeMS Data and its Subsets](https://github.com/zhiyongc/Seattle-Loop-Data) 

---

🗄️ T-drive

This dataset contains a large number of taxicab trajectories collected by 30,000 taxis in Beijing from February 1st to June 2nd, 2015.

- [T-drive Data](https://www.microsoft.com/en-us/research/publication/t-drive-driving-directions-based-on-taxi-trajectories/)

---

🗄️ SHSpeed (Shanghai Traffic Speed) 

This dataset contains 10-minute traffic speed data, derived from raw taxi trajectory data, collected from 1 to 30 April 2015, for 156 urban road segments in the central area of Shanghai, China.

- [SHSpeed Data](https://github.com/xxArbiter/grnn)

---

🗄️ TaxiBJ 

This dataset contains inflow and outflow data derived from GPS data in more than 34,000 taxicabs in Beijing from four time intervals: (1) July 1st to October 30th, 2013; (2) March 1st to June 30th, 2014; (3) March 1st to June 30th, 2015; and (4) November 1st, 2015 to April 10th, 2016. The Beijing city map
is divided into 32 × 32 grids and the time interval of the flow data is 30 min.

- [TaxiBJ Data](https://onlinelibrary.wiley.com/doi/10.1002/itl2.297)
https://github.com/topazape/ST-ResNet


<h2 id="Recommender systems">🗺️ Recommender systems</h2>

🗄️ Yelp

Yelp is an online location-based social platform  which allows users search, rate and review business, such as restaurants, hotels and shopping malls. The Yelp dataset is provided by the Yelp challenge. It contains 17,235 users, 37,378 restaurants and 207,945 interaction records.

- [Yelp Data](https://www.yelp.com/dataset) 

---

🗄️ Epinions

Epinions is a social based product review platform and the Epinions dataset is publicly available. The Epinions dataset contains 139,738 items, 598,329 ratings and 49,289 users, 25 categories and 240 subcategories.

- [Epinions Data](http://www.trustlet.org/downloaded epinions.html) 

---

🗄️ Foursquare

Foursquare is a location-based social networking platform that allows users to discover and share places by checking in at various locations. Users can leave reviews, rate businesses, and receive recommendations based on their activity. The Foursquare dataset contains user check-in history, location details, and social connections, making it useful for research on spatial-temporal behavior and recommendation systems.

- [Foursquare Data](https://sites.google.com/site/yangdingqi/home/foursquare-dataset) 

---

🗄️ Flickr

Flickr is a image sharing based online social platform. Users express their views and interests through social behaviours such as publishing and liking. The Flickr dataset contains 8,252 users, 82,120 images, 327,815 interaction records, and 81 categories.

- [Flickr Data](http://flickr.com/)

---

🗄️ Gowalla 

Gowalla is a location-based social network where users could share their locations by check-ins. The Gowalla dataset is publicy available. It contains users, businesses, users’ historical check-ins and online social relations information.

- [Gowalla Data]( https://www.gowalla.com)


<h2 id="Environmental sensors">🌡️ Environmental sensors</h2>

🗄️ Beijing PM2.5 Dataset 

This dataset is derived from the data interface released by the U.S. Embassy in China, and data is collected hourly. It includes PM2.5 pollution data and meteorological data. It contains various attributes such as date, time, temperature, humidity, wind speed, wind direction, and PM2.5 values.

- [Beijing PM2.5 Data](https://archive.ics.uci.edu/ml/datasets/Beijing+PM2.5+Data) 

---

🗄️ Urban Air Quality Dataset

The dataset collects air quality data hourly from 2296 stations located in 302 cities in China. Each air quality instance is composed of concentrations of six air pollutants: NO2, SO2, O3, CO, PM2.5 and PM10. In total, more than 12 million air quality instances were collected from August 2012 to May 2015.

- [Urban Air Quality Data](http://research.microsoft.com/apps/pubs/?id=246398) 

---

🗄️ KDD Cup Dataset

The dataset used in the KDD competition contains air quality data and weather data from 35 sites in Beijing and 13 sites in London. Air quality data includes the following important air pollutants: PM2.5, PM10, NO2.

- [KDD Cup Data](https://www.biendata.xyz/competition/kdd_2018/data/) 

---

🗄️ Italian Air Quality Dataset

The longest freely available record for this dataset is from March 2004 to February 2005 (one year) and contains 9358 examples of hourly average responses from an array of 5 metal oxide chemical sensors that is located on the road surface in a heavily polluted area of an Italian city.

- [Italian Air Quality Data](https://archive.ics.uci.edu/ml/datasets/Air+Quality)

---

🗄️ Indian Air Quality Dataset

The data includes several pieces of relevant information (station code, date of sampling, state, location of recording, agency, type of area, SO2, NO2, respirable suspended particulate matter, suspended particulate matter, location of data collection, PM2.5) is released by the Ministry of Environment and Forests and the Central Pollution Control Board of India under the National Data Sharing and Access Policy (NDSAP).

- [Indian Air Quality Data](https://www.kaggle.com/shrutibhargava94/india-air-quality-data)

---

🗄️ Environmental Protection Agency Dataset

Air quality data collected on outdoor monitors across the U.S. contains outdoor air quality data collected from state, local, and tribal monitoring agencies. The air quality data are collected from eighteen monitoring stations with one record per hour.

- [Environmental Protection Agency Data](https://www.epa.gov/outdoor-air-quality-data)

---

🗄️ Center Weather Bureau Dataset

The dataset is recorded every six hours and collected from 70 monitoring stations. Twenty-six features are presented in the dataset, including temperature, dew point, precipitation, wind speed and direction, etc.

- [Center Weather Bureau Data](http://opendata.cwb.gov.tw/index)

---

🗄️ GAMS Air Quality Dataset

This dataset contains indoor and outdoor air quality data recorded by GAMS. The indoor data contains: CO2, humidity, PM10, PM2.5, temperature and volatile organic compounds. The outdoor data contains: CO, NO2, O3 (1-h avg), O3 (8-h avg), PM10, PM2.5 and SO2.

- [GAMS Air Quality Data](https://github.com/twairball/gamsdataset)

<h2 id="Crime">🕵️‍♂️ Crime</h2>

🗄️ Chicago Crime Dataset

This dataset contains crime reports from the City of Chicago. The data includes information on crime types, locations, dates, and other attributes. It covers various crimes such as burglary, assault, theft, and more, recorded from 2001 to the present. The data is updated regularly and is available for public use.

- [Chicago Crime Data](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2/about_data)

---

🗄️ NYC Crime Dataset

This dataset contains information on hate crimes recorded by the New York Police Department (NYPD). It includes details such as the type of crime, date of occurrence, geographic location, crime classification based on discrimination type (race, religion, sexual orientation, etc.), and investigation status. This dataset can be used to analyze hate crime patterns, identify trends, and predict high-risk areas.

- [NYC Crime Data](https://data.cityofnewyork.us/Public-Safety/NYPD-Hate-Crimes/bqiq-cu78/about_data)


























