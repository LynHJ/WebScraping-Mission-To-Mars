# Mission To Mars


## Background
The topic of migrating to Mars is getting hot.Elon Musk's projects like SpaceX, Starlink,Mars migration program,etc.Each porject he have launched brings hope to human society. I am also very interesting on exlporing Universe. Mars perhape is our next destination to continute next human generations.  
This project has two parts. First part is scraping news from 'https://redplanetscience.com ' and storing data in MongoDB and as a json file. Second part is also using scraping skill to retrieve weather data from another website. Then based on the dataset, I will perform some simple data analsis.  

### Source

1. https://redplanetscience.com    
![alt text](https://github.com/LynHJ/web-scraping-challenge/blob/2177e6d85f8130523f4f55cf02a6f30c9f0ed65d/Mission_to_Mars/OputData/MarsWeatherData.png)  

2. https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html   
![alt text](https://github.com/LynHJ/web-scraping-challenge/blob/2177e6d85f8130523f4f55cf02a6f30c9f0ed65d/Mission_to_Mars/OputData/redplanetscience.png)  

---

### Part  1: Scrape Mars News  

##### Stroing data in MongoDB:  

![alt text](https://github.com/LynHJ/web-scraping-challenge/blob/610da38d6720db9089b716a7892c5c7aaf301219/Mission_to_Mars/OputData/MongoDB.png)  

## Part 2: Scrape and Analyse Mars Weather Data

![alt text](https://github.com/LynHJ/web-scraping-challenge/blob/67501cec27df0cd71aff8ec3f64b20ee4d443978/Mission_to_Mars/OputData/AveTempByMonth.png)  
##### Summary:  
![alt text](https://github.com/LynHJ/web-scraping-challenge/blob/ade26ca6b0bdebde7e128a4806ffd0e37c2b907d/Mission_to_Mars/OputData/AvePresByMonth.png)  
##### Summary:  
![alt text](https://github.com/LynHJ/web-scraping-challenge/blob/67501cec27df0cd71aff8ec3f64b20ee4d443978/Mission_to_Mars/OputData/DailyTemp.png)  
##### Summary:  
 
---

## Content:
```
Project  
├── Mission_to_Mars  
│   ├── Mars_News_Scraping.ipynb  
│   ├── Mars_Weateher_Data_Collecting.ipynb  
│   ├── OputData  
│   │   ├── AvePresByMonth.png  
│   │   ├── AveTempByMonth.png  
│   │   ├── DailyTemp.png  
│   │   ├── MarsWeatherData.png  
│   │   ├── MongoDB.png  
│   │   ├── data.json  
│   │   ├── redplanetscience.png  
│   │   └── temperatureData.csv  
│   └── temperatureData.csv  
├── README.md  
├── requirements.txt  

```

## Installation

pip install -r requirements.txt  







