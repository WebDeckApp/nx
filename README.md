# WebDeckNX
**Launches the Internet Browser applet.**
<br>
([BrowseNX](https://github.com/crc-32/BrowseNX) fork)

## Usage
1. Make sure you already have a [WebDeck](https://github.com/Lenochxd/WebDeck) instance started on your PC
2. Open the app in non-applet mode by holding R on an APP (e.g. a game) NOT an applet (e.g. Gallery)
3. Choose how to start the app:
    - Press L to choose a URL directly
    - Press R to set the default URL (recommended)
    - Press X to reset the default URL
    - Press - to launch as an auth applet (not recommended)
4. WebDeck !

## Credit
- p-sam - Supernag fix via sysmodule included in previous releases: https://github.com/p-sam/switch-sys-tweak AND wifiwebauthapplet fallback: https://github.com/switchbrew/libnx/commit/8360e561c5e48f7a2a704df3c97657e0d879629b used in previous releases
- XorTroll - Working out the browser applet arguments and for the nsp structure/build method.
- The-4n - Making legal NSP packing easy.
- Switchbrew - NPDMTool
- Lenoch - poorly made fork

## Building

### Requirements
 - Libnx
 - switch-tools devkitpro package

### Windows
 - You need to have devkitpro installed with msys, including command prompt support for msys-specific commands like `mv`
 - Run `make`

### Linux
 - Run `make`
