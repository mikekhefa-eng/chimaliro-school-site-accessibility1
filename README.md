# chimaliro-school-site-accessibility1
Determine best sites to construct new primary school in TA Chimaliro, Thyolo

#Project description
Determine best sites to construct new primary school in TA Chimaliro, Thyolo.

#Ministry's criteria
The new schools should be at least 2km away from existing primary schools, not more than 500m away from main roads, and not be located in protected areas.

#Results
A web-based map and a static map showing TA boundary, roads, existing schools, protected areas and suitable areas, with a title, legend, scale bar, north arrow and data sources.

#Data source
The data has been acquired from Department of Surveys in a form of shapefiles and an open source map.

#Reproduction instructions
clean the data by clipping the boundary, roads, protected area, and schools that fall withing TA Chimaliro. Create an environment Install or import all python libraries for the analysis such as pandas, geopandas, matplotlib, and folium Open a notebook in a preferred folder directory Save the notebook to any preferred name Load datasets and check their crs using "datasetname.crs" In a case crs of the dataset differs, the other datasets should be assigned a dataset of a the one with preferred crs using (.to crs) function Plot the clipped boundary to visualise it Perform an overlay on the clipped of roads, schools, and protected areas Create a buffer of roads and schools, and display them separatly Merge the buffer of schools and roads, and show the boundary for proper visualisation Using the difference value on the merged shapefiles using overlay method. Map title can be added at this stage Perform a dissolve function on the merged shapefiles eg .dissolve(). This function helps to visualize only areas that qualify for new school site Perform and explore function (.explore) on a dissolved datasets to display a map on a satellite image Create a map showing the boundary, suitable areas, roads, and schools Add title, data source, legend, scale bar, axes, and north arrow. specify the color and position where they should be positioned
