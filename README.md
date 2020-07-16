# Project-Absolam
A Set of Dungeon Crawler Tools and Utilities for GZDoom

## Primary Features
- Customizable 3rd Person Camera
- Advanced reticule targetting system
- Managed extensibility through modularity

### [The Camera](https://github.com/Saican/Project-Absolam/tree/pa-cam "### The Camera")
The core module of Project Absolam.  Geared toward a top-down perspective, the camera height and pitch can be tweaked both by the developer and player.  Other options include the ability to swap back to first-person and sync the camera pitch and angle to the players.

### The Crosshair
Again with a top-down perspective in mind, the crosshair features targetting logic that can be tweaked to the preffered play style of the player.  The target search distance and various behavior settings are available.

### Extensions
The crosshair is itself an extension, a proof of concept.  Project Absolam will function perfectly well without it.  Using polymorphism and event handlers, some information may be sent to the "Control Handler", a master event handler, which can disseminate and share that information with the player, who will then spawn whatever objects the extension defines.
