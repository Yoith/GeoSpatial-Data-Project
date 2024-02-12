# GeoSpatial Data Project

## Overview

The GeoSpatial Data Project is focused on extracting information from a MongoDB database and utilizing APIs to perform geo queries on various locations. 

## Project Structure

The project folder includes:

**Data**: Stores databases created from the initial MongoDB database and others generated with information extracted from APIs.
  
**Images**: Contains graphics illustrating results from queries on both the initial database and APIs.
  
**Notebooks**: Includes Jupyter notebooks detailing processes using functions and Python code.

## Notebook: Exploring

This notebook covers:

- Importing libraries such as pymongo, pandas, and matplotlib.
  
- Extracting information about different companies, filtering by category, country, and city.
  
- Cleaning and manipulating data in DataFrames.
  
- Generating tokens to access the Four Square API securely.
  
- Creating functions to find geolocations in the API and insert data into MongoDB collections.
  
- Extracting information about nearby primary schools, Starbucks cafes, and design companies.

## Notebook: Visualizing

This notebook focuses on:

- Importing libraries like folium, pandas, and numpy.
  
- Visualizing data from DataFrames using pie plots and bar plots.
  
- Creating layers on a London map with different markers for companies, schools, cafes, etc.
  
- Adding a heat map layer to accumulate data points.
  
- Generating an HTML file with the map and a PDF presentation summarizing project findings.

## Conclusion

This README provides an overview of the project structure and the processes detailed in the Exploring and Visualizing notebooks. For detailed implementation and code, refer to the respective Jupyter notebooks.

### Author

Guillermo Diaz