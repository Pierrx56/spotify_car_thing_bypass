# Trying to bypass date limitation of Spotify Car Thing

Linux system is located under system_a folder
settings is located under settings folder
data is located under data folder


# !!! You need to activate large file storage !!!
`git lfs install`

Follow this tutorial to make sure your Car Thing is ready to be edited: https://www.youtube.com/watch?v=anDEqX6szcI

# Install [ADB](https://dl.google.com/android/repository/platform-tools-latest-windows.zip) for windows in C:/dev, add it to Path environment C:\dev\platform-tools

# Useful [ADB File Explorer v0.31](https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/adb-file-explorer/ADB%20File%20Explorer%20v031.zip) to transfer files

# File location
Main screen: `/usr/share/qt-superbird-app/webapp/index.html`

Main screen script: `/usr/share/qt-superbird-app/webapp/static/js/main.js`

Setup scripts: `etc/init.d/`
Edit scripts:
    `mount / -o remount,rw`
    `chmod 777 etc/init.d/S01syslogd`

Mounted disk: `/etc/fstab`
