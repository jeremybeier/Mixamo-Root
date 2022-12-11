# Mixamo Root
The majority of the funcitonality was implemented by Johngoss725's original contributions,
which were published under a Creative Commons 1.0 Universal License (CC0-1.0) located at:
<https://github.com/Johngoss725/Mixamo-To-Godot>.

I have simply reworked some of the functions to be less error prone, and to work better inside an addon.


This is a Blender 2.8+ script for importing mixamo Models and adding root bones to it.
This has only been tested with importing fbx files and exporting to a collection for godot 4
This may be compatible with other versions or engines,
 
This addon does the following things 
1) Imports the mixamo animations from the folder you specify.
2) Adds a root motion bone to the skeleton and keyframes
3) [Optionally] Renames the armature to remove the prefix.



How to use:
Install and enable the addon by downloading this repo as a zip file and directly importing it from the preferences menu.
Once activate a 'Mixamo Root' panel should be visible in the mixamo tab. Specify the folder with your mixamo animations
and import them into the file by pressing 'Import Animations'

The file can also be run as a script under the blender scripting console as long as you replace the path parameter in the
main function with your animation library path.
