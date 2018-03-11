# Project for Android with use JS

```sh
$ npm install -g cordova
$ cordova create workshop com.yourname.workshop Workshop
```

So, I have little problem when I add basic plugins

```sh
$ cordova plugin add org.apache.cordova.device
$ cordova plugin add org.apache.cordova.console
```
I changed to

```sh
$  cordova plugin add cordova-plugin-device
$  cordova plugin add cordova-plugin-console
```
Next, I download Android SDK

```sh
$ cd ~/
$ wget https://dl.google.com/android/repository/sdk-tools-linux-3859397.zip
$ unzip sdk-tools-linux-3859397.zip
```
or [here](https://developer.android.com/studio/index.html)

Dependencies

```sh
$ sudo apt-get install lib32ncurses5 lib32stdc++6
$ export ANDROID_HOME="$HOME/tools:$PATH"
$ export PATH=${PATH}:$ANDROID_HOME/tools:$ANDROID_HOME/platform-tools
$ source ~/.bashrc
```
Download platform tools [here](https://developer.android.com/studio/releases/platform-tools.html)

```sh
$ cordova run android
```