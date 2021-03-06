# AudioMoth Configuration App #
An Electron-based application capable of configuring the functionality of the AudioMoth recording device and setting the onboard clock.

For more details on the device itself, visit [www.openacousticdevices.info](http://www.openacousticdevices.info).

### Usage ###
Once the repository has been cloned, you must either have electron-builder installed globally, or get it for the app specifically by running:
```
npm install
```

From then onwards, or if you already had electron-builder installed, start the application with:
```
npm run start 
```

Package the application into an installer for your current platform with:
```
npm run dist
```

This will place a packaged version of the app and an installer for the platform this command was run on into the `/dist` folder.

For detailed usage instructions of the app itself and to download prebuilt installers of the latest stable version for all platforms, visit the app support site [here](http://www.openacousticdevices.info/config).

### Related Repositories ###
* [audiomoth-hid](https://github.com/OpenAcousticDevices/audiomoth-hid)
* [AudioMoth Timesetter](https://github.com/OpenAcousticDevices/AudioMoth-TimeSetter)

### License ###

Copyright 2017 [Open Acoustic Devices](http://www.openacousticdevices.info/).

[MIT license](http://www.openacousticdevices.info/license).
