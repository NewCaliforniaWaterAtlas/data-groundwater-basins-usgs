TopoJSON conversion of Aquifer Boundaries 
https://github.com/mbostock/topojson


1. Install TopoJSON (https://github.com/mbostock/topojson/wiki/Installation)
```
sudo npm install -g topojson
```
2. Test TopoJSON installed
```
which topojson
/opt/local/bin/topojson
```
3. Convert .shp file to topojson. https://github.com/mbostock/topojson/wiki/Command-Line-Reference
```
$ sudo topojson -o topojson/alvaqfp025-aluvial-aquifers-edit.json aquifers_edit/aquifrp025.shp                        
bounds: -124.47185529933108 31.329513634432033 -108.9468532848723 46.21443564829474 (spherical)
quantization: 173m (0.00155°) 166m (0.00149°)
topology: 1060 arcs, 56688 points
prune: retained 1060 / 1060 arcs (100%)
```
