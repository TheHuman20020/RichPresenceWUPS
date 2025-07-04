# Wii U Rich Presence Plugin

This plugin uses UDP port 5005 to communicate with an application on your computer to set Discord Rich Presence for the user. The activity is set based on the application currently being played, the time the application was loaded, and the amount of controllers connected.

## Installation
(`[ENVIRONMENT]` is a placeholder for the actual environment name.)

1. Download both `wurpWiiU.zip` and `wurpDiscord.zip` and extract both of them.
2. From `wurpWiiU`, copy the file `RichPresence.wps` into `sd:/wiiu/environments/[ENVIRONMENT]/plugins`.
3. Keep the `wurpDiscord` folder on your computer.
4. Requires the [WiiUPluginLoaderBackend](https://github.com/wiiu-env/WiiUPluginLoaderBackend) in `sd:/wiiu/environments/[ENVIRONMENT]/modules`.

## Usage
Start your Wii U with the environment you placed the plugin in.

Run `WiiURichPresence` in the `wurpDiscord` folder with the Discord app open or Discord open on your browser. Authorize the app in Discord.

Elapsed time may not show up correctly because of your Wii U's time. To offset the elapsed time that shows up in Discord by a certain amount of hours, open the plugin configuration menu and change the setting. If elapsed time displays `0:00:00`, you need to change the setting to a negative number. If elapsed time displays hours ahead of your actual play time, you need to change the setting to a positive number.

## Contribute
The plugin is missing images of many Wii U games. If you are interested in adding game images, and have a Github account, check out the [image repository](https://github.com/flamingnineteen/RichPresenceWUPS-DB) for this plugin.

## Building
For specifics on building either the plugin or the executable, please check the respective directories.
