# Development and Evaluation of XR app using W3C, WebXR API and Object detection library
## This app can detect mulitple objects from a single frame using tensorflow. 


The XR app is implemented on the top of webxr-polyfill framework. 

Apps are hosted on https://shaon-webxr.herokuapp.com

(this repo is exported from the common repo with other experiments https://github.com/shaondebnath/Web-base-Augmented-reality-with-Object-detection.git)

## WARNING
The app is developed on unstable version of webxr-polyfill. for more information please go through webxr-polyfill Framework from https://github.com/mozilla/webxr-polyfill


## Building and Running the examples

	npm install   # downloads webpack and an http server
	npm start     # builds the polyfill in dist/webxr-polyfill.js and start the http server in the current directory


Best result in Safari browser on iOS

Browse http://YOUR_HOST_NAME:8080/	and select "Multiple Object Detection in WebXR"

Video Demo: https://www.youtube.com/watch?v=r8OyJbNJEdk




For other Demo Videos checkout playlist: https://www.youtube.com/watch?v=5aqUpPg2XOE&list=PLxchafb_QYe7kxxKm8bc1vkpz3yBo5i6g




## Supported Devices and browsers

### iOS users
Install XR Browser from Apple Store(iOS 11.0 or later)
https://itunes.apple.com/us/app/webxr-viewer/id1295998056?mt=8 


### Android Users:
Step1: Install Tango Core (https://github.com/google-ar/arcore-android-sdk/releases/download/sdk-preview/arcore-preview.apk) (also can be found in google play store)

Step2: Install Browser: WebARonARCore (https://github.com/google-ar/WebARonARCore/raw/webarcore_57.0.2987.5/apk/WebARonARCore.apk)

### Supported device list
Supported devices list can be found at https://developers.google.com/ar/discover/supported-devices 
