# ExplorerPatcher

This project aims to enhance the working environment on Windows.
[Read more on the Wiki »](https://github.com/valinet/ExplorerPatcher/wiki)


## How to?

1. Download the latest setup program from the [Releases page](https://github.com/valinet/ExplorerPatcher/releases/latest).
   - Choose `ep_setup.exe` if your device uses an Intel or AMD processor.
   - Choose `ep_setup_arm64.exe` if your device uses a Snapdragon processor.
2. Run the installer. It will automatically prompt for elevation, after which it will close `explorer.exe` and install the necessary files. When done, you will see the desktop again and the Windows 10 taskbar.
3. Right-click the taskbar and choose "Properties".
4. To change the taskbar style, go to the "Taskbar" section and look for "Taskbar style".
5. To use the Windows 10 Start menu, go to the "Start menu" section and change the Start menu style to Windows 10.
6. To use the Windows 10 Alt+Tab, go to the "Window switcher" section and change the "Window switcher (Alt+Tab) style" to Windows 10.
7. Feel free to check other configuration options.

That's it!

> [!WARNING]  
> **False antivirus detections**: the setup files are not digitally signed, so Windows Defender, SmartScreen, or other antivirus software may flag them as a threat and block them from running (this is a false positive).
> Just make sure you download the file (`ep_setup.exe` or `ep_setup_arm64.exe`) from a trusted source, such as [GitHub Releases](https://github.com/valinet/ExplorerPatcher/releases/latest).
>
> **Windows updates**: with each new Windows 11 release, Microsoft removes more and more of the features left over from Windows 10.
> ExplorerPatcher reimplements them on its own and grafts them back into the system, so after major Windows updates some features may temporarily stop working until the project catches up with the new version of Windows.

> [!NOTE]  
> Some features may be unavailable on some Windows versions.


## Uninstalling

You can uninstall ExplorerPatcher using any of the following methods:

- Right-click the taskbar, click "Properties" (or search for "ExplorerPatcher"), and go to the "Uninstall" section.
- Use "Programs and Features" in Control Panel, or "Apps and features" in the Settings app.
- Run `ep_setup.exe /uninstall`.
- Rename `ep_setup.exe` to `ep_uninstall.exe` and run it.


## Updating

- The program features built-in updates: go to "Properties" > "Updates" to configure, check for and install the latest updates. Learn more [here](https://github.com/valinet/ExplorerPatcher/wiki/Configure-updates).
- Download the latest version's [setup file for x64](https://github.com/valinet/ExplorerPatcher/releases/latest/download/ep_setup.exe) or [setup file for ARM64](https://github.com/valinet/ExplorerPatcher/releases/latest/download/ep_setup_arm64.exe) and simply run it.


## Donate

If you find this project essential to your daily life, please consider donating to support the development through the [Sponsor](https://github.com/valinet/ExplorerPatcher?sponsor) button at the top of this page, so that we can continue to keep supporting newer Windows builds.


## Discord Server

Join our Discord server if you need support, want to chat regarding this project, or just want to hang out with us!

<p align="center">
  <a href="https://discord.gg/gsPcfqHTD2"><img src="https://discordapp.com/api/guilds/1155912047897350204/widget.png?style=shield" alt="Join on Discord"></a>
</p>

