# Zaman TV for Windows and Android

A live TV player. It plays free public channels from around the world, and
playlists or accounts you add yourself (M3U, Xtream Codes, with an XMLTV TV
guide). Zaman TV comes with no subscriptions; add only playlists and accounts
you are allowed to watch.

## Download

**[Download the latest version](https://github.com/chahinali85-alt/zaman-tv-download/releases/latest)**

### Android

- `ZamanTV-<version>.apk`: open it on the phone or tablet to install. Android
  asks once to allow installing apps from the browser or Files app you opened
  it with: tap **Settings**, turn on **Allow from this source**, go back and
  tap **Install**.

Android 7 or newer.

### Windows

- `ZamanTV-Setup-<version>.exe`: the installer (recommended). Adds Zaman TV
  to the Start menu, offers a desktop icon, and can be removed from
  Settings > Apps. No administrator rights needed.
- `ZamanTV-Windows-<version>.zip`: portable version. Unzip anywhere and run
  `ZamanTV.exe`.

Windows 10 or 11, 64-bit.

## "Windows protected your PC"

The installer is not code-signed yet, so Windows SmartScreen may warn the
first time. Click **More info**, then **Run anyway**.

## Using it

- Pick a country or list with the button at the top right; choose a channel
  from the list. On a phone, swipe up or down on the picture to change
  channel.
- Space: play or pause. Up and Down: change channel. Left and Right: volume,
  M: mute. F: full screen layout, Esc: leave it. Move the mouse to show the
  controls.
- Search channels with the magnifier, or Ctrl+F. Enter plays the first match.
- Tap a heart to add a favorite. The Favorites tab keeps them from every
  country and list, and plays them from wherever you are.
- To watch your own playlist or account, open the list menu and choose
  "Add IPTV link".

## Licenses

Zaman TV plays some streams with [libmpv](https://mpv.io) and
[FFmpeg](https://ffmpeg.org), used under the GNU Lesser General Public License
2.1 or later and shipped as separate libraries (`libmpv-2.dll`). Their source
code is available from those projects; the build used is
[media-kit/libmpv-win32-video-build](https://github.com/media-kit/libmpv-win32-video-build/releases/tag/2023-09-24).
