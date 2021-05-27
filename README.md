# Android-Webview-App
A Simple To Use App That Shows Web Pages Within The App And Download Content Using Phone's Internal Downloader

[![Platform](https://img.shields.io/badge/platform-android-green.svg)](http://developer.android.com/index.html)
[![API](https://img.shields.io/badge/API-21%2B-brightgreen.svg?style=flat)](https://android-arsenal.com/api?level=21)

#Screenshot

![ANDROID WEBVIEW](https://raw.githubusercontent.com/satyakami/Android-Webview-App/master/screenshot_demo.png)!

# Demo

Download here : [Demo Apk](https://github.com/satyakami/Android-Webview-App/raw/master/demo.apk)

# How To Build Your Own App

## Change Package name
- Change package name in  ```app/build.gradle```
```json
applicationId "com.webview.app"
```
Replace with your package name
```json
applicationId "your.package.name"
```
## Change Website URL (Line 68)
```app/src/main/java/com/webview/app/MainActivity.java```
```json
mWebView.loadUrl("https://fast.com");
```
Replace The Link With Whatever You Want

## Replace Logo
- You Can Use This Website To Create Icons For Your App 
[APP ICON GENERATOR](https://appicon.co/)
- Replace logo **ic_launcher.png** in ```app/src/main/res/``` directory

_**You Are DONE**_
