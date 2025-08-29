# Unreal Engine - MacOS

[![Unreal Engine Logo](unreal-engine.png)](https://www.unrealengine.com/)

This custom VR template takes the base VR template and makes the following changes:

* Thumbstick locomotion (Left controller thumbstick)
* Sprint (Click and hold left thumbstick while moving)
* Snap turn (Right thumbstick L + R)
* Custom Pawn collision
* Base teleport functionality is unchanged (Right thumbstick up)
* Variables for walk speed, sprint stamina, etc. can be changed in Blueprints

## How to use

* Clone into desired location
* Open `CustomVRTemplate` project in Unreal Engine
* Run `Platforms > Android > Package Project`
* When packaging completes successfully you can find the optimized build `.apk` file in the `Android_ASTC` directory
* To build your own project off this template simply copy the `/Config` and `/Content` folders and replace those directories in your new project


*When starting your new project make sure to navigate to `Edit > Project Settings` and in the Platforms tab click `Android` and resolve any issues in the `APK Packaging` and `Google Play Services` sections. Set the `Minimum SDK Version` to 29 and `Target SDK Version` to 32

*For light building issues on MacOS you will need to add `UnrealEditor` and `UnrealLightmass` to your firewall settings to allow connections or temporarily disable firewall

[Install SDKs with Android Studio Flamingo](https://developer.android.com/studio/releases/past-releases/as-flamingo-release-notes)

## Run a project on the Quest 3

* Install Meta Quest Developer Hub
* Connect Quest 3 to machine
* Allow connection from inside the Quest 3 headset
* In the Meta Quest Developer Hub navigate to the `Device Manager` tab and locate the `Apps` section. Use the `Add Build` button or drag the .apk file located in `Android_ASTC > YourProjectName-arm64.apk`

[Getting started with Meta Quest Developer Hub](https://developers.meta.com/horizon/documentation/unity/ts-mqdh-getting-started)
