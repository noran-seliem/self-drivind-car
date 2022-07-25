# Indoor Localization Using Machine Learning
Get the location of a moving object inside the building, decides in which room it is.
## steps
* Get the wi-fi strength in each region detected by the ESP.
* Train `random forest` model on the collected data and test it,
the model have an accuracy of 98%
* On the use, the ESP collects the strength and send it to `Flask server` .
* the position is displayed on a `Flutter app` 
  
```image of the app and the wifi strengt 