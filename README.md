# MapTiler Basic

A simple GL JS basemap style showcasing OpenStreetMap data. It is using the vector tile schema of [OpenMapTiles](https://github.com/openmaptiles/openmaptiles).

**[:globe_with_meridians: Explore this map](https://openmaptiles.github.io/maptiler-basic-gl-style/)**

[![MapTiler Basic](https://openmaptiles.org/img/styles/basic.jpg)](https://openmaptiles.github.io/maptiler-basic-gl-style/)

## Use this map in your website

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Display a map</title>
  <script src="https://cdn.maptiler.com/maptiler-sdk-js/v4.0.2/maptiler-sdk.umd.min.js"></script>
  <link href="https://cdn.maptiler.com/maptiler-sdk-js/v4.0.2/maptiler-sdk.css" rel="stylesheet" />
  <style>
    body { margin: 0; padding: 0; }
    #map { position: absolute; top: 0; bottom: 0; width: 100%; }
  </style>
</head>
<body>
  <div id="map"></div>
  <script>
      maptilersdk.config.apiKey = 'Get your own API key at https://www.maptiler.com/cloud/';
      const map = new maptilersdk.Map({
        container: 'map',
        style: "basic", // ev. "https://www.yourdomain.com/styles/basic.json"
      });
  </script>
</body>
</html>

```

> [!TIP]
> This style has a high-quality alternative called [Base map style](https://www.maptiler.com/maps/#style=base-v4&lang=auto) for lightweight basemap available in dark/light mode, multi-lingual, government compliant, easy to customize. Try it! 


## Edit design of this map style

Use the map design editor in MapTiler Cloud to view and adjust this map. Open the designer and upload style from this repository or host from various styles available on the platform.

[Try style editor](https://cloud.maptiler.com/maps/editor?map=basic)
