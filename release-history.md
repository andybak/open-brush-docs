# Release History

List of changes in all major releases. For bleeding edge features see [alternate and experimental builds](alternate-and-experimental-builds/).

## v0.4.0: LIV, Snap and Guides

* Support for[@LIV](https://twitter.com/LIV)'s mixed reality on Oculus devices
* Color Jitter varies your strokes. Thanks @andybak!
* New 'plane' guide type + guide snapping, thanks @michael-g!

{% embed url="https://twitter.com/i/status/1425910471199240193" %}



## v0.3.0: Flying, Filming, and Fixes!

### New Features

#### Flying

* Fly tool, a new locomotion type. Reach out like your favourite caped hero and pull the trigger to fly around your sketch! Thanks to [@lachlansleight](https://github.com/lachlansleight)!

#### Filming

* Mixed Reality support on both Desktop and Quest.
  * The [LIV](https://www.liv.tv) SDK has been added, fixing a number of issues that were present when trying to use LIV with Tilt Brush. You will need to set your blend mode to `SDK: Normal (Masked FG Premultiplied)`. Thanks to [@SteffanDonal](https://github.com/SteffanDonal) and the LIV team!
  * Oculus [Mixed Reality Capture Tool](https://creator.oculus.com/mrc/) fixes. The plugin now receives the correct world scale. This also works with the [LIV for Quest](https://www.liv.tv/quest-on-pc) beta! Thanks to [@fabio914](https://github.com/fabio914). Check out Fabio's [Reality Mixer](https://apps.apple.com/us/app/reality-mixer/id1539307552) app ([GitHub](https://github.com/fabio914/RealityMixer)), allowing you to use MRC from your iOS devices!
* Capture Camera Paths! We decided to read our own README and re-enable video capture on camera paths now that we have general video support.

### Fixes

* Block Poly on Quest 1. Sadly Poly was causing crashes on Quest 1, and due to the short time that Poly will be available, we have chosen to block access. Poly downloads will still work on Quest 2 until the service shuts down. Once Icosa is up and running we'll make sure Quest 1 (and 2!) will have full support for it!
* Uploads to SketchFab are now tagged with Open Brush as the creation tool.
* [@mikeage](https://github.com/mikeage) has done some amazing work on our build pipeline. Any Pull Requests that get merged now automatically generate new builds, so if you feel adventurous, check out our [Bleeding Edge Releases](https://github.com/icosa-gallery/open-brush#bleeding-edge-releases). This also includes Linux builds!

## v0.2.0: Return of the Integrations

0.2.0 focuses on adding back a lot of the functionality that was removed from the original Tilt Brush codebase for release.

### Both Platforms:

* Re-added Sketchfab login
* Re-added Google/Poly login (note: uploading to Poly isn't possible as it uses proprietary Google code that wasn't released, sorry!)
* Re-added GIF recording (auto, 5s)

### Desktop extras:

* Re-added video recording
* Re-added FBX support
* Fixed USD support
* **We have also added basic Linux support, expect to see binaries soon!**

### Known issues:

* Camera preview disappears if you've disabled PostFX in your config
* Cannot record with camera paths

## v0.1.0: Initial Release

{% embed url="https://www.youtube.com/watch?v=5R4Vhkv_i2c" %}



##
