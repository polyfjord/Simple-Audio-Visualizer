# Simple Audio Visualizer

A Blender Extension that creates a simple audio visualizer by generating animated cubes, or by animating your own objects to the spectrum of a selected audio file.

Note: This is a Blender Extension, and it is recommended to install through Blender's [extensions platform.](https://extensions.blender.org/add-ons/simple-audio-visualizer/)

### How to Use:
The add-on is located in the **Graph Editor** sidebar panel.

**To Generate New Visualizer Objects:**

1.  Open the Graph Editor in Blender.
2.  In the sidebar, find the "Simple Audio Visualizer" panel.
3.  Choose an **Audio File** by specifying the path to your desired audio file.
4.  (Optional) Adjust the **Audio Visualizer Multiplier** to control the intensity of the animation.
5.  (Optional) Set the **Number of cubes** to determine how many objects will represent the audio spectrum.
6.  (Optional) Enable **Mirror Mode** to create a mirrored visual effect.
7.  Click the **Create Visualizer** button to generate the objects and add the animation.

**To Animate Your Selected Objects:**

1.  In the 3D Viewport, select the object(s) you wish to animate.
2.  Choose an **Audio File** and set the **Multiplier** intensity.
3.  Select the transform channels (**Location, Rotation, Scale**) and axes (**X, Y, Z**) you want to animate.
4.  (Optional) Enable **Additive** mode to add the animation on top of existing keyframes instead of replacing them.
5.  Click the **Visualize Selected Objects** button. The audio spectrum will be distributed across your selected objects (sorted alphabetically) and animated according to your settings.

This extension is based on a script originally created by GitHub user soerenmetje: https://github.com/soerenmetje/Blender-Music-Visualisation-Python-Script
