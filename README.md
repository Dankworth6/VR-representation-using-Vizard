# VR-representation-using-Vizard
The provided code appears to be using the Vizard library, which is a platform for building and interacting with 3D virtual environments. The code sets up a scene with various avatars and defines functions to control their actions. Here's a breakdown of the code:

1. The `viz` module is imported, presumably referring to the Vizard library.

2. Some settings are configured for the visualization, such as enabling multisampling, initializing the visualization window, and setting the field of view (FOV) to 60 degrees.

3. The `piazza` object is created and added as a child to the scene. It seems to represent a 3D model of a piazza.

4. Collision detection is enabled in the scene using `viz.collision(viz.ON)`.

5. Two avatars, male and female, are added to the scene using the `viz.addAvatar()` function. They are positioned and oriented in the scene.

6. The state of the male and female avatars is set to 14, possibly indicating a specific animation or pose.

7. A list named `pigeons` is created to store instances of pigeon avatars.

8. A loop is executed ten times to create ten pigeon avatars. Each pigeon's position and orientation are randomly set within specific ranges.

9. Each pigeon avatar is added to the scene and positioned accordingly. Their state is set to 1, likely representing a specific animation or pose.

10. A `walkAvatars()` function is defined. When the 'w' key is pressed, it causes the male and female avatars to start walking towards specific positions.

11. An `ontimer2()` function is used to delay the walking action of the female avatar by 0.5 seconds.

12. A `pigeonsFeed()` function is defined. When the 'p' key is pressed, it triggers a feeding action for the pigeon avatars.

13. The feeding action involves a sequence of random movements, animations, and waiting periods. Each pigeon in the `pigeons` list is assigned this feeding action.

The provided code seems to set up a scene with avatars and defines keyboard-triggered actions for walking the male and female avatars and triggering a feeding action for the pigeon avatars.


Download vizard app from : https://www.worldviz.com/vizard-virtual-reality-software
For Tutorial and similar projects visit : https://www.youtube.com/watch?v=0cpfftwbFyg
