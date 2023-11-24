# ChatAvatar_Plugin_for_Unity
Reposity of ChatAvatar Plugin for Unity

## How to install

1. Right click in your Project folder, then click Import Package - Custom Package

2. in the file dialog, select the .unitypackage file and import all files into your project.

## How to use

1. In your project, you can open the plugin widget window by clicking Window - Deemos Import Tool.

## How to import your package

1. In the widget window, please click 'Import', then select the .zip file you have downloaded from ChatAvatar website (https://hyperhuman.deemos.com) in the file dialog, then click Confirm.

2. After the plugin has checked if your package is a valid ChatAvatar asset package, you will see the Setting page and can select the resolution of texture and render pipeline of your current project. In default the proper RP will be selected. Then click Next.

3. Next you can choose the features you want in your mesh. You can choose multiple options of them ranging from rigged body to back head textures. Please notice that we do not support back head material slot for obj model. 

4. Next you can choose whether you want basic facial controls or/and body controls. You can select both at the same time.

5. Click Confirm, then the plugin will import all assets needed into your project and do the necessary setup on the model. You can find them later in ChatAvatar folder. The window will then close and you will see your mesh in the scene. Please enjoy!

## Features in Demo Scene

1. View distance: we provide 3 different view distance preset -- Close Up, Mid Shot and Full Shot, all 3 view preset is animated to rotate around the character.

2. Facial control: we support 2 ways to control the face of the character lively: Livelink and Custom. you can see the tutorial for Livelink in the following section. For Custom we provide a Rig Panel which can be toggled on, with Rig Panel you can control the face with the sticks.

3. Light preset: we offer 7 different lighting preset for you to view different presentation under the light condition.

## How to use facial control

1. We use "Unity Live Capture" package and "Unity Face Capture" app in AppStore for real-time facial control, please kindly refer to the "Setup" section of this website (https://docs.unity3d.com/Packages/com.unity.live-capture@1.1/manual/index.html) to link your capture device to the project.

## Notes

1. The materials your mesh uses is a copy of parent materials, which means you can adjust the material's detail parameters at will and easily to enhance the mesh's presentation in your scene.

2. If you encounter any problem during use, please feel free to issue in this repo. We will assist in resolving the issue at the earliest opportunity.

3. Our developing environment is: Unity 2021.3.20f1c1 in Win64. It should be upward compatible with the newer version of the editor, but we are not sure. We also suggest that you use an editor whose version is not lower than our development version for development.

## Please Enjoy!
