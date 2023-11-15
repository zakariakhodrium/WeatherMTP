# WeatherWebApp
- This repository is made for a personal project for the course of HAX712X: Software development for data science, 1st year Master of Statistics and Data science.
- As the name States we are going to create a web application for weather forecast in Montpellier where we will forecast the next four days using **Quarto**.
## Page description : 
We displayed the following information about the weather for today and forecasts of the next four days :
- An **icon** that represent the weather according to [WMO codes](https://www.umr-cnrm.fr/dbfastex/tablesOMM/index.html).
 - A **description** of the Weather.
  - A rounded value of **minimum** temperature and **maximum** temperature during the day in celsius (°C).
  - The **maximum speed of wind** during the day in Km/h.
  - The expected amount of **precipitation** during the day in millimeter.
## Packages description for the project : 
- My approach to this problem was to keep it as simple as possible with the least amount of code.
- Our data is fetched from the website of [open_meteo.com](https://open-meteo.com/en/docs/meteofrance-api) where we used **requests** and saved them in a JSON file (JavaScript Object Notation).
- To make it refresh updated everyday, we used Github Action to trigger a workflow each **[insert here an] hour** and deploy it using github pages.
- And we had to pre-process the data using **Pandas** and fix the missing values.
- To display the html code, we used the module **Ipython.display**.
- We used **[Black](https://github.com/psf/black)** to format our python code.
## Resources :  
- The cloud icons are from this [github repository](https://github.com/erikflowers/weather-icons) and of course they are in svg format.
- The rest of the icons (water drop, wind and thermometer) are taken from [google fonts and icons](https://fonts.google.com/icons).