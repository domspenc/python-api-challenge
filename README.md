<h1>Python API Challenge</h1>
<img
        src="https://www.worldatlas.com/r/w960-q80/upload/ef/4f/43/shutterstock-1445255762.jpg"
        alt="Image of a world map showing colour-coded temperatures close to and away from the equator"
        width="650"
      />
</br>
<h3><u>Description</u></h3>
<p>
"What is the weather like as we approach the equator?"
</br>
This repository contains two parts; the first, WeatherPy, is a python analysis of temperatures in cities around the world, identifying any correlation between various weather variables and latitude (specifically), including plots to visually demonstrate the findings. The second, VacationPy, is a python-led experiment identifying hotels in cities that meet my personal 'ideal holiday' requirements, relating to the weather.</p>
</br>
<h3><u>Some Notes and Observations</u></h3>
</br>
<p>- A number of scatterplots were generated reflecting the following relationships:</p> 
</br>
<p>- Latitude vs. Temperature.</p> 
</br>
<p>- Latitude vs. Humidity.</p> 
</br>
<p>- Latitude vs. Cloudiness.</p> 
</br>
<p>- Latitude vs. Wind Speed.</p> 
</br>
</br>
<p>- Regression lines and equations were later calculated, reflecting the above relationships, with data split between Northern and Southern hemispheres. Plots can be seen in the ipynb file, however the results for each subgroup are as follows:</p> 
</br>
<p>- Latitude and Max Temp:  the r-value is -0.7061, indicating a strong negative relationship. For the Southern Hemisphere variables, the r-value is 0.7979, indicating a very strong positive relationship.</p> 
</br>
<p>- Latitude vs. Humidity: For the Northern Hemisphere variables, the r-value is -0.0154, indicating a very weak negative relationship. For the Southern Hemisphere variables, the r-value is 0.0402, indicating a very weak positive relationship.</p> 
</br>
<p>- Latitude vs. Cloudiness: For the Northern Hemisphere variables, the r-value is -0.0442, indicating a very weak negative relationship. For the Southern Hemisphere variables, the r-value is -0.0895, indicating a very weak negative relationship. </p> 
</br>
<p>- Latitude vs. Wind Speed: For the Northern Hemisphere variables, the r-value is 0.0077, indicating a very weak positive correlation. For the Southern Hemisphere variables, the r-value is -0.0921, indicating a weak/very weak negative correlation. </p>
</br>
<p>----------------------------------------------------------</p> 
</br>
<p>Thank you for reading!</p> 
<h3>🌞🌞🌞</h3>
</br>
<p>NB: I leaned on numerous sources for troubleshooting and help, including OpenWeatherMap API for API data and ChatGPT for definitions and function uses, Python/Matplotlib/Pandas documentation sites, plus myself and a peer studied statistics together to better understand regresson lines and correlations.</p>
</br>
<p>Image by World Atlas (worldatlas.com)</p>