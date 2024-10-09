# Unity Build Unused Assets Finder
C# scripts for the Unity game engine that identify used and unused assets in a build.

The scripts analyze the Unity build log to determine which assets are essential and which are not used.

A new window displays both used and unused assets, with the option to filter the assets by selecting a folder in the project view.

Tested with Unity 5.5.0f3 and Unity 2020.2.1f1.

## How to use

- Place the C# files in a special Unity [Editor](https://docs.unity3d.com/Manual/SpecialFolders.html) folder.
- After recompiling, a new menu item will appear under `Window > Build Info`. Click on this menu item.
- Build your application.
- In the new window, click the "Update Build Info" button to display the list of used and unused assets.
