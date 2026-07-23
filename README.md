# Bean

Bean is a lightweight local file sharing app for sending files between devices on the same network. It can also create a secure temporary public link through ngrok when remote access is needed.

![Bean interface](bean_design.png)

## First release

Download `Bean.exe` from the [latest release](https://github.com/vxncius-dev/Bean/releases/latest), open it, and use the address or QR code shown by the app to connect from another device.

The app stores shared files locally on the host computer. The ngrok authtoken is stored locally in encrypted form using Windows DPAPI.

## Remote access

Open Settings, paste your ngrok authtoken, and start the tunnel. Bean updates the displayed address and QR code to the generated HTTPS link. Stopping the tunnel returns the app to the local network address.

## Status

The Android APK is currently in development and will be available soon.

## License

This repository contains the compiled Windows release and product assets only. Source code is not included in this repository.