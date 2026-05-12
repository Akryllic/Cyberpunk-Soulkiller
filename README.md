#### Cyberpunk: Soulkiller

![](https://raw.githubusercontent.com/Akryllic/Cyberpunk-Soulkiller/main/Soulkiller.png)

<p align="center">
  <a href="https://github.com/Akryllic/Cyberpunk-Soulkiller/blob/main/CHANGELOG.md">Changelogs</a> |
  <a href="[https://www.nexusmods.com](https://www.nexusmods.com/cyberpunk2077/mods/29614)">Nexus</a> |
  <a href="https://discord.gg/GgkPMBMTrS">Discord</a>
</p>

#### Introduction

Soulkiller is a Wabbajack mod list featuring survival-focused modern gameplay and enhanced immersion systems. Built with cutting-edge graphics in mind.

If you're curious about the specific mods in the list, the full modlist can be viewed [here](https://loadorderlibrary.com/lists/cyberpunk-soulkiller-2).

### System Requirements

**DISCLAIMERS:**
- Cyberpunk-Soulkiller only supports Windows 10/11 operating systems.
- HDD and external SSD installs are absolutely not supported. A NVMe Gen 3 or Newer is mandatory for installation.
- Any remote PC / desktop services or apps are not supported.
- At least 16GB of RAM is required for optimal performance.
- 12GB+ of VRAM is strongly recommended for 1080p gameplay. Higher resolutions require more.
- 150~ GB of available disk space; downloads folder can be deleted after installation.

## Installation

**⚠ WARNINGS ⚠:**
- **Ensure your game is updated to the latest version before installation.**

### Pre-Installation

#### General Utilities

Before installing Cyberpunk-Soulkiller, please complete the following steps:

**.NET Framework**

.NET is a free, cross-platform, open-source developer platform for building many different types of applications. This is required for various mod tools to function properly.

[.NET 8.0 SDK - Windows x64 Installer](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)

[.NET 9.0 SDK - Windows x64 Installer](https://dotnet.microsoft.com/en-us/download/dotnet/9.0)

**Microsoft Visual C++ Redistributable**

The Visual C++ Redistributable installs Microsoft C and C++ (MSVC) runtime libraries. These libraries are required by many applications built using Microsoft C and C++ tools.

[Microsoft Visual C++ Redistributable for Visual Studio 2015, 2017, 2019, and 2022 - x86](https://aka.ms/vs/17/release/vc_redist.x86.exe)

[Microsoft Visual C++ Redistributable for Visual Studio 2015, 2017, 2019, and 2022 - x64](https://aka.ms/vs/17/release/vc_redist.x64.exe)

**RedMod**

RedMod is a free modding utility for Cyberpunk 2077 that needs to downloaded for full mod functionality and loading

[RedMod Steam Download](https://store.steampowered.com/app/2060310/Cyberpunk_2077_REDmod/)

#### Storage and Installation

**Important:** Do not install the game in `C:\Program Files` or `C:\Program Files (x86)` — this can cause permission issues.

If already installed there, reinstall to a different location such as `C:\Games` or `D:\Games\`. This prevents compatibility issues with mod managers and virtual file systems.

#### Antiviruses

Remove or disable any 3rd party antiviruses such as `Webroot` or `Bitdefender`. These programs can cause issues with your installation due to how mod managers' Virtual File Staging works.

To prevent the game from having trouble loading scripts, please, do the following:
Add the modlist folder to your antivirus exclusion list
Add the game executable to your antivirus exclusion list
Add the redmod executable to your antivirus exclusion list

#### Pagefile Configuration

Larger modlists require a significant amount of memory and running out of memory **will** result in crashes and other potential issues.

**This step is NOT optional. Regardless of how much RAM or VRAM you have, please complete this step.**

To set up your pagefile:

1. Press **Win Key + R**
2. Type `sysdm.cpl ,3` and hit **ENTER**
3. Navigate to **Performance** and click "Settings..."
4. Click the **Advanced** tab at the top
5. Under **Virtual Memory** click "Change..."
6. Uncheck **Automatically manage** if it is checked
7. Select your disk drive, ideally your fastest solid state drive
8. Click the **Custom size:** button
9. In the box next to **Initial Size (MB)** type `40960`
10. In the box next to **Maximum Size (MB)** type `40960`
11. Click the **Set** button
12. Click **OK**
13. Click **Apply**
14. Click **OK**
15. Restart your computer for the new pagefile to take effect
    
<img width="430" height="603" alt="image" src="https://github.com/user-attachments/assets/dec2c742-0e23-468f-95e4-aef88d951be8" />

---

#### Setting Shader Cache Size (NVIDIA Graphics Cards Only)

If you have an NVIDIA GeForce Graphics Card, please do the following:

1. Right-click on your desktop and select **NVIDIA Control Panel**
2. Navigate and click on **Manage 3D settings** (2nd option from top)
3. Scroll down in Global Settings until you see **Shader Cache Size**
4. Double Click **Driver Default** next to Shader Cache Size and select **10 GB**
5. Click **Apply** in the bottom right corner
6. You may exit the application

<img width="1235" height="884" alt="image" src="https://github.com/user-attachments/assets/e6371ebe-2f73-41cd-bace-ae890dedf6c0" />


---

### Credits and Thanks

[**ItzIvy**](https://www.nexusmods.com/profile/ItzIvy?gameId=1704) for helping with testing and compiling the mod list via Wabbajack

[**DigitalVixen**](https://www.nexusmods.com/profile/DigitalVixen?gameId=3333) for the amazing mods and her continued support and shared knowledge of modding Cyberpunk 2077 

Halgari and the Wabbajack Team for their amazing platform that allows me to create and host lists like these.

[**CD Projekt Red**] - For the original game and tools that make modding possible.

[**The Community**] - For the tools, resources, and collective knowledge that make projects like this possible.

---

This work is licensed under a [Creative Commons Zero v1.0 Universal License](https://creativecommons.org/publicdomain/zero/1.0/).
