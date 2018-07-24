# leaflet-heatmap-radius [![NPM version][npm-image]][npm-url] [![NPM Downloads][npm-downloads-image]][npm-url]

A plugin for heatmap.js to add heatmaps to leaflet, with a fixed radius option (meters).

This is an enhanced version of
[leaflet-heatmap](https://www.patrick-wied.at/static/heatmapjs/example-heatmap-leaflet.html) which provides an
additional `radiusMeters` option, so you can have a heatmap with a concrete, known radius.

## example

```javascript
let heatmap = new HeatmapOverlay({
	fixedRadius: true, // enable use of meters instead of pixels
	radiusMeters: 100  // set the radius value in meters
});
```

## License
MIT License (MIT)

[npm-image]: https://badge.fury.io/js/leaflet-heatmap-radius.svg
[npm-url]: https://www.npmjs.com/package/leaflet-heatmap-radius
[npm-downloads-image]: https://img.shields.io/npm/dt/leaflet-heatmap-radius.svg