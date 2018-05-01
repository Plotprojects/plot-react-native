# React Native with Plot Projects

This project is an example integration of the Plot Projects plugin for both Android and iOS using React Native.

### Configuration ###

Additional settings are possible using the `plotconfig.json` configuration file, an example is shown below. More information about where to place the configuration file, please have a look at [the integration guide](https://www.plotprojects.com/documentation/#react_native_integrate). The publicToken and enableOnFirstRun fields are required, the notificationSmallIcon, notificationAccentColor and askPermissionAgainAfterDays options are Android only, the maxRegionsMonitored is an iOS only setting.
	
Information about these settings can be found in our extensive documentation, in chapter 1.4: [http://www.plotprojects.com/documentation#ConfigurationFile](http://www.plotprojects.com/documentation#ConfigurationFile)

```	
{
  "publicToken": "REPLACE_ME",
  "enableOnFirstRun": true,
  "notificationSmallIcon": "ic_mood_white_24dp",
  "notificationAccentColor": "#01579B",
  "askPermissionAgainAfterDays": 3,	
  "maxRegionsMonitored": 20	
}
```

### Running the project ###

Install React Native and it's dependencies:
`npm install -g react-native-cli`

_Note_: If you already have Node installed in your system, make sure it's version 8 or newer.

Run the project in XCode/Android Studio

Further information can be found on the React Native documentation https://facebook.github.io/react-native/docs/getting-started.html


### More information ###
Website: https://www.plotprojects.com/

Documentation: https://www.plotprojects.com/documentation/

### License ###
The source files included in the repository are released under the Apache License, Version 2.0.

