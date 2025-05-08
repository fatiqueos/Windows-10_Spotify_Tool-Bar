# Windows 10 Spotify Tool Bar
A Windows 10 toolbar to show your current Spotify song in the taskbar

![Spotify Widget](https://i.debuggings.dev/Nwiag4WQ.png)

If the song name is too long hovering over the widget will show the full name.  
![Tooltip](https://i.debuggings.dev/garj5pZK.png)

If the song name is shorter than the maximum, the widget will be resized.  
![Resized Widget](https://i.debuggings.dev/0I6bv8MG.png)

The currently played track is grabbed from the Spotify window's title. If Spotify is not running the widget will hide entirely. If the song is paused the widget will simply say "Paused".

## Installation
1) Grab the latest release from the releases page.
2) Unzip it somewhere on your computer.
3) Run `register.bat` as Administrator.
4) Enable the Toolbar in your taskbar.  
<img src="https://i.debuggings.dev/lw7ueEla.png" width=400px>
## Running on Windows 11

Use **ExplorerPatcher** to restore classic taskbar functionality.

### Steps:
1. Install **ExplorerPatcher** from [here](https://github.com/valinet/ExplorerPatcher/releases).
2. Enable classic taskbar.
3. Follow the regular Spotify toolbar setup (download, run `register.bat`, and enable the toolbar).

Once ExplorerPatcher is active, the toolbar will work on Windows 11.
