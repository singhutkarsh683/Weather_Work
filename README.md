# Weather_Work
Program to find weather of any location from either it location name or its coordinates.

I used Python as I knew for data Mining course it is genrally used.

Since I never used python before, so I installed Anaconda in my windows laptop and choosed Jupyter notebook to run my code. i initially looked up the basic in python and basic youtube video.

Now i need weather data from a website so I choosed openweather.org to get its API KEY which could be imported to python, watching youtube video I came to know that API key is like a waiter which transfers its data from its website to my python script.
Later I went to Openweather.org crated an account to get acces to its API key and in there they showed us how to type the url to get the desired result of certain area

By seeing example code of API key on google, I came to know what code to write to gather desired information from the directed url eg. x['weather']['humidity'], it will get me info of humidity in weather section of the url.

For city input I genereated url in that way so that we get weather info of the specified city, same for the input given of Longitude and Latitude,via help of google I used its python code to find longitude and latitude which I transferred it to the url of lon and lat one to get the weather data

I used argapase as while I was scrolling in Google in search on CLI i found this code and it helped me not to used if else-code and by simply writing -c for city name, -l for longitude and latitude, -i for current location after python3 Weather.py made more easier and simpified. 
