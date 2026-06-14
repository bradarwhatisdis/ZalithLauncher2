# OpenLauncher

> [!IMPORTANT]
> This is an **unofficial modified version** of [Zalith Launcher 2](https://github.com/ZalithLauncher/ZalithLauncher2).  
> This fork removes the account region restriction that prevents offline account usage outside of Greater China without a linked Microsoft account.

**OpenLauncher** is a fork of Zalith Launcher 2 — a launcher for **Android devices** tailored for [Minecraft: Java Edition](https://www.minecraft.net/). The project uses [PojavLauncher](https://github.com/PojavLauncherTeam/PojavLauncher/tree/v3_openjdk/app_pojavlauncher/src/main/jni) as its core launching engine and features a modern UI built with **Jetpack Compose** and **Material Design 3**.

## ✨ Changes from upstream

- **Removed account region restriction**: offline/local accounts can now be used from any region without requiring a Microsoft account
- All other features remain identical to upstream

## 📦 Build Instructions (For Developers)

### Requirements

* Android Studio **Bumblebee** or newer
* Android SDK:
  * **Minimum API level**: 26
  * **Target API level**: 35
* JDK 11

### Build Steps

```bash
git clone <your-fork-url>
# Open the project in Android Studio and build
```

## 📜 License

This project is licensed under the **[GPL-3.0 license](LICENSE)**.

### Additional Terms (Pursuant to Section 7 of the GPLv3 License)

1. When distributing a modified version of this program, you must reasonably modify the program's name or version number to distinguish it from the original version. (According to [GPLv3, 7(c)](https://github.com/ZalithLauncher/ZalithLauncher2/blob/969827b/LICENSE#L372-L374))
    - Modified versions **must not include the original program name "ZalithLauncher" or its abbreviation "ZL" in their name, nor use any name that is similar enough to cause confusion with the official name**.
    - All modified versions **must clearly indicate that they are "Unofficial Modified Versions" on the program's startup screen or main interface**.
    - The application name of the program can be modified in [gradle.properties](./ZalithLauncher/gradle.properties).

2. You must not remove the copyright notices displayed by the program. (According to [GPLv3, 7(b)](https://github.com/ZalithLauncher/ZalithLauncher2/blob/969827b/LICENSE#L368-L370))
