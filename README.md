
[Desktop Entry]
Version=1.0
Name=blender
Type=Application
Exec=/home/lqs/Downloads/blender_2.81/blender
TryExec=/home/lqs/Downloads/blender_2.81/blender
Terminal=false
StartupNotify=true
Icon=/home/anandharaja/Downloads/blender_2.74/icons/48x48/apps/blender.png

Name=blender2.8
Comment=Access and organize files
Keywords=folder;manager;explore;disk;filesystem;
Exec=nautilus --new-window %U
Icon=org.gnome.Nautilus
Terminal=false
Type=Application
Categories=GNOME;GTK;Utility;Core;FileManager;
Actions=new-window;open-downloads;

Name[en_US]=blender2.8.desktop

[Desktop Action new-window]
Name=New Window
Exec=nautilus --new-window

[Desktop Action open-downloads]
Name=Open my Downloads folder
Exec=nautilus /home/lqs/Downloads
