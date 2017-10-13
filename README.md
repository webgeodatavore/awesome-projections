# Awesome Projections

The intent of this repository is to gather informations related to maps projections.

It can be any type of support (books, comics, website, videos, articles, dedicated libraries for developers, demos,...)

We are looking to improve content organization, add more descriptions (terse or absent at the moment) and adding more interesting links. Feel free [to open a PR](http://github.com/webgeodatavore/awesome-projections) to discuss about any suggestions.

If you don't have a Github account, you can also make feedback using a freely editable online editor called ["Framapad"](https://semestriel.framapad.org/p/uIjOFLvBvw) (no password, no account)

## Books

* [Map projections: A working manual](https://pubs.er.usgs.gov/publication/pp1395)
* [Elements of map projection with applications to map and chart construction](https://archive.org/details/cu31924003898271)

## Courses

* [Geometric aspects of mapping](https://kartoweb.itc.nl/geometrics/Map%20projections/mappro.html) by R. Knippers
* [Cartographical Map Projections](http://www.progonos.com/furuti/MapProj/Normal/TOC/cartTOC.html) by Carlos A. Furuti
* [Excerpt from "MapSchool"](http://mapschool.io/#the-shape-of-the-earth)
* [Map Projections part](http://www.axismaps.com/guide/projections/) in "Thematic Cartography Guide. A short, friendly guide to basic principles of thematic mapping"

## Arts

### XKCD (comics)

* [Bad Map Projection: Liquid Resize](https://xkcd.com/1784/)
* [Map Projections](https://xkcd.com/977/)

### Artists using mapping projection

* [Agnes Denes exposition at Fenwick Gallery](http://fenwickgallery.gmu.edu/agnes-denes/)

## Videos

* [Why all world maps are wrong](https://www.youtube.com/watch?v=kIID5FDi2JQ) (Vox)
* [Cartographers for Social Equality - The West Wing](https://www.youtube.com/watch?v=OH1bZ0F3zVU)
* [The Impossible Map](https://www.onf.ca/film/impossible_map/)

## Websites

### Compare countries size

* [The true size of ...](http://thetruesize.com)

### Convert/choose/reproject projections

* [epsg.io](http://epsg.io)
* [ProjFinder](http://projfinder.com) with [Github code](https://github.com/aaronr/projfinder.com)
* [Projection Wizard](http://projectionwizard.org), an online map projection selection tool, by [Bojan Šavrič](http://projectionwizard.org/BojanSavric/).
* <http://bboxfinder.com>
* [Reprojections Dogeo](https://projection.dogeo.fr) (French mainly)

### EPSG codes

<quote>The IOGP’s EPSG Geodetic Parameter Dataset is a collection of definitions of coordinate reference systems and coordinate transformations which may be global, regional, national or local in application." ([official website](http://www.epsg.org/))</quote>

* [Wikipedia EPSG](https://en.wikipedia.org/wiki/International_Association_of_Oil_%26_Gas_Producers#European_Petroleum_Survey_Group) page
* [EPSG official registry](https://www.epsg-registry.org)
* <http://epsg.io>
* <http://spatialreference.org>

## Articles

* [The problem with maps](http://mjmdavis.com/showing/2017/05/16/how-to-read-maps.html)
* [Mercator Madness](http://mjmdavis.com/showing/2017/04/29/mercator-madness.html)
* [All maps are wrong. I cut open a globe to show why.](http://www.vox.com/world/2016/12/2/13817712/map-projection-mercator-globe)
* [Misleading maps and problematic projections](http://www.economist.com/blogs/graphicdetail/2016/12/daily-chart-1)
* [Top 7 maps that ultimately explain map projections](http://geoawesomeness.com/top-7-maps-ultimately-explain-map-projections/)
* [Map Projections: Flatten the Sphere](http://gisgeography.com/map-projections/)
* [Look, Ma, No More Mercator Tiles](http://vis4.net/blog/posts/no-more-mercator-tiles/)
* [This map of Earth is the most accurate ever produced, and it looks completely different](https://www.indy100.com/article/map-earth-projection-mercator-gall-peters-authagraph-accuracy-area-globe-fold-7395716)
* [I would map 500 miles](http://cartonerd.blogspot.com/2014/05/i-would-map-500-miles.html) by Kenneth Field
* [Australia's latitude and longitude coordinates out by more than 1.5 metres, scientists say](http://www.abc.net.au/news/2016-07-28/aust-latitude-longitude-coordinates-out-by-1-5m-scientists/7666858)

## Presentations

* [Projections and datums in web mapping: an introduction](http://lyzidiamond.com/nacis-2017/)
* [Projections and Coordinate Systems - for the modern mapper](http://mjfoster83.github.io/projections/)

### Miscellanous

* [lon, lat, lon](http://www.macwright.org/lonlat/) A single-page website that explains the difference between lat/lon and lon/lat in various software and specifications

## Demos

* Some [new projections related demos](http://projectionwizard.org/BojanSavric/projections.html) with associated papers. It includes [adaptive Composite Map Projections](http://cartography.oregonstate.edu/demos/AdaptiveCompositeMapProjections/) by Bernhard Jenny, Cartography and Geovisualization Group at Oregon State University.
* [Map projections demos](https://www.jasondavies.com/maps/) covering interrupted maps, butterfly maps, retroazimuthal projections and other projections related contents. Demos based on D3, by Jason Davies.
* [Comparing Map Projections](https://bl.ocks.org/syntagmatic/ba569633d51ebec6ec6e)
* [Personal World Map](http://www.personalworldmap.org/), change the center of the map and display the center on a globe approximated.

## Projections images illustrations

* [List of map projections](https://en.wikipedia.org/wiki/List_of_map_projections)
* <http://www.csiss.org/map-projections/>
* Nearly a meme now > <https://twitter.com/vicchi/status/814549529831895040>
* [Australian coastline shown using 10 different map projections](https://www.reddit.com/r/MapPorn/comments/5l0ac9/australian_coastline_shown_using_10_different_map/)

## Libraries

### C / C++

[proj.4](http://proj4.org) is a standard Unix filter function which converts geographic longitude and latitude coordinates into cartesian coordinates (and vice versa), and it is a C API for software developers to include coordinate transformation in their own software.
[GDAL (Geospatial Data Abstraction Library)](http://gdal.org) is a translator library for raster and vector geospatial data formats that is released under an X/MIT style Open Source license by the Open Source Geospatial Foundation. Although it's purpose is related to spatial data formats, it also manage well projections changes for raster and vector formats.

### Java

* [JMapProjLib](https://github.com/OSUCartography/JMapProjLib) Java Map Projection Library
* [Coordinate Transformation Suite (abridged CTS)](https://github.com/orbisgis/cts) is a library developed to perform coordinate transformations using well known geodetic algorithms and parameter sets. It strives to be simple, flexible and interoperable, in this order.

### JavaScript

* <http://proj4js.org>
* <https://github.com/d3/d3-geo-projection/>

### Python

* <https://github.com/jswhit/pyproj>
* <https://github.com/geo-data/python-epsg>

### Go

* <https://github.com/pebbe/go-proj-4>
* <https://github.com/omniscale/go-proj>

### Rust

* <https://github.com/georust/rust-proj>

## Software

* [CanvasMap](https://github.com/OSUCartography/CanvasMap) is a simple HTML framework to experiment with projection equations.
* [Flex Projector](http://flexprojector.com) is a freeware, cross-platform application for creating custom world map projections, implemented with Java
* [G.Projector — Global Map Projector](http://www.giss.nasa.gov/tools/gprojector/) by the NASA. G.Projector transforms an equirectangular map image into any of over 125 global and regional map projections. Longitude-latitude gridlines and continental outlines may be drawn on the map, and the resulting image may be saved to disk in GIF, JPEG, PDF, PNG, PS or TIFF form.

## Academic references

## English

* Looking for input. Maybe look at creating something like [a Zotero group](https://www.zotero.org/support/groups) about projections to avoid adding to much content targeting specialists, researchers in this repo.

Notes: you can find a lot of contents on the [ICA (International Cartographic Association) Commission on Map Projections site](http://ica-proj.kartografija.hr/home.en.html). See if duplication required.

## French

* Colette Cauvin, "Au sujet des transformations cartographiques de position", Cybergeo : European Journal of Geography [En ligne], Cartographie, Imagerie, SIG, document 15, mis en ligne le 14 janvier 1997, consulté le 03 avril 2017. URL : <http://cybergeo.revues.org/5385> ; DOI : 10.4000/cybergeo.5385