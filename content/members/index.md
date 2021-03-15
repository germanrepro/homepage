+++
title = "Members"
+++

# Members

## Steering Group *&* Administration

<div class="mx-lg-negative my-4">
  {{ members(data_path="content/members/steering.toml") }}
</div>

## Local nodes

<link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css" integrity="sha512-xodZBNTC5n17Xt2atTPuE1HxjVMSvLVW9ocqUKLsCC5CXdbqCmblAshOMAS6/keqq/sMZMZ19scR4PsZChSR7A==" crossorigin=""/>
<script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js" integrity="sha512-XQoYMqMTK8LvdxXYG3nZ448hOEQiglfqkJs1NOQV44cWnUrBc8PkAOcXy20w0vlaXaVUearIOBhiXZ5V3ynxwA==" crossorigin=""></script>

<div id="map" class="mx-lg-negative" style="height: 750px"></div>
<script>
	var map = L.map('map').setView([51.163375, 10.447683], 6);
	L.tileLayer('/maps/tiles/{z}/{x}/{y}.png', {
    minZoom: 5,
		maxZoom: 7,
		attribution: 'Public domain map data by <a href="https://www.naturalearthdata.com">Natural Earth</a>',
		tileSize: 256,
	}).addTo(map);
  //
  function onEachFeature(feature, layer) {
    // does this feature have a property named popupContent?
    if (feature.properties && feature.properties.popupContent) {
        layer.bindPopup(feature.properties.popupContent);
    }
  }
  //
  var members = {
    "type": "Feature",
    "properties": {
      "name": "University of Mannheim",
    },
    "geometry": {
      "type": "Point",
      "coordinates": [8.466944, 49.488888]
    }
  };
  //
  L.geoJSON(members, {
    onEachFeature: onEachFeature
  }).addTo(map);
</script>
