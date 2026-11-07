# AR Artifact Tracker: Map of Infinity
An interactive Augmented Reality experience developed using HTML, A-Frame, and AR.js. This project transforms a standard AR.js Hiro marker into a localized heads-up display tracking scattered pieces of the Map of Infinity.

Key Features:

Marker Tracking: Renders a multi-object 3D scene when a Hiro marker is detected by the device camera.

Dynamic UI Banner: Includes a live DOM overlay banner that updates its text and background color based on marker visibility events (markerFound and markerLost).

Custom Interactivity: Features custom A-Frame JavaScript components allowing users to tap 3D objects to trigger state changes (color cycling and size scaling).

Animations: Utilizes A-Frame animation components for continuous rotation and positional looping on primitive shapes.

Custom 3D Models: Integrates an external .glb 3D model into the marker scene.

Technologies Used:

HTML5 / CSS3

JavaScript

A-Frame (WebVR/WebXR framework)

AR.js (Lightweight WebAR tracking)
