# Jupiter Notebook - python - adding data

This Jupyter Notebook processes a dataset of points of interest (POIs) by enriching it with corresponding city and district information. The main functionality of the notebook includes:

>> Loading geographic data (GeoJSON or shapefiles) representing city and district boundaries.
>> Assigning each POI a matching city and district based on its geographic coordinates using spatial joins.
>> Cleaning and exporting the enhanced POI dataset for further analysis or visualization.

This data processing step was necessary to build an interactive map in Power BI, which can now be filtered by both city and district. This functionality was used as part of a final academic project for Gdańsk University of Technology. The Power BI dashboard focuses on analyzing apartment prices in Gdańsk based on data collected using a custom web scraper. The scraper extracts listing information from the Otodom website, which publishes property sale offers.
