# Cordova OutSystems Notificare Core

Main dependency for all OutSystems Notificare plugins, that handles the Notificare configurations files for iOS and Android. 


## How to use it


#### Add the plugin dependency
The Notificare Core plugin must be added as a dependency in the plugin.xml as shown below:
```
<dependency id="cordova-plugin-outsystems-notificare-core" url="https://github.com/kelter-antunes/cordova-plugin-outsystems-notificare-core"/>
```
Please, always check if there is a newer tag version available, and update it accordingly.

## Notes
The configuration files will be imported by the Notificare Core plugin's hook, and there will be no need to have multiple configuration files for different Notificare components anymore.
