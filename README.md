# PenguinMod-Messenger

A Messenger program built for PenguinMod.

## Important Note

Due to race condition concerns, I will not provide a prepackaged version, as that would share a single project ID.

To use this project, you must package it yourself using the PenguinMod Packager:
https://studio.penguinmod.com/PenguinMod-Packager

## Packaging Instructions

When packaging the project, use the following settings:

Enable:
- Turbo Mode
- Enable Dangerous Optimizations
- Remove sandbox on the JavaScript Extension
- Try to embed cached copy of custom extensions instead of downloading them each time the project is run
- Remove raw asset data after loading to save RAM
- Enable legacy permission manager
- Optimize generated code

Disable:
- Interpolation
- Infinite Clones
- Remove Fencing
- Remove Miscellaneous Limits
- Special cloud variable behaviors (HTMLifier)
- Additional unsafe special cloud behaviors
- Increase max vector costume resolution
- Remove default fonts (Sans Serif, Pixel, etc.)

## Cloud Variables

Make sure to enable cloud variables and use any server you prefer.
