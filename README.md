#GPS 

###Danny's Notes
I'd like to analyze multi-path error in the pickup/dropoff coordinates as it relates to building bulk density (urban canyon effect). This is somewhat related to my work. There is also fare data and tip data and temporal data so if multipath error isn't interesting there's def. some other uses for the data.

Basically, I'd like to use this data and the building bulk data to help predict error in GPS (in this case Taxi's rather than study subjects) as distance from nearest Roadbed and in the areal unit of Census Block. I can handle GIS processing but not savvy with statistical analysis.

---

Danny Tasks:

Choose a date. 
Build a Kernel Density. 
Print out 20 rows of data. 
	

####Links:
* [Taxi Data on Google Big Query](https://bigquery.cloud.google.com/table/833682135931:nyctaxi.trip_data)

* (SQL Query 1000)[https://bigquery.cloud.google.com/results/api-project-613643693354:job_mGbEYdCir9yzU1sgmMHrS9LVZ_8]


* [Taxi Data as Foiled from Chris Whong](http://chriswhong.com/open-data/foil_nyc_taxi/)

* [MapBox Blog Post](https://www.mapbox.com/blog/nyc-taxi/)

* [GPS Stationary Battery Test](https://cartodbacademy.cartodb.com/viz/26250460-05d8-11e4-9e73-0e73339ffa50/public_map)

* [Building Bulk Quartiles - not actual values](http://cartodbacademy.cartodb.com/viz/0e12d8f0-f185-11e3-a6bc-0e73339ffa50/embed_map)

* [NYC Open Data Roadbed shapefile](https://data.cityofnewyork.us/City-Government/Roadbed/xgwd-7vhd)

* [Multipath Error Diagrames on Goolge Image Search](https://www.google.com/search?q=multipath+error&es_sm=91&tbm=isch&imgil=lmyptHWdWtcRkM%253A%253Bkp_kCkAnfbpKCM%253Bhttp%25253A%25252F%25252Fgeoawesomeness.com%25252Fgnss-reflectometry-making-use-multipath-altimeter-measurements%25252F&source=iu&pf=m&fir=lmyptHWdWtcRkM%253A%252Ckp_kCkAnfbpKCM%252C_&usg=__93l_45AVQN1KYvCtk_LIsb7VahM%3D&biw=1327&bih=751&ved=0CDAQyjc&ei=thXtVOuVBMaoNuPqgzA#imgdii=_&imgrc=lmyptHWdWtcRkM%253A%3Bkp_kCkAnfbpKCM%3Bhttp%253A%252F%252Fgeoawesomeness.com%252Fwp-content%252Fuploads%252F2014%252F01%252Fmultipath.gif%3Bhttp%253A%252F%252Fgeoawesomeness.com%252Fgnss-reflectometry-making-use-multipath-altimeter-measurements%252F%3B337%3B268)
