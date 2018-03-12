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
$ mkdir android
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
and put in folder **android** (unzipped)

```sh
$ cordova run android
```

sudo mkdir -p /usr/lib/jvm
sudo tar -xf jdk-8u161-linux-x64.tar.gz -C /usr/lib/jvm/



sudo nano /etc/environment

```
PATH="...:/usr/lib/jvm/jdk1.8.0_161/bin:/usr/lib/jvm/jdk1.8.0_161/jre/bin"
JAVA_HOME="/usr/lib/jvm/jdk1.8.0_161"
JDK_HOME="/usr/lib/jvm/jdk1.8.0_161"
JRE_HOME="/usr/lib/jvm/jdk1.8.0_161/jre"
ANDROID_HOME="/home/raymond/android"

```