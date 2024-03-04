# Android-Webview-App
This Android application demonstrates how to use a WebView to display web content, handle file downloads, and manage network connectivity.

[![Platform](https://img.shields.io/badge/platform-android-green.svg)](http://developer.android.com/index.html)
[![API](https://img.shields.io/badge/API-30%2B-brightgreen.svg?style=flat)](https://android-arsenal.com/api?level=30)

## Features
* **WebView Integration:** Utilizes Android's WebView to display web content within the application.
* **JavaScript Support:** Enables JavaScript execution within the WebView for interactive web experiences.
* **File Download Handling:** Implements a DownloadListener to handle file downloads initiated within the WebView.
* **Network Connectivity Management:** Monitors network connectivity changes and adjusts WebView content accordingly.
* **Offline Mode Handling:** Displays an offline HTML page when there is no network connection available.



### Screenshot
<img src="screenshot_demo.png" width="350">

### Demo

Download here : [Demo Apk](app/release/app-release.apk)

# Getting Started

[Download](https://github.com/bishwassagar/Android-Webview-App/archive/refs/heads/master.zip) or clone this repository and import it into Android Studio.

## Change Website URL 
Open the ```app/src/main/java/com/webview/myapplication/MainActivity.java``` file and replace `https://github.com/BishwasSagar` on line **52** and **62** with your website
```json
mWebView.loadUrl("https://github.com/BishwasSagar");
```
