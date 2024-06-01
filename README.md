# thane5-blender-keymap
My personal Blender (4.0.2) keymap that attempts to be intuitive for beginners and advanced users alike.

## How to install
### Option A: Install just the keymap
Go to preferences -> Keymap -> import and Import Blender_keymap_by_thane5.py.
### Option B: Install the userprefs.blend file 
This will let you keep the "preferences" section on top of new keymaps, which for some reason is missing when you install a keymap via the python file. Unfortunately, this replaces all of your other blender settings. Anyways, just move userprefs.blend into the same folder as the startup file (usually \AppData\Roaming\Blender Foundation\Blender\4.0\config)

## Features
### 1. Optimized for  QWERTZ keyboards
Qwertz users can now use Ctrl+Y for undo and Ctrl+X for redo. These keys are much easier to reach compared to using the Z key.

|Operator|Shortcut   |
| :------------ | :------------ |
|Undo|Ctrl+Y|
|Redo|Ctrl+X|
|Cut|Ctrl+Shift+X|

### 2. Navigation without modifier keys. 
Rotating, panning and zooming the 3d view requires no modifier key, as they are entirely mapped to the mouse.

|Operator|Shortcut   |
| :------------ | :------------ |
|Select|Left Mouse|
|Pan View|Middle Mouse|
|Rotate View|Right Mouse|

**Note: Since the context menu can no longer be used by the right mouse button, it has now been assigned to the W key in most places.**

### 3. Left-handed shortcuts. 
No need to take your right hand off the mouse to parent an object or to focus on an object. Some Shortcuts that prevoiously required a numpad are not more easily accessible.

|Operator|Shortcut   |
| :------------ | :------------ |
|Frame selected|F|
|Frame all|Shift+F|
|Local view|Alt+Q|
|Brush Radial Control|D|
|Subdivide Mesh|D|
|Pie Menu: Shading|V|
|Toggle Wireframe|Shift+V|
|Toggle Wireframe Overlay|Alt+W|
|Pie Menu: Pivot Point|Tilde Key (^)|
|Rip Vertices (Edit Mode)|Shift+R|

### 4. The "Connect" key
This keymap now combines several actions under the C key. In mesh/bone/curve mode it takes over what previously was the F key - connecting nodes, vertices and making new faces.

Alt+C now brings up the parent menu, Alt+Shift+C the unparent menu. Circle-select had to be moved to shift+C

|Operator|Shortcut   |
| :------------ | :------------ |
|Make Face (Edit Mode)|C|
|Join Objects (Object Mode)|C|
|Set parent (Object & Bone Edit Mode)|Alt C|
|Clear parent (Object & Bone Edit Mode)|Alt Shift C|
|Circle Select|Shift C|

