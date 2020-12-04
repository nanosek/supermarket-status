# Is is busy? 
This is a prototype of an OpenStreetmap Mashup to show the current "waiting queue" length

### How does it work?

Almost everything runs in your browser via JavaScript, there is no dedicated server that belongs to this mashup.
Three external servers are being used (their public APIs are being queried by your browser):
- OpenStreetMap to get the map tiles (the map background)
- wss://mqtt.eclipse.org to fetch the reported status that others have published
- overpass-api.de/api/interpreter to get the actual data where the elements that you are interested are located
 

[Map with Leaflet](./map-leaflet.html)

