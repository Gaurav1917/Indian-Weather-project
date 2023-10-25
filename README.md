# Indian-Weather-project
1.Dataset: https://www.kaggle.com/datasets/nelgiriyewithana/indian-weather-repository-daily-snapshot
This dataset provides real-time weather information for major cities in India. Unlike forecast data, this dataset offers a comprehensive set of features that reflect the current weather conditions.

2.About project: The ML model is used to predict the weather condition. The dataset having the 40+ features including temperature, wind, pressure, precipitation, humidity, visibility, and air quality measurements.

     #)Target column - 'condition_text' is the target column it contain some category like,
                        sunny,cloudy,clear,Light rain etc.
 Basically it is a multiclass classification model.  
 
3.Algorithms: The model is made by using random forest classifier algorithm with hyperparameter tunning.

     #Accuracy:
       Training data - 97%
       Test data - 94%

## Weather Analysis
### 1) What is the weather condition at high and low latitude?.

![download (17)](https://github.com/Gaurav1917/Indian-Weather-project/assets/146158309/4107151b-536b-4450-aa09-24b8e7a4ba40)
![download (18)](https://github.com/Gaurav1917/Indian-Weather-project/assets/146158309/d70a34b5-23ac-4308-a654-6434d216d289)
![download (19)](https://github.com/Gaurav1917/Indian-Weather-project/assets/146158309/e6defbbb-658c-4fcf-bedc-e8ea12c42fe8)

a) At high latitude weather condition is (Light freezing rain, patchy snow possible and patchy light snow with thunder) colder.

b) At low latitude weather condition is (Heavy rain at times, Torrential rain shower).

c) Reason is temperature become lower as we moving towards high latitude areas.

### 2) What is wind speed(kph) in different weather condition?.

![download (1)](https://github.com/Gaurav1917/Indian-Weather-project/assets/146158309/091b7831-11bd-4f48-b8e1-4039c8da8c09)

a) Wind speed is maximum during 'Heavy rain'.

b) At heavy rain wind speed is 37 kph.

c) The average wind speed during heavy rain is 17 kph.

### 3) Weather condition on different temperatures?.

![download (8)](https://github.com/Gaurav1917/Indian-Weather-project/assets/146158309/82191fb9-cd5d-40f7-b3f3-dd17efe3d3f7)
![download](https://github.com/Gaurav1917/Indian-Weather-project/assets/146158309/7ac8c9ad-8366-4fc2-8d41-51edd39d299d)

a) At high temperatures the weather condition is Sunny.

b) At lowest temperature the weather is Moderate or heavy snow with thunder.

### 4) Visibility at different condition ?.

![download (2)](https://github.com/Gaurav1917/Indian-Weather-project/assets/146158309/6750993d-c87b-430a-b8de-9e2ba6ee6281)

a) The visibility is almost good in majority of condition given on graph.

b) Except Fog , the visibility of fog is minimum i.e zero or near to zero.

### 5) How temperature changes according to the region in india?.

![download (4)](https://github.com/Gaurav1917/Indian-Weather-project/assets/146158309/58bef50c-41cb-41ab-98ad-a3c19269f741)
![download (5)](https://github.com/Gaurav1917/Indian-Weather-project/assets/146158309/6bb7011e-3c7a-4fa0-a603-98a43fc99ff8)
![download (3)](https://github.com/Gaurav1917/Indian-Weather-project/assets/146158309/3a4bb76f-cf47-401b-a798-72f54371e8a7)

a) The Temperature is low in the state like Arunachal pradesh, jammu and kashmir, Uttarakhand, HimachalPradesh.

b) This states located at high latitude and have low temperature.

c) Region with high temperature are Uttarpradesh, Rajasthan, Delhi .

### 6) Air Quality index for different region?.

![plot](https://github.com/Gaurav1917/Indian-Weather-project/assets/146158309/e17f02da-3cd5-4b20-b499-a3bd61ea75a0)
![newplot (2)](https://github.com/Gaurav1917/Indian-Weather-project/assets/146158309/69230f60-71ec-4de4-89d1-b2eee216db93)
![download (13)](https://github.com/Gaurav1917/Indian-Weather-project/assets/146158309/87a68ead-ac08-4570-ae0b-76d8f8bd5c93)
![newplot (1)](https://github.com/Gaurav1917/Indian-Weather-project/assets/146158309/11571238-dbf4-4a52-9743-9fb1e534f2ed)
![download (10)](https://github.com/Gaurav1917/Indian-Weather-project/assets/146158309/868ec520-0da0-4d0c-b9e6-cb42ce5baf1a)
![download (12)](https://github.com/Gaurav1917/Indian-Weather-project/assets/146158309/fdee0869-b6e8-405e-a814-541b83bee1e1)

a) AQI PM2.5 -

      # Delhi has highest AQI PM2.5 of 470.
      # The average AQI PM2.5 of delhi is 120.
      # The lowest AQI PM2.5 of delhi is 20.
      # Andaman and nicobar island has lowest AQI PM2.5 .
      
b) AQI PM10 -

      # Delhi has highest AQI PM10 of 670.
      # The average AQI PM10 of delhi is 180.
      # The lowest AQI PM10 of delhi is 30.
      # Andaman and nicobar island has lowest AQI PM10 .
      
c) AQI Nitrogen dioxide.

      # Delhi has highest AQI NO2 of 75.
      # The average AQI NO2 of delhi is 31.
      # The lowest AQI NO2 of delhi is 6.
      # Andaman and nicobar island has lowest AQI NO2 .
      

 d) AQI Sulphur dioxide.

      # Delhi has highest AQI SO2.
      # West bengal, chhattisgarh and Haryana have high AQI SO2
      # Arunachal Pradesh, Mizoram and Andaman and nicobar island have low AQI SO2 .

e) AQI Carbon Monoxide.

      # Delhi has highest AQI CO of 2000+.
      # Punjab ,West bengal, chhattisgarh , Uttarpradesh, Haryana have high AQI CO
      # Lakshadweep ,Daman and Diu, Mizoram, Arunachal Pradesh have low AQI CO.

### UV index of different region?.

![download (6)](https://github.com/Gaurav1917/Indian-Weather-project/assets/146158309/672fc094-838e-4836-b9db-cc300da3d9f8)
![download (7)](https://github.com/Gaurav1917/Indian-Weather-project/assets/146158309/02489717-ce99-4fd5-ac26-73ebabb34cd4)





### How Humidity Changes with Temperature across different region ?.

![newplot (3)](https://github.com/Gaurav1917/Indian-Weather-project/assets/146158309/887641e4-7cac-44a9-a8b0-5483099b8b3b)





      
    
      
    








