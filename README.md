# Blender 4x ArmorPaint Livelink

This addon is the current implementation of live link for [ArmorPaint](http://www.armorpaint.org) inside of Blender 4.x

## Getting Started

### Prerequisites

Download latest version of Blender (v. 4.0 minimum) and ArmorPaint V0.8.

### Installing

1. Clone the repository  
2. Inside of Blender, *Edit > Preferences... > Add-ons (Tab) > install..* the armorpaint_livelink.py file  
3. Turn on the addon  
4. Add the ArmorPaint executable path in the "ArmorPaint Executable" field  
5. In the 3D View, open the panel side (*N* shortcut) and locate the project directory  (folder where your Arm file and textures will be saved)  
6. Select your object  (he needs to be unwrapped) and click on the "Open in ArmorPaint" to edit it inside of ArmorPaint  (* Optionnal:You can use a custom arm name instead of the object name - example: Use "MyBeautifullCube.arm" for the "Cube" object instead of "Cube.arm"*)  
7. When the texturing process is done, export your textures to a subdirectory called "exports" (* Optionnal: You can also use a custom directory for your textures - example: "/highdefTextures/"*)

## Authors

* **[PiloeGAO](https://github.com/PiloeGAO)** - *Initial work*
* **[Spirou4D](https://github.com/Spirou4D)** - *Code fix*
* **[tobiasBora](https://github.com/tobiasBora)** - *Temporary directory fix*
* **[kcalvinroy](https://github.com/kcalvinroy)** - *Switch fix from previous Blender Obj export to new Blender 4.x export*
## License

This project is licensed under the GNU GPLv3 License - see the [LICENSE.md](LICENSE) file for details.
