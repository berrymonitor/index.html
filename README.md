# Please download the latest bb.js file via
# http://104.199.26.164/berrymonitor/bb.js

For the www.berrymonitor.com, the bb.js and worldwind.min.js are downloaded from BerryMonitor AWS bucket.

https://s3-eu-west-1.amazonaws.com/berrymonitor/worldwind.min.js
https://s3-eu-west-1.amazonaws.com/berrymonitor/bb.js

index.html contains the Web World Wind code for a webpage - including visual settings and other parameters. This can be copy-pasted to nearly any website with minor modifications.

bb.js (bb=BlueBerry) contains a FeatureCollection of the most likely areas, in which blueberries can be found in Finland.

bb_decim.js is a smaller decimated version of the FeatureCollection - featuring only 5-decimals in the WGS-84 coordinates.

The areas are based on open satellite data (Landsat, Sentinel) combined with open land cover and forestry data (Corine, VMI).
