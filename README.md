# DoneWithIt
A React Native App


## Steps to Install Android Studio in the Linux Machine

Reference Video: https://youtu.be/0-S5a0eXPoc - Time: 00:18:02 - Running on an Android emulator

Reference: https://developer.android.com/studio/install#linux

1. Download Latest version of android studio from the official site
   Downloaded File: android-studio-2021.1.1.21-linux.tar.gz
2. Extract the compressed file
3. Open the terminal & run following commands
4. `sudo mv ./Downloads/android-studio /usr/local/`
5. `cd /usr/local/android-studio/bin/`
6. `./studio.sh`
7. Follow steps to install the android studio related packages (SDK, Emulator, etc,.)
8. Follow steps given in this site: https://docs.expo.dev/workflow/android-studio-emulator/
9. At the bashrc file script step, Do this. Open the `.bashrc` file present in home directory (Access in terminal like this `vi ~/.bashrc`)
10. Add this line at the end of the document (.bashrc)
    `export ANDROID_SDK=/home/sridhar/Android/Sdk`
    The path is Android SDK Location, it will get from the Android Studio > SDK Manager window
11. Follow all other steps & Open Emulator
