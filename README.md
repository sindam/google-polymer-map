# Polymer-GoogleMaps

Consists of reusable google map polymer element (../my-elements/map-element) which can load a map,detect user's location,adjust accuracy etc.


# Install
What things you need to install the software and how to install them

# Install bower
```
npm install -g bower
```
# Install polymer-cli:
```
bower install -g polymer-cli
```
# Setup

## Clone directly from Github
```
git clone https://github.com/mani0108/polymer-GoogleMaps
```
### Running the server 
```
- Go to the folder polymer-GoogleMaps
- Make sure you have all the dependencies available
```

```
polymer serve
```
It creates a local host server with an available port

# Brief-Description

- The current location of the user is obtained using 'geo-location' (see : ../bower_components/geo-location)
- The marker automatically adjusts its position with changing geo-location
- User can also adjust the position of marker by dragging it within the radius allowed
- Dragging outside the radius places the marker back to its previous position
