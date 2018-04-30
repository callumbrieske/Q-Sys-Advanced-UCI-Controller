# Q-Sys-Advanced-UCI-Controller
A plugin for the QSC Q-Sys platform to allow easy creation of advanced UCI's using multiple layers.

Intructions for use:

1. Fill the setup section with the details of the UCI & page you wish to control.
2. FIll in the layer names of the layers that you wish to control.
3. Optionally, give a group of controls a 'Radio Group' name if they are to operate as a radio group. Any name can be used, and you can create as many groups as required.
4. If any layers are to be 'sub layers', choose a parent layer. These layers will only be shown if the parent layer is on. Nested parents are also possible.
5. Select the desired transitions for in and out. When a parent layer is changed, the transitions will be inherited.
6. If layers are part of a radio group, it will be possible to select the 'Reset Group' option. This will reset the group to its first member when a parent is enabled.
7. A 'Logical Parent' can be created that doesnt have an associated layer by selecting the 'Logical Parent' button. These are useful as a master control to hide a radio group.
