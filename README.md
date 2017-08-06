Berry monitoring application using NASA Web World Wind for visualization. The spectrum libraries, applications, data processing and data visualization will open-sourced in the near future, as development continues. 

The current bb.js areas are based on open satellite data (Landsat, Sentinel) combined with open land cover and forestry data (Corine, VMI).

Visit www.berrymonitor.com for more information.

For the www.berrymonitor.com, the bb.js and worldwind.min.js are downloaded from BerryMonitor AWS bucket.

https://s3-eu-west-1.amazonaws.com/berrymonitor/worldwind.min.js

https://s3-eu-west-1.amazonaws.com/berrymonitor/bb.js

embed.html --- Contains a BerryMonitor v1.0 - including improved visual settings and other parameters for the BerryMonitor.com website. This can be copy-pasted to nearly any website with minor modifications.

bb.js (bb=BlueBerry) --- Contains a FeatureCollection of the most likely areas, in which blueberries can be found in Finland.

bb_decim.js --- Is an alternative, decimated version of the FeatureCollection - featuring only 5-decimals in the WGS-84 coordinates. Smaller in size to improve load times.

worldwind.min.js --- The latest Web World Wind source code. In case non-secure http-connection is OK, please use http://worldwindserver.net/webworldwind/worldwind.min.js

For more information, please contact atte.korhonen@aalto.fi

TO BE REMOVED 
(index.html --- Contains the BerryMonitor v0.1 webpage)

# Please download the latest bb.js file via
# http://104.199.26.164/berrymonitor/bb.js
