# Google-polymer-map
  This repository consists of reusable google map polymer element (../my-elements/map-element) which can load a map,detect user's location,adjust accuracy etc (made using Polymer 1.0 library using Google web-components )
## Install

  What things you need to install the software and how to install them

### Install bower
```
  npm install -g bower
```
### Install polymer-cli:
```
  bower install -g polymer-cli
```
## Setup

### Clone directly from Github
```
  git clone https://github.com/sindam/google-polymer-maps.git
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

# Short-description
 * The current location of the user is obtained using geo-location (see:./bower_components/geo-location.html)
 * marker automatically adjusts its position with changing geo-location
 * User can also adjust the position of marker by dragging it within the radius allowed
 * Dragging outside the radius places the marker back to its previous position
 
