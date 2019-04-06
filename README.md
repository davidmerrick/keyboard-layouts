The Dvorak-no-modifiers layout is to get rid of an annoyance in IntelliJ where, during the commit dialogue flow,  an `alt` + `i` was 
interpreted both as a command and as a keyboard modifier, so a carat (`^`) would get appended to all my commit messages. Removing the modifiers
fixed this.

Using [Keyboard Pilot](http://tinybird.com/mac/keyboard-pilot.html), I set up profiles for IntelliJ to switch to my modified Dvorak layout, and all other times
switch back to standard Dvorak. 

# Installation

On macOS, drag the keyboard layout file into `/Library/Keyboard Layouts`. You'll need to authenticate to do this.
Restart the machine, and then open up the Keyboard preference pane. From there, add your new keyboard layout (it'll be found under `Other`).
From there, you'll be able to configure Keyboard Pilot to use your new layout.
