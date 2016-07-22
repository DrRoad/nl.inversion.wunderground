##Weather Underground app for Homey

Want to trigger your blinds when it's hot outside?
Want to close your windows screen when the wind picks up?
Want to be notified when the levels of UV become high risk?
Weather Underground app helps you accomplish these!

#Built in voice triggers
* Read Weather forecast
  * Read forecast for today (*Okay homey weather for today*)
  * Read forecast for tomorrow (*Okay homey weather for tomorrow*)
  * Read forecast for day after tomorrow (*Okay homey weather for day after tomorrow*)
  * Read how many rain has fallen today, until now (*Okay homey rainfall today*)
  * Read how many rain has fallen the past hour (*Okay homey rainfall this hour*)


#Flow triggers
* Temperature has changed
* Humidity has changed
* Temperature is above an certain degree of Celcius/Fahrenheit
* Temperature is below an certain degree of Celcius/Fahrenheit
* Humidity is above an certain percentage
* Humidity is below an certain percentage
* UV is above an certain threshold
* UV is below an certain threshold
* Wind is above an certain speed
* Wind is below an certain speed
* Wind gust is above an certain speed
* Wind gust is below an certain speed


#Flow conditions
* Temperature is above an certain degree of Celcius/Fahrenheit
* Temperature is below an certain degree of Celcius/Fahrenheit
* Humidity is above an certain degree of Celcius/Fahrenheit
* Humidity is below an certain degree of Celcius/Fahrenheit
* UV is above an certain threshold
* UV is below an certain threshold
* Wind is above an certain speed
* Wind is below an certain speed
* Wind gust is above an certain speed
* Wind gust is below an certain speed


#Flow actions
* Read forecast for today
* Read forecast for tonight
* Read forecast for tomorrow
* Read forecast for tomorrow night
* Read forecast for day after tomorrow
* Read forecast for rain this hour
* Read forecast for rain today


#Insights
* Temperature
* Humidity
* Feels like
* Air pressure
* Wind speed
* Dew point
* UV
* Sight
* Wind gust
* Wind direction
* Precepation for 1hr
* Precepation for today


#Settings
* You can use your own API key, (available here: https://www.wunderground.com/weather/api it's free!) so you can update up to every 10 minutes.
If you don't have a key the app uses my key and will update every 60 minutes.
* Use Homey's location or a custom location
* Celsius and Fahrenheit support


#Future functions
* Trigger/condition on current weather condition (Cloudy, Raining etc)
* Trigger on weather alerts
* Average/high/low temperature on this date
* Triggers and conditions for precipation 1hr/today
* Much more!


#Changes
* Version 2.0
  * Better checks to prevent undefined crashes
  * Built in triggers to read the weather forecast
  * Flow action to read the weather (Read in Homey's set language!)


#Donate
This is an open source application and totaly free. 
By donating you support me in my work of which I do in my own free time.
[![Paypal Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=AY82R46VQSSS2&lc=US&item_name=Weather%20Underground%20App%20for%20Homey&item_number=wunderground_homey&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted)


#Source
https://github.com/Inversion-NL/nl.inversion.wunderground