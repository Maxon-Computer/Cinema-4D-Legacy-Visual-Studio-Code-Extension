# Cinema 4D Connector - Cinema 4D Plugin

> This repository is provided as a legacy repository and is not actively maintained.

> :warning: **As of Cinema 4D 2023.2, this plugin is no longer required and supported**, as its functionality has been integrated into Cinema 4D. For more information please read the [Cinema 4D Connector documentation](https://help.maxon.net/c4d/en-us/#html/5896.html#codeexchangesendtoIDE).

Provides a plugin for Cinema 4D to exchange code between the Script Manager and external code editors.

The solution is server-based and requires a matching implementation on the side of the code editor. Such matching implementation is being provided with the Visual Studio Code extension `Cinema 4D Connector`.

## Installation

To use all the features it is necessary to install the following two extensions:

- The Cinema 4D plugin, downloadable [here](/releases). Once downloaded, extract the archive to the Cinema 4D S26+ plugins folder. You then need to activate the extension in the Cinema 4D preferences in the `Extensions | Code Exchange` menu, activate the WebSocket Json checkbox.

- The `Cinema 4D Connector` extension for Visual Studio Code, directly accessible in the Visual Studio code marketplace, or download it [here](/releases).

## Features

In-depth documentation can be found in [Cinema 4D Connector - Documentation](/documentation.md).

## Requirements

- Cinema 4D S26.

## Known Issues

If settings are not present in the preferences, you do not have the correct version of Cinema 4D.

## License

This extension is licensed under the [Apache 2.0 License](LICENSE).
