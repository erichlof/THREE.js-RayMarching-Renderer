# THREE.js-PathTracing-Renderer
Real-time PathTracing with Monte Carlo integration and progressive rendering, all on top of the Three.js WebGL framework.
Click for demo -> http://erichlof.github.io/THREE.js-PathTracing-Renderer/ThreeJS_PathTracing_Renderer.html

<h4>TODO:</h4>
* Add random sampling from the unit hemisphere oriented around the normal of the ray|object hit point.  Do this every frame.
* Once the above is complete, we can have Monte Carlo integration by adding these samples together and taking the average.
* Add simple FPS-style flying controls for desktop and mobile.
* Instead of setting up meshes with Phong Material, use Three.js's new Standard Material (physically-based parameters).
* Allow automatic adjustable resolution when the camera moves.  Lower resolution while moving, higher resolution while still - so that the image converges to a high-quality render while static.  

This project is in the early Alpha stage. More features, examples, coming soon...
