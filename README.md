# NekoGPT Engine Mate Bridge Plugin

Optional plugin for connecting NekoGPT to Engine Mate as an external avatar.

NekoGPT does not depend on Engine Mate. The bridge uses only `localhost`, a local pairing token, and WebSocket.

## Install in NekoGPT

1. Open NekoGPT.
2. Go to `Settings > Plugins`.
3. Paste this repository:

```text
https://github.com/inobushi3/nekogpt-engine-mate-bridge-plugin
```

4. Click `Add`.
5. Click `Enable` on `Engine Mate Avatar Bridge`.
6. Go to `Integrations > Engine Mate Plugin` to configure the port, token, and connection test.

## Install in Engine Mate

1. Download `NekoGPTBridge-Setup-1.0.1.exe` from the GitHub release.
2. Run the installer.
3. Choose the installer language.
4. Select the Engine Mate root folder, the same folder that contains `MateEngineX.exe`.
5. Open Engine Mate.
6. Open the `NekoGPT Bridge` window.
7. Paste the token shown in NekoGPT.
8. Click `Connect`.

## What the plugin does

- Shows connected/disconnected status in NekoGPT.
- Sends visual lip sync during TTS.
- Sends subtitles above the Engine Mate avatar head.
- Sends pizza, lollipop, hammer, and perfume interaction events.
- Sends dance events when the jukebox plays.
- Receives Engine Mate events such as pat pat and boundary touch so the NekoGPT chat can react through the active persona.

## What it does not do

- It does not replace the current NekoGPT Live2D/Live3D renderer.
- It does not start Engine Mate automatically.
- It does not open external network access.
- It does not execute remote code inside NekoGPT.

## Checksums

```text
NekoGPTBridge-Setup-1.0.1.exe
SHA256: F6EFAD472B454F9F00EC62698DA7A1D33626DAA56F99B6C90159A466D65D985D
```
