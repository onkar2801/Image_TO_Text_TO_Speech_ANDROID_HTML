
# Image to Text to Speech

Our objective is to turn a text image into a string of words, save it to a file, then play the audio to read what is written there.


## Pre-Requisites
+ node.js
+ cordova
+ jdk 1.8+
## Installation

Install cordova:
```bash
    npm install -g cordova
```
Before creating project check the requirement of cordova env:
```bash
    cordova requirements android --verbose
```
Creating new Cordova project:
```bash
    cordova create itts com.cordova.itts ITTS 
```
Unzip the file

For building the android app used following cmd:
```bash
    cordova platform add android
```
## Plugins 
For camera plugin
``` bash
    cordova plugin add cordova-plugin-camera
```
For Mobile OCR plugin
```bash
    cordova plugin add cordova-plugin-mobile-ocr
```
For Text To Speech
```bash
    cordova plugin add cordova-plugin-texttospeech
```


## Code files
Put this files under the **www** folder

+ index.html
+ index.css
+ index.js

also extract **img.zip** into **img folder**

## Deployment

Path of output file:
```path
    Project_Name/platform/android/app/build/outputs/apk/debug
```
Copy the **"app-debug.apk"** file and paste it on Android device

## Useful Links 
Cordova site: 
https://cordova.apache.org/docs/en/latest/guide/cli/
