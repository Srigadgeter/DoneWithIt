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
10. Add these lines at the end of the document (.bashrc) <br />
    `export ANDROID_HOME=$HOME/Android/Sdk` <br />
    `export PATH=$PATH:$ANDROID_HOME/emulator` <br />
    `export PATH=$PATH:$ANDROID_HOME/tools` <br />
    `export PATH=$PATH:$ANDROID_HOME/tools/bin` <br />
    `export PATH=$PATH:$ANDROID_HOME/platform-tools` <br />
11. Follow all other steps & Open Emulator
