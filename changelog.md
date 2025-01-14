# ReTiCo changelog

## [2019.11.17](https://github.com/Vinc3r/ReTiCo/releases/tag/v2019.11.17)

Please search for "nothing-is-3D" in your addons list, if exists, delete it before installation.

- addon name is now **ReTiCo** for **Re**al **Ti**me **Co**mpanion
- versionning now use date (more convenient)
- object names can be put in OS clipboard
- orm, normal & emit textures nodes can now be activated as well as albedo (useful when in viewport shading solid-texture)
- ability to names material using object names and material id with *objName*.*id*.000 pattern
- report objects without materials and/or object with empty material indexes
- create an uv chan when using "Activate" button when it doesn't exists
- create an uv1 chan when using "Box mapping" button when it doesn't exists  
- fixed: emissive texture node no longer set as linear but sRGB
- fixed: Box mapping in Edit mode only applied on selected faces

## [v1.2.1](https://github.com/Vinc3r/BlenderScripts/releases/tag/v1.2.1)

- the stats/polycount part is [now an independant addon](https://github.com/Vinc3r/Polycount)

## [v1.2.0](https://github.com/Vinc3r/BlenderScripts/releases/tag/v1.2.0)

### Misc

- converted for Blender 2.8

### glTF workflow

- mute by texture type
- fix materials to match glTF norm

### Materials

- backface culling on/off
- select active texture node type (for viewport devlook mode)

### Meshes

- copy object name to mesh
- mass-overwrite autosmooth

### UVs

- do a box mapping but using MagicUV algorythm (much efficient than default one)
- report meshes without UVs


## [v1.0.0](https://github.com/Vinc3r/BlenderScripts/releases/tag/v1.0.0)

*25 november 2018* - *tested on Blender 2.79*

### Misc

- add-on is now a multi-file add-on (make future development easier)

### Meshes

- *Rename channels UV* now rename all UVs, not only UV1 & 2 (but still keep the default name UVMap for UV1 for convenience)

### Stats

- stats panel are now in Properties > Scene

## [v0.2.1](https://github.com/Vinc3r/BlenderScripts/releases/tag/v0.2.1)

*18 March 2018* - *tested on Blender 2.79*

### Stats

- avoid console error when no object is selected

## [v0.2.0](https://github.com/Vinc3r/BlenderScripts/releases/tag/v0.2.0)

*18 March 2018*

### Misc

- fix some bugs when selecting UV2 which doesn't exist
- stats panel: clicking on the object name make it the active one

### Blender Render

- add *diffuse/lightmap to texface* functionnality
- add *set spec to black*

## v0.0.2

*07 June 2017*

- show total stats

## v0.0.1

*06 June 2017*

- adding mesh selection stats (verts & tri)



