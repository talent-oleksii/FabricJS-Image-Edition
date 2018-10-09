# FabricJS Demo

FabricJS allows you to control each object in the canvas freely with JavaScript.

This demo currently adds two objects onto the canvas and the user can immediately manipulate the objects. You can rotate, scale, and move the objects. The "Shift Left" and "Shift Right" buttons moves the rectangle object. The "Sepia-fy" button adds a Sepia filter to the current active object. The "Rotate Current Object" button rotates the object 360&deg; and animates it. The bounce at the end of the rotation is due to the choice of easing, which there are many types provided in FabricJS.

### Usage

```
npm install http-server -g
```

Installs http-server globally, then you can navigate to your project path and type

```
http-server
```

Alternatively,

```
http-server [path] [options]
```

Now, you can visit http://localhost:8080 on your browser.
