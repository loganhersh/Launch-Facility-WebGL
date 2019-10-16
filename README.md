# Launch-Facility-WebGL
Rendering of an ICBM launch facility with animation

This is an HTML/JavaScript application that renders a launch facility loosely based on the Minuteman III launch facility. 

There are some lighting and object controls as well as an animation. 
This program seems to work best on Firefox (tested on Firefox 69.0.2). 

It may be necessary to manually allow Firefox to load the textures from the local file system. 
To accomplish this: 
  + Type "about:config" in the address bar
  + To continue, the warning must be accepted
  + Type "security.fileuri" in the search bar at the top
  + Right click the preference labeled "security.fileuri.strict_origin_policy"
  + Select "Toggle" to change the value to false
  
** This setting should be reverted to true before returning to regular browsing activities.
  
The main file (p4.html) can be opened through an IDE like IntelliJ IDEA to avoid having to change settings in Firefox.
