---
layout: post
title: 3D movie - Computer Vision in daily life
---

Yesterday, I went to the cinema with my wife and my son. It is a 3D movie. It is not the first time for me to watch 3D movie, and I have been told the principle of 3D movie before, however, I havenot analyze it in detail and donnot undertand it well.

However, it changes this time.

When I put the 3D glasses on my glasses and see the 3D scenes, I understand that depth estimation is the key. And the disparity of left eye and right eye is used. Two cameras are used to record, and the videos are overlayed. This is why it looks blur without the 3D glasses. For dispairty algorithm, we generated blurred image by overlaying the ground truth image.

Then what is the magic behind the 3D glass? It also appear in our under-display-camera task, which is polarizing film. With different polarizing film, our left eyes can only see the scene of left camera, and right eyes can only see the scene of right camera.

I am so glad that I becomes clear about the principle of 3D movie at once, and the root reason is I have a better understanding of computer vision in the past year. When water flows, a channel is formed.

However, I still have something to be verified next time or in future:
- What will happen if I hold the 3D glasses upside down?
- What will happen If I close one eye?
- Is it helpful for de-blur algorithm?
