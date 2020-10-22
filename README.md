# File node_texture.h for Blender OSL shaders

This file needs for properly works of some OSL shaders in Blender which use the directive

  #include "node_texture.h"

but in the last versions, this file is missed in the official Blender distributive.

To make such OSL shader works - copy this file to the directory:

  _path_to_blender_/_blender_version_/scripts/addons/cycles/shader/

for example
  
  c:/blender_2_91/2.91/scripts/addons/cycles/shader/
  
and refresh the OLS shader
