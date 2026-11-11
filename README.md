## 3D Billiard Ball Pre-Collision Visualization

This application displays a 3D visualization of a cue ball and an object ball
on a "table" (just a flat plane with no pockets) before they actually collide.
It lets you explore the geometry you're faced with in a real game after you've
picked an object ball and a pocket (i.e., direction), but before you actually
make the shot.

There's absolutely no physics involved in this application. However, I believe
it gives you a good way to look at the pre-collision geometry using adjustable
cameras, billiard balls that aren't always opaque, and control over the display
of things like the aim line, contact line, pocket line, contact caps, and ghost
ball.

### Running the Application

You can run the application directly in your browser using GitHub Pages:

    https://rich-drechsler.github.io/shotview/shotview.html

You can also clone this repository or just download `shotview.html` and open
it locally in almost any modern web browser (an internet connection is still
needed because your browser has to download the Three.js 3D library).

For the best results, use a desktop or laptop computer with a mouse that has a
scroll wheel (a Bluetooth mouse connected to an iPad can also be useful). Full
instructions for all of the controls and visual aids are available via the
**Help** button at the bottom of the application window.

### History

This application is based on a primitive Java 3D Yoix script that I wrote in
2012 and abandoned for more than a decade. In late May 2026, I handed that old
script to Google Gemini 3.5 Flash and guided it as we built an HTML, JavaScript,
and Three.js version that ran in a browser.

That first browser version worked reasonably well, but the source code was messy
and hard to modify. Version 1.0 (November 2026) is a complete cleanup and rewrite
developed in collaboration with Google Gemini 4 Argon.
