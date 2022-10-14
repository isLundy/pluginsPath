# pluginsPath

Search gizmo path using keywords or from selected node.

Requirements:

- Nuke 11 or later

## Installation example

### Method 1:

`init.py`

```python
nuke.pluginAddPath('./PythonScripts/pluginsPath')
```

`menu.py`

```python
import nuke
import pluginsPath

s = nuke.menu("Nuke").addMenu("PythonScripts")
s.addCommand('pluginsPath'，'pluginsPath')
```

### method 2: (Highly recommended)

You can also put the code in `W_hotbox`, it's so convenient.


<img src="/images/W_hotbox_pluginsPath.png">

<img src="/images/W_hotbox_pluginsPath_2.png">
