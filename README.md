# Geospatial analysis and representation for data science

## Dall'Asen Nicola - 211662

## Florence AirBnB analysis

The report can be found in the `report.pdf` file.

To execute the notebook the following libraries are required

- Python version 3.8.6
  - folium==0.11.0
  - contextily==1.0.1
  - geopandas==0.8.1
  - geopy==2.1.0
  - matplotlib==3.3.3
  - osmnx==1.0.0
  - pandas==1.2.0
  - pygeos==0.8
  - pyproj==3.0.0.post1
  - pyrosm==0.6.0
  - rpy2==3.4.1
  - seaborn==0.11.1
  - Shapely==1.7.1
- R version 4.0.3
  - rgdal 1.5-19 
  - spdep 1.1-5

The most convenient way to install the Python dependencies is by the use of a virtual environment, following these steps:

- `pyenv install 3.8.6`
- `pyenv virtualenv 3.8.6 geospatial`
- `pyenv activate geospatial`
- `pip install -r requirements.txt`

For the R packages `install.packages()` should be sufficient

### Where is the R code?

It has been included in the Python notebook through `rpy2` which allows to call R code inside Jupyter cells

### Availability of data

The code is able to download every file it needs. If for some reasons the code is unable to download what it needs the dataset are included in this repo in the correct location.