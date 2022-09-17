# Bluestacks-Tool
A GUI application for modifying the bluestacks emulator with features such as rooting, removing ads, editing memory, backup and restore, and more!
__________________________________________________

This is still a WIP.
This is Open-source, feel free to use, modify, and redistribute anything in this repository (with credit)!

A GUI application coded in python / c++ / c# for modifying the bluestacks emulator.

Disclaimer:
Never share any bluestacks files with other people unless you trust them! Some files, such as bluestacks.conf, contain personal data like your IP address!

Note:
Check out GameguardianForWindows (WIP Tool) to modify the memory of your emulators!

Features:
-Creates desktop shortcuts for android apps and emulators and bluestacks .exe files such as HD-MultiPlayer.exe
-Transfer and sync up shared folders / files between emulators and windows
-Create, delete, and modify emulators
-Tweak emulators with features such as rooting
-Modify names and settings of emulators
-Move bluestacks folders to new directories
-Backup, repair, and restore emulators
-Modify, backup, and restore global settings
-Modify multidrive (change GUI and theme, etc.) and create new exe and files for modified multidrive
-Modify HDPlayer (remove ads etc.) and create new exe and files for modified HDPlayer
-Start and kill emulators with more reliability than the built-in systems or even task managers
-Install and uninstall all versions of BlueStacks, up to Bluestacks X, with the custom installer that is more reliable, less buggy, more feature-full, and cleaner. Features improvements such as installing all versions with a universal installer, uninstalling / cleaning up existing installations if they are found, cleaning up files the official uninstaller misses, and installing to custom paths
-Write scripts to execute tasks from outside, such as macros
-Edit the memory of your emulators with the "GameguardianForWindows: Bluestacks" plugin
-Perform actions such as uninstalling and installing apps and apks outside the emulator
-Export apks from outside your emulators
-Browse, edit, and export the android files of your emulators with Windows via a Linux to Windows file converter

How it works:
-Exe and Dll parsing, reading, and modification: Uses pereader
-Json and XML parsing, reading, and modification: Uses jsonloader and xmlparser
-Registry reading and editing: Uses windows registry editor to read and modify data like folder directories
-File / folder copying, deleting, moving, searching, and creating
-Parsing and editing the bluestacks.conf file: Parses bluestacks.conf file into dictionary for global settings, and dictionaries for each emulator's settings

Bluestacks.conf Notes:

Global:

All emulator names:
bst.installed_images
Custom cursor:
bst.custom_cursor_enabled
Bluestacks X enabled:
bst.feature.bluestacksX
Global rooting enabled:
bst.feature.rooting
Show Bluestacks X cloud instance:
bst.feature.show_cloud_instance
Default CPU Cores:
bst.fresh_cpu_core
Default RAM:
bst.fresh_cpu_ram
Language Locale:
bst.locale
Default FPS:
bst.mim.max_fps
Prefer Dedicated GPU:
bst.prefer_dedicated_gpu
Shared Folders:
bst.shared_folders
All Shortcuts:
bst.shortcut.boss_key="Ctrl + Shift + X"
bst.shortcut.decrease_volume="Ctrl + Shift + Down"
bst.shortcut.enable_disable_game_controls="Ctrl + Shift + F10"
bst.shortcut.go_back="Ctrl + Shift + 2"
bst.shortcut.go_home="Ctrl + Shift + 1"
bst.shortcut.increase_volume="Ctrl + Shift + Up"
bst.shortcut.install_apk="Ctrl + Shift + B"
bst.shortcut.mute_unmute="Ctrl + Shift + M"
bst.shortcut.open_controls_editor="Ctrl + Shift + A"
bst.shortcut.open_location_provider="Ctrl + Shift + K"
bst.shortcut.open_macro_recorder="Ctrl + Shift + 7"
bst.shortcut.open_media_folder="Ctrl + Shift + 6"
bst.shortcut.open_mim="Ctrl + Shift + 8"
bst.shortcut.open_recent_apps="Ctrl + Shift + 5"
bst.shortcut.open_settings="Ctrl + Shift + I"
bst.shortcut.open_sync_operations="Ctrl + Shift + 9"
bst.shortcut.pause_play_macros="Ctrl + Shift + U"
bst.shortcut.play_pause_sync_operations="Ctrl + Shift + P"
bst.shortcut.rotate="Ctrl + Shift + 4"
bst.shortcut.screen_translate="Ctrl + Shift + L"
bst.shortcut.shake="Ctrl + Shift + 3"
bst.shortcut.show_hide_on_screen_controls="Ctrl + Shift + F6"
bst.shortcut.take_screenshot="Ctrl + Shift + S"
bst.shortcut.toggle_eco_mode="Ctrl + Shift + F"
bst.shortcut.toggle_fullscreen="F11"
bst.shortcut.toggle_mouse_cursor_lock="Ctrl + Shift + F8"
bst.shortcut.trim_memory="Ctrl + Shift + T"
Startup Macro:
bst.startup_macro
Macros Enabled:
bst.feature.macros
Quicklaunch Enabled:
bst.feature.quicklaunch
Country Locale:
bst.country
Custom Cursor Enabled:
bst.custom_cursor_enabled


Local (per emulator):

Hide notifications:
bst.instance.Nougat32.autohide_notifications
CPU Cores:
bst.instance.Nougat32.cpus
DPI:
bst.instance.Nougat32.dpi
Eco Mode:
bst.instance.Nougat32.eco_mode_max_fps
FPS Display:
bst.instance.Nougat32.enable_fps_display
High FPS:
bst.instance.Nougat32.enable_high_fps
Notifications:
bst.instance.Nougat32.enable_notifications
Root Access:
bst.instance.Nougat32.enable_root_access
Vsync:
bst.instance.Nougat32.enable_vsync
Max FPS:
bst.instance.Nougat32.max_fps
RAM:
bst.instance.Nougat32.ram
Show sidebar:
bst.instance.Nougat32.show_sidebar
Pin to top:
bst.instance.Nougat32.pin_to_top
Controls Overlay:
bst.key_controls_overlay_enabled
Overlay Opacity:
bst.key_controls_overlay_opacity
