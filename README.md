# NodeConnectorGodot
Plugin for the Godot editor that provides a convenient way to connect a bunch of UI elements to a script.

For each of the selected nodes it adds a line to your scene's script like:

`onready var button = find_node("Button");`

Will also add a signal handle for Buttons and TextEdit nodes for their "pressed" and "text_changed" events.

Demo:
![Gif Demo](demo.gif)


Note: There is one annoyance, that when modifying an existing script Godot doesn't pickup the changes until you unfocus Godot and reopen it.
