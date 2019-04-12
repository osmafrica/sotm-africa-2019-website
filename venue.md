---
layout: post
title: Venue
permalink: /venue/
isStaticPost: true
image: city.jpg
---
![](../img/posts/grand-bassam.jpg)
Grand-Bassam is a town in south-eastern Ivory Coast, lying east of Abidjan.


<div id="map" class="map leaflet-container" style="height: 500px; position:relative;"></div>

<script>

var map = L.map('map').setView([5.212844,-3.743198 ], 10);

// create the tile layer with correct attribution:
L.tileLayer('https://maps.heigit.org/openmapsurfer/tiles/roads/webmercator/{z}/{x}/{y}.png', {
    attribution: 'Map data &copy; <a href="http://openstreetmap.org">OpenStreetMap</a> contributors, <a href="http://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>',
    maxZoom: 18
}).addTo(map);

//conference center
L.marker([5.228410, -3.757705], {icon: L.AwesomeMarkers.icon({icon: 'star', prefix: 'fa', markerColor: 'green'}) }).addTo(map);

//Airport
L.marker([5.261417, -3.925778], {icon: L.AwesomeMarkers.icon({icon: 'spinner', prefix: 'fa', markerColor: 'red'}) }).addTo(map);

//hotel
L.marker([5.194925, -3.737784], {icon: L.AwesomeMarkers.icon({icon: 'group', prefix: 'fa', markerColor: 'purple'}) }).addTo(map);


</script>
