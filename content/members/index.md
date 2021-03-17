+++
title = "Members"
+++

# Members

## Steering Group *&* Administration

<div class="mx-lg-negative my-4">
  {{ members(data_path="content/members/steering.toml") }}
</div>

## Local nodes

The GRN is primarily made up of local initiatives and stakeholders throughout Germany.

<link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css" integrity="sha512-xodZBNTC5n17Xt2atTPuE1HxjVMSvLVW9ocqUKLsCC5CXdbqCmblAshOMAS6/keqq/sMZMZ19scR4PsZChSR7A==" crossorigin=""/>
<script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js" integrity="sha512-XQoYMqMTK8LvdxXYG3nZ448hOEQiglfqkJs1NOQV44cWnUrBc8PkAOcXy20w0vlaXaVUearIOBhiXZ5V3ynxwA==" crossorigin=""></script>

<div id="map" class="mx-lg-negative my-4" style="height: 750px"></div>
{{ members_map() }}
