### Unreal Engine - MacOS
![](https://dev.epicgames.com/community/api/documentation/image/bafbc878-8d43-4bdd-9964-85d6079d6811?resizing_type=fill&width=1920&height=335)

This custom VR template takes the base VR template and makes the following changes:

* Thumbstick locomotion (Left controller thumbstick)
* Sprint (Click and hold left thumbstick while moving)
* Snap turn (Right thumbstick L + R)
* Base teleport functionality is unchanged (Right thumbstick up)

**How to use**

* Clone into desired location
* Open `CustomVRTemplate` project in Unreal Engine
* Run `Platforms > Android > Package Project`
* When packaging completes successfully you can find the optimized build `.apk` file in the `Android_ASTC` directory
* To build your own project off this template simply copy the `/Config` and `/Content` folders and replace those directories in your new project

*For light building issues on MacOS you will need to add `UnrealEditor` and `UnrealLightmass` to your firewall settings to allow connections or temporarily disable firewall


[Getting started with Meta Quest Developer Hub](https://developers.meta.com/horizon/documentation/unity/ts-mqdh-getting-started)

**Run a project on the Quest 3**

* Install Meta Quest Developer Hub
* Connect Quest 3 to machine
* Allow connection from inside the Quest 3 headset
* In the Meta Quest Developer Hub navigate to the `Device Manager` tab and locate the `Apps` section. Use the `Add Build` button or drag the .apk file located in `Android_ASTC > YourProjectName-arm64.apk`