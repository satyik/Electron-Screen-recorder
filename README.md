# Electron-Screen-recorder
An electron Screen capturing desktop app using Electron JS

*Electron* uses Chromium and Node.js so you can build your app with HTML, CSS, and JavaScript.
Access information about media sources that can be used to capture audio and video from the desktop using the navigator.mediaDevices.getUserMedia API.
To capture video from a source provided by desktopCapturer the constraints passed to navigator.mediaDevices.getUserMedia must include chromeMediaSource: 'desktop', and audio: false.
To capture both audio and video from the entire desktop the constraints passed to navigator.mediaDevices.getUserMedia must include chromeMediaSource: 'desktop', for both audio and video, but should not include a chromeMediaSourceId constraint.
