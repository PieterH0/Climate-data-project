# Climate-data-project
Small (ongoing) data science project on climate data from the Danish Meteorological Institute ([DMI](https://www.dmi.dk/)). The prupose of this project is to improve my skills in data science and to get experience working with meteorological and climate data.

## Notebooks
The project contains a number of notebooks each containing a smaller project.

### Monthly_temp.ipynb
Jupyter notebook that loads climate data from DMI's [Open Data API](https://www.dmi.dk/frie-data) using the requests package. The data is loaded into Geopandas' GeoDataFrame and the monthly average temperature across Denmark across 15 years is animated using matplotlib. 

GeoJSON of Denmark (dk.json) from [simplemaps.com](https://simplemaps.com/gis/country/dk) under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).


Things learned from project:

- Accessing data through an API using requests
- Working with GeoDataFrame in GeoPandas

![alt text](/Media/WeatherDenmark.gif)



## License

MIT License  
See `LICENSE` file for details.