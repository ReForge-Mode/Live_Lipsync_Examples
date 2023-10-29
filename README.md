# LIVE Runtime Lipsync with uLipSync
uLipSync is the most underrated lipsync plugin EVER. I'm trying to change that right now! In this tutorial video, I'm going to show you how to use uLipSync plugin by hecomi.

This project contains both 3D and URP project already installed with UniVRM and URP Shader. This project is made with Unity version 2022.2.17f1. Earlier version of Unity might not work.

Huge credit to these guys who made this possible!
- uLipSync v3.0.2 by hecomi: https://github.com/hecomi/uLipSync
- UniVRM v0.108.0 plugin: https://github.com/vrm-c/UniVRM


# Tutorial Video
Here are some explanations how to use or create this project in a video form:

[![FREE Lipsync plugin that EVERYONE should use!](https://github.com/FFaUniHan/Live_Lipsync_Examples/blob/main/Video.jpg)](https://www.youtube.com/watch?v=aaks0yg9ZyU "FREE Lipsync plugin that EVERYONE should use)")


# Instructions
Once you download and extract the zip file or clone the project to your Git application, open it in Unity Hub. This project uses Unity version 2022.2.17f1, earlier versions of Unity might not work, and later versions might break some of the scripts. To download a specific version of Unity, go to this website https://unity3d.com/get-unity/download/archive.

After you download and install the Unity version, you can add this version of Unity back to Unity Hub and open it. Once the project is opened, don't forget to double click the Scene file in the Project Window.


## Adding Mouth Blendshapes
In the tutorial video, I mentioned adding in extra mouth blendshapes. You can either do this manually with NEBPro or NEBLite. You're looking to copy these three mouth blendshapes from Extra Mouth Blendshapes.vrm file:

<img src="https://github.com/FFaUniHan/Live_Lipsync_Examples/blob/main/NewBlendshapes.png" width=100% height=100%>

You can get either of them on my Ko-Fi page:
- NEBLite (Free): https://ko-fi.com/s/ad2b08fa67
- NEBPro (2.99$): https://ko-fi.com/s/c47de71369

I've made a separate tutorial for NEBLite and NEBPro here: 

[![FREE HanaTool Alternative!](https://github.com/FFaUniHan/Live_Lipsync_Examples/blob/main/Video2.jpg)](https://youtu.be/ZQh7BQ_qQYE "FREE HanaTool Alternative!)")


## Switching Between Models
Once you have set up the Profile like in the video, you don't need to set it up again for a new character model. You can just drag the profile into your uLipSync component.

Of course, you still have to follow the initial steps in the new character model as well, like adding Lipsync child gameobject, Audio Source component, uLipSync component, and uLipSyncBlendshape component. But you can keep reusing the Profile for every character.

<img src="https://github.com/FFaUniHan/Live_Lipsync_Examples/blob/main/Screenshot1.png" width=100% height=100%>


# Support me on Ko-Fi or Patreon

<img src="https://github.com/FFaUniHan/Live_Lipsync_Examples/blob/main/LogoPatreonKofi.png" width=50% height=50%>

If this tutorial helps you, consider supporting me on these platforms. I would like to do more tutorials in the future!
- Patreon: https://www.patreon.com/ReForgeMode
- Ko-Fi: https://ko-fi.com/reforgemode


# Got any questions?

<img src="https://github.com/FFaUniHan/Live_Lipsync_Examples/blob/main/LogoDiscord.png" width=30% height=30%>

Encounter any weird bugs or problems? Let's talk about it on our Discord server forums:
- Discord Server https://discord.com/invite/aDMGjpFeBX
