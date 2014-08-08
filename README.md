J3DIO
======
Java 3D Input Output, or J3DIO(say "jedio"), is a file IO system for 3D models.  


Download
--------
Click [here][1] to download the latest version of J3DIO for Java 7

What's new
----------
 * Fixed `.mtl` loader
 * Creted `Definable`
 * Changed how colors are stored in `MtlModel`s

File type support
-----------------
| File type | Import  | Export  | Render  |
|-----------|---------|---------|---------|
|   .obj    | Yes     | Yes     | Yes     |
|   .mtl    | Yes     | Yes     | No      |
|   .raw    | Yes     | Yes     | Yes     |
|   .ply    | Partial | Partial | No      |
|   .stl    | Partial | Partial | Partial |
|   .dae    | No      | No      | No      |
|   .fbx    | No      | No      | No      |

####`.obj` and `.mtl`####
**Import/Export:** Textures not supported  
**Render:** Materials not supported

####`.raw`####
**Import/Export:** Full support  
**Render:** Full support

####`.ply`####
**Import/Export:** Binary, Colors, and Textures not supported  
**Render:** Not supported

####`.stl`####
**Import/Export:** Colors not supported  
**Render:** Colors not supported

####`.fbx`####
**Import/Export:** N/A  
**Render:** N/A

####`.x`####
**Import/Export:** N/A  
**Render:** N/A

####`.dae`####
**Import/Export:** N/A  
**Render:** N/A

####`.ms3d`####
**Import/Export:** N/A  
**Render:** N/A

####`.3ds`####
**Import/Export:** N/A  
**Render:** N/A

 [1]: https://github.com/FracturedRetina/J3DIO/releases/download/v4.0-beta/jml_v4.0-beta_jre7.jar
