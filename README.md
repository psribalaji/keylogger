# keylogger


This is the simple keylogger which will capture all the keystrokes and it will save the keystrokes with the timestamp to the remote server. This will work only on rooted devices if (android_version is > 6). Rooting is not mandatory for devices (android_version <5). Using the Accessibility Service as an listener here. And I made a simple server configuration in the server.go to my domain. It might work if the user manually enables the accessibility service in the settings.
