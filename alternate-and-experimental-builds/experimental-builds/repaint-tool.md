# Repaint Tool and Improved Jitter

#### Status: Usable

## Download

* [Oculus Quest](https://nightly.link/IxxyXR/open-brush/workflows/build/features%2Fcolor-jitter/Oculus%20Quest%20Experimental.zip)
* [Oculus PC VR](https://nightly.link/IxxyXR/open-brush/workflows/build/features%2Fcolor-jitter/Windows%20Rift%20Experimental.zip) (Rift, Quest via Link cable...)
* [SteamVR ](https://nightly.link/IxxyXR/open-brush/workflows/build/features%2Fcolor-jitter/Windows%20SteamVR%20Experimental.zip) (Vive, Index, Reverb...)
* [Other Builds](https://nightly.link/IxxyXR/open-brush/workflows/build/features%2Fcolor-jitter) (Non-VR, Linux, Mac...)

**Alternatively:**

* [All features in one](all-features-in-one.md) (Grab a build that has all current features combined into one build)

### What does it do?

It expands on the existing Recolor tool which is now renamed to "Repaint". The following features can be used individually or in any combination:

#### Recolor

Same as before (but see the "jitter" feature below which adds new functionality to Recolo)

#### Rebrush

Similar to "Recolor" except it repaints existings strokes with a different brush. This is the same as the"Rebrush" tool in previous experimental builds. That feature is now part of this Repaint Tool)&#x20;

#### Resize

Change the brush size of existing strokes.

#### Jitter

When this option is turned on, recolor and resize will add random variations based on your current Jitter settings.

### Jitter Improvements

In addition to the Repaint Tool, this build adds some new features to the existing "Color Jitter" settings on the Color picker (the Dice icon near the bottom)

#### Jitter Brush Size

This slider controls how much the stroke size varies from stroke to stroke. All the way to the left behaves normally. As you move the slider more to the right, each stroke will have more randomness applied to it's stroke size.

#### Jitter Positions

![](<../../.gitbook/assets/image (12) (1).png>)

This slider controls how much randomness is applied to each point on a brush stroke. . All the way to the left behaves normally. As you move the slider more to the right, each point of the stroke will be randomly shifted from it's usual position. At higher settings and with some brushes this will cause the brush stroke to actually split and form multiple small strokes.

### Things to try

1. Try a high setting for "Jitter positions" and press the trigger to draw but don't move your hand. You'll get a small spherical "squiggle" that can be very interesting with some brushes.
2. Draw something regular with the Hull brush and make copies of it. Then use the "Repaint Tool" with a low setting for "Jitter positions" to add random variation to each copy
3. Position jitter can cause strokes to break into many small strokes. This depends on the brush you use and amount of jitter. Try really low jitter settings, try smaller brush sizes and try different brush types such as tube brushes (they tend not to break up as much)

### What's it good for?

Modifying parts of existing sketches. Adding random variation after you've already painted something. Trying out different brushes and reusing parts of a sketch with different properties. (try duplicating some strokes and then repainting the duplicate)

### How do I install it?

Download a build for your headset from the link above and unzip it. You can run the Windows exe directly. To install the Quest apk use SideQuest: [https://uploadvr.com/sideloading-quest-how-to/](https://uploadvr.com/sideloading-quest-how-to/)

### How do I use it?

The Recolor button on the Tools Panel has been replaced with "Repaint". When you select it, a side panel appears with 4 toggle buttons: Recolor, Resize, Rebrush and Jitter.

Any combination of these 4 options can be selected at any time. If you choose "jitter" then set your chosen amount of jitter using the button with the dice icon at the bottom of the Color Picker Panel

### Known Issues

1. You have to keep switching back to the Repaint tool whenever you choose a new brush. Rebrush didn't work this way but if we copy how rebrush worked then it would make it harder to change brush size for the "Resize" feature.

## How do I get help

Come over to the [Open Brush Discord](https://discord.com/invite/fS69VdFXpk) and chat to me ( @andybak#5425 ). I'm on UK time (currently UTC+1) but I check in fairly regularly.

### Can I see it in action?

{% embed url="https://youtu.be/mScGKQke4QA" %}

![Hull brush drawn with the Polyhedra tool with color and position jitter added](<../../.gitbook/assets/image (11).png>)
