# pluginsPath

Search gizmo path using keywords or from selected node.

> Requirements: Nuke 12 or later

<br />

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
s.addCommand('Plugins Path'，'pluginsPath.PluginsPath().showModal()')
```

### Method 2: ( Highly recommended :exclamation: :exclamation: :exclamation: )

You can also put the code for pluginsPath.py in [`W_hotbox`](https://www.nukepedia.com/python/ui/w_hotbox), it's so convenient.


<img src="/images/W_hotbox_pluginsPath.png">

<img src="/images/W_hotbox_pluginsPath_2.png">
