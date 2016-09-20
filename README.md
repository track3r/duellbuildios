## Description

Use this plugin to build for the ios platform.
## Usage:
`$ duell build ios -simulator -debug`
## Arguments:
* `-simulator` &ndash; runs the app on the ios simulator.
* `-debug` &ndash; Use this argument if you want to build in debug.

## Release Log

# v3.5
* added main view to app delegate so that libraries can retrieve/set the main view to make integration easier.

# v5.0
* added support for Xcode 8.

## Next Major TODOs

* Properly name required-capability, capability, fullscreen and requires-fullscreen to something less confusing.