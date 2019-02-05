# Predicting-Weather

## In this project I used the past six years' daily temperatures of my city and predicted next month's temperatures.
![Prediction](https://github.com/Shaier/Predicting-Weather/blob/master/Prediction.jpg)  

  
    
    
The idea behind this project was to practice my skills in order to eventually predict natural disasters and save lives (and also to be able to give my grandma a very simple example of what I'm doing all day- I told her about my model that can detect if an image has a cat or a dog. Needless to say, she was not impressed).    
  
I collected the average daily temperatures of my city (Portland, Oregon) from the past 6 years (April 1st 2013 to Dec 31 2018) by making several requests to [NOAA](https://www.noaa.gov/).  
I then trained a recurrent neural network (LSTM type) on the data (after preprocessing it and making it neat) to make predictions.  
As you can see in the image above, the results were quite impressive.
  
The file [Weather.ipynb](Weather.ipynb) shows my progress, along with some notes on the network.  
