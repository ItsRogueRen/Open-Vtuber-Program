# Open-Vtuber-Program

THIS PROJECT IS BEING SCRAPED, A BETTER VERSION USING THE GODOT GAME ENGINE IS BEING MADE CALLED `OpenSeeFace-GD`
https://github.com/you-win/openseeface-gd
THE CURRENT VERSION WILL REMAIN UP IF ANYONE WISHES TO FORK AND CONTINUE IT

An open-source Vtuber application for Linux, Windows, and MacOS

This program is current in very early development and merely a proof of concept at the moment. Included is the Unity project and a build for Linux x86_64

There are things still needed to improve this project! If you want to help, I'm looking for the following:
- A way to build a MacOS version without an Apple device
- A way to improve eye tracking (OpenSeeFace makes eyes closed when not looking directly at the camera)
- Any custom C# code you think will help improve the application!

I'm currently taking C# classes to write some code that will allow uploading your own model to the built application, but if someone has already found a way to do this feel free to save me the time!

HOW TO EDIT THE MODEL

To edit the model with your own, your model must be a vrm file and you need to have the UniVRM plugin in Unity.
- Open the project in Unity
- import your model via UniVRM
- Make a duplicate of your head, and in the heiarchy (the list of things in the scene) move the duplicate head to the top. Rename it something along the lines of IK-container
- Copy the components from the included container piece to your head duplicate and then delete the original container.
- Copy components from my model to the same locations on your model, and then delete my model
- Build the game from the menu for your OS (Linux, Windows, or MacOS)

OPEN VTUBER PROGRAM CURRENTLY USES:
- FastIK/Formerly SimpleIK (Open Source) - https://github.com/ditzel/SimpleIK
- OpenSeeFace (Open Source) - https://github.com/emilianavt/OpenSeeFace
- Unity (Closed source, but source code is readable) - https://github.com/Unity-Technologies/UnityCsReference
- COMING SOON uLipSync (Open Source) - https://github.com/hecomi/uLipSync

MENUS ARE CURRENTLY BEING WORKED ON
