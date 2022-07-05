# Virtual DMX Lighting Template

## Overview
This is a Unity project file for a virtual light art installation. It cannots assets and scripts that connects to the DMXForArtists library github.com/jaysonh/DMXForArtists and enables one to control a virtual light installation in Unity with the same code that sends DMX signals to an FTDI USB DMX device.

## How to Use
First install and setup up Unity https://unity.com/download then install Processing https://processing.org/download then in Processing from the libraries manager install the DMXForArtists and OSCP5 libraries.

Once these have all been setup run the Unity project and when in game mode it will receive DMX data via OSC from the Processing Unity Bridge: https://github.com/jaysonh/DMXUnityBridge 