# piedmontite
A test server for GSI Maps Vector Consumption in ArcGIS Online

# Summary
* This server does not delivers vector tiles (pbf).
* This server delivers static htdocs contents in "htdocs" folder.
* This server now has an interface with Esri ArcGIS online.
    * It returns the index.json of the vector tile service. 
    * It returns the style.json for the styling. 
    * It retuns the simplified tilemap informaiton.

# Tested environment
* OS CentOS Linux release 7.8.2003
* nodejs v16.13.1
* npm v8.1.2

# Vector Tile Information
* Tile URL: `https://cyberjapandata.gsi.go.jp/xyz/{t}/{z}/{x}/{y}.pbf`
* Zoom levels: ZL 4-17


# References
* https://github.com/gsi-cyberjapan/gsimaps-vector-experiment  
* https://qiita.com/T-ubu/items/1f772fd92ec8dfb0c2b2
