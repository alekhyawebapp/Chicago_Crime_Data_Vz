**Chicago Crime Data Process and Visualization**
This project visualizes Chicago crime data by deriving neighborhood information from geospatial coordinates and analyzing spatial relationships between neighborhoods.

**Project Tasks Completed**
Neighborhood ID Derivation

Crime data points were matched with official Chicago neighborhood boundaries using a spatial join (geopandas.sjoin).

A subset of the dataset (January 2022) was used for demonstration.

Crime Heat Map Visualization

A choropleth map was created using folium to display the number of crimes per neighborhood.

Neighborhoods are color-coded based on crime volume.

Neighborhood Graph Construction (k = 5)

Centroids of each neighborhood were computed.

A k-nearest neighbors graph (k=5) was created using scipy.spatial.KDTree.

Neighborhoods are connected based on geographic proximity and overlaid on the folium map.

GitHub Pages Deployment

The interactive visualization is hosted and accessible at:
🔗 https://alekhyawebapp.github.io/Chicago_Crime_Data_Vz/

🛠️ Technologies Used
Python, Jupyter Notebook

GeoPandas, Pandas, Folium, Matplotlib

Spatial analysis with shapefiles and GeoJSON

GitHub Pages for deployment

