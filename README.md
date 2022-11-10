# Mesh Resizer 0.1v
A program that sets the **size**, **rotation value**, and **pivot** of the **.obj** file.
It's a program made using Unity.
![enter image description here](https://drive.google.com/uc?id=1U63KvU8wtBAsbdeBbJaM9mCUpvkJpdr2)

## Program Features
The .obj file itself modifies the vertex value of the mesh to set the size, rotation value, and overall pivot position. 
UV mapping and image mapping will remain the same, and the output file will be applicable to **most programs** *(maybe)*.
ㅤ  
## How to download
On the current page, download from the Code button to the compressed file format via **Download Zip**, extract, and use the program.
ㅤ  
## How To Use
 - Run the program.
 - Press Load and use the file dialog that appears within Unity to find and select the obj file.
 - Modify the obj file as desired.
	 - A. Left-click and move: Rotate 
	 - B. Mouse Drag: Resize 
	 - C. Click the middle mouse button to move: move object (move pivot position)
 - Press Export to subtract the results to a file.
> **Note:**  Exporting creates a new file with the **suffix _resized** attached to the file at the location of the imported file **without the need to set a new path.**

> **Note:** The **size of the grid means one meter in a unity meter** (for example, if a person is two meters, it takes up two compartments)

ㅤ  
## Application example

> The large chair is set to appear 1 meter with the default scale of Vector.one (1,1,1) in Unity.

![enter image description here](https://drive.google.com/uc?id=1uR2ZJV-Lq8RLUFLhmIawyBd21O0TGRza)

> These changes are also fully implemented in 3ds Max.

![enter image description here](https://drive.google.com/uc?id=1vz0LRepQJGgpjDebLMGo34-4gGf9dmtE)
ㅤ  
## Reference
Allows you to use a file browser within Unity.
https://github.com/yasirkula/UnitySimpleFileBrowser
