# python-api-challenge
## Part I: WeatherPy
This project analyzes weather data to better understand what the weather is like as we approach the equator.
- It visualizes the weather of 500+ randomly selected cities across the world using the the OpenWeatherMap API, and 
- Creates a representative model of weather across world cities.

The project consists of:
- a Jupyter notebook (MT_WeatherPy.ipnyb) that uses Pandas, MatPlotlib and the OpenWeatherMap API to create and analyze this weather model.
- A series of scatterplots and linear regression models that are visible within the notebook and stored as .png files in the WeatherPy\output_data\ folder.

## Part II: VacationPy
This project chooses ideal vacation destinations.
- It filters through a list of more than 500+ randomly selected cities across the world, looking for those with ideal weather conditions.
- It uses the Google Places API to finds hotels close to those perfect locations.
- And it uses Jupyter-gmaps to visualize these locations across a worldwide humidity map.

The project consists of:
- a Jupyter notebook (MT_VacationPy.ipnyb).
- A worldwide humidty heatmap and a map overlaid with the destination hotels, both stored as .png files in in the WeatherPy\output_data\ folder.  
Notes
I had to enable the following in order for my maps to display in Jupyter:
- jupyter nbextension enable --py gmaps
- jupyter nbextension enable --py widgetsnbextension
