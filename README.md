## Description

StreamDeck-AudioSwitch is a C++ plugin for the Elgato StreamDeck for setting the default audio device.

It supports:
- setting input or output device
- setting default device or communication device
- either one-button-per-device, or one button to toggle between two devices

For example, this can be useful to switch between headphones and speakers if they are on different sound cards (e.g. USB speakers or USB headphones).

# Video Demo

[![YouTube Demo Video](https://img.youtube.com/vi/Y5avo5WrwwM/0.jpg)](https://www.youtube.com/watch?v=Y5avo5WrwwM)

# Installation

Download the `com.fredemmott.audiooutputswitch.streamDeckPlugin` file from [the releases page](https://github.com/fredemmott/StreamDeck-AudioOutputSwitcher/releases), and double-click it.

# Notes

This uses undocumented and unsupported Windows APIs. These have apparently worked since Windows 7, but they
might stop working at any time or have unexpected side effects.

# Thanks

- Thanks to "EreTIk" for finding/documenting the COM interface.
- Thanks to "LordValgor" for the idea of making this plugin.

# License

This project is [MIT-licensed](LICENSE), except for the image files.

The image files are proprietary, and may not be re-used or modified.
