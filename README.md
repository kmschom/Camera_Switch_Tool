A small script for quickly cycling through all perspective cameras and select orthographic cameras in the Maya viewport.

I was frustrated with the built-in systems for switching between difference camera views. 
I found them annoying and I would often hit the wrong button by accident and thus be taken off track trying to fix whatever I had just accidentally done.
Kitty Fung was one of my animation instructors and gave the class a small script to switch between perspective cameras.
I modified it so that I could add on any orthographic cameras I was using. 

This script can be added to any Maya shelf and, when clicked on, will cycle through all perspective cameras and some number of orthographic cameras.
Right now, to add orthographic cameras to the cycle, you must edit the script manually. You can do so by right-clicking on the script button in the shelf and selecting "Edit".
Then add any camera to the 'string $addtCameras[]' on line 7. Be sure to enclose the camera name in double quotation marks "". 

See a video demo here: https://youtu.be/EB8CezkSbOQ

Future features:
- Create a UI where users could select what cameras the button will cycle through, rather than requiring users to edit the code directly
- Have a series of buttons for each camera for the user to quickly switch to any camera, rather than cycling through all the cameras
