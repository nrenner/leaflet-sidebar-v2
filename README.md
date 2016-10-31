# leaflet-sidebar-v2

A responsive sidebar _just_ for [Leaflet](http://leafletjs.com/). A fork of [sidebar-v2](http://turbo87.github.io/sidebar-v2) that only contains the necessary ingredients for use in Leaflet.

![Demo](doc/sidebar-v2.gif)

## [Leaflet](http://leafletjs.com/)

![Sidebar collapsed](doc/leaflet-1.png) ![Sidebar extended](doc/leaflet-2.png)

## Why the Fork?
I wanted to `npm install` sidebar-v2 for a Leaflet project which required the `main` and `style` fields in [`package.json`](package.json). This fork removes the Google Maps and OpenLayers files since I don't need them in the npm package.

## License

leaflet-sidebar-v2 is free software, and may be redistributed under the [MIT license](LICENSE).
