Leaflet.Control.Search
============

What ?
------

A leaflet control that search markers location by attribute, with ajax/jsonp autocomplete feature

Forked from Stefano Cudini's leaflet-search, this fork will include the ability to automagically search geoJSON layers imported in leaflet.  Also allow full text searching with geoJSON properties.  Should be able to search any [well-built geoJSON spec'd files](http://www.geojson.org/geojson-spec.html) including all supported feature types.

Tested in Leaflet 0.4.5

How ?
------

(Currently not ready for release)
Adding the search control to the map:

```

map.addControl(new L.Control.Search({layer: searchLayer}));
//searchLayer contains searched markers//

map.addControl(new L.Control.Search({searchJsonpUrl: 'search.php?q={s}&callback={c}'}) );
//searchJsonpUrl is jsonp service for retrieve elements locations

and insert leaflet-search.css styles to your css page

```

Where ?
------

###Source code:
	
>Orignal: https://github.com/stefanocudini/leaflet-search

>Forked (you are reading): https://github.com/roma0104/leaflet-search/

###Demos:
>Orignal: http://easyblog.it/maps/leaflet-search/

