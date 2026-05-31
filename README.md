# Three.js-PointerLockControls-mobile
Three.js PointerLockControls for mobile / touch devices

This is a modified PointerLockControls.js for Three.js
It allows mobile devices to have first person controls like desktop devices with PointerLockControls

Install :
Replace PointerLockControls.js in jsm/controls/

WARNING :
For now it is FORCED to act as mobile devices. I haven’t decided the best way to determine if a device is a touch device or not.
You can use the current method (available for Iphone, Ipad, Ipod, Android) by changing line 8 bool to false : 
````js
mobile = false;
````

Working in progress : 
- Get if device is a touch device or not
- adapt normal pointerSpeed for touchscreens
