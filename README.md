# Plait

![Plait screenshot](images/plait.png "Plait screenshot")

Plait is a tool for visualizing and untangling the mess of gates that makes up GateBoy. It's not at all finished yet, but there's enough functionality to be useful. It's also quite fun to poke around in the graph and see how things like the pixel pipe are actually implemented, gate-wise. The pic above is the "pixel output" circuit that merges the background tile pixels with the sprite pixels, applies the color palettes, and sends the pixels to the LCD.

Plait **parses the GateBoy source code**, extracts all tagged (`/*#p08.ASUR*/`) lines, and converts the result to an editable graph. To make the level of complexity more manageable, Plait includes multiple editing features to help modularize and untangle the graph.
