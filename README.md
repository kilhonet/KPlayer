# KPlayer

**A clean, free video player with no ads.**

English · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> This document is a translation. If anything differs, the [Korean version](README.ko.md) is authoritative.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20x64-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Source](https://img.shields.io/badge/source-GPL--2.0--or--later-lightgrey)
![Version](https://img.shields.io/badge/version-1.1.0-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/kplayer?lang=en)

![KPlayer screenshot](images/kplayer-en.webp)

## Overview

KPlayer is a video and music player with no ads and no clutter. It is built on the open-source media engine **libmpv**, so it plays 38 formats out of the box — 23 video, 12 audio and 3 playlist formats — without installing any codecs.

The window shows only the video; the controls appear at the bottom only when you move the mouse. Drop a file on the window and it starts playing, and when you open one episode of a series, the following episodes in the same folder are queued up in order.

Every keyboard shortcut and mouse action can be changed, and subtitles can be styled in detail, down to the font, color, outline and position.

## Features

- **38 formats** — 23 video formats including MP4, MKV, AVI, MOV, WMV, WebM, TS, M2TS, VOB and RM/RMVB; 12 audio formats including MP3, FLAC, AAC, M4A, WAV, OGG, Opus, WMA, APE and DSF; and 3 playlist formats (M3U, M3U8, PLS).
- **No codecs to install** — everything needed for playback is included.
- **Hardware acceleration** — keeps high-resolution video smooth.
- **Drag and drop** — drop on the main window to replace the list and play right away, or on the playlist window to add to the list. Drop a folder and only its media files are added.
- **Next episodes added automatically** — opening a file queues the related files in the same folder (Episode 1, Episode 2…) in order.
- **Playlist** — drag to reorder, repeat (all or one), shuffle, and the list is remembered after you close the program.
- **Subtitles** — show/hide, track switching, font, size, color, bold, outline, shadow, position and alignment, and automatic subtitle language selection based on your Windows display language.
- **Playback control** — chapter skipping, frame stepping, speed (0.25×–4.0×), screenshots (JPG/PNG).
- **Info panel** — press `TAB` to see file, codec, resolution, frame and audio details at a glance.
- **Volume normalization** — narrows the gap between quiet and loud sounds (adjustable strength).
- **Custom shortcuts and mouse** — assign keys for 30 actions and choose what click, double-click, middle button and wheel do.
- **File associations** — register file types one by one in Settings and open the Windows default app picker directly.
- **Clean look** — borderless dark window, always on top, remembers window position and size.

## Download / Installation

| Package | Link |
|---|---|
| Installer | [Download](https://down.kilho.net/kplayer?lang=en) |
| Portable (ZIP) | [Download](https://down.kilho.net/kplayer?lang=en&nosetup) |

For the portable version, extract the ZIP anywhere and run `KPlayer.exe`.

After installation, the installer associates common files such as MP4, MKV, AVI, MOV, WMV, WebM, TS, MP3, FLAC, M4A and WAV with KPlayer. The portable version leaves associations alone; register the ones you want under Settings → **File types**.

## Usage

### Getting started

1. When you start KPlayer, the start screen shows the **KPlayer logo** in the middle.
2. Drag a video or music file onto the window. You can also click the logo or press `Ctrl+O` to pick a file.
3. Playback starts right away. Move the mouse and the controls appear at the bottom; leave it still for a moment and they fade out.
4. `Space` pauses, `←` `→` skip 5 seconds, `↑` `↓` change the volume. `Enter` or a double-click goes full screen, and `ESC` brings you back.
5. The playlist button at the bottom right opens the playlist window, and the gear button next to it opens Settings.

### The window

**Player window**

| Element | What it does |
|---|---|
| Top bar | Name of the file playing. On the right: pin (always on top) · minimize · full screen · close |
| Progress bar | Click or drag to seek. Hover to see the time at that point in a tooltip; chapter marks appear if the file has chapters |
| ⏮ ▶ ⏭ | Previous file / play-pause / next file |
| Speaker | Click to mute. Hover to slide out the volume bar |
| Time | Current position / total length |
| Subtitles | Show/hide subtitles — appears only for files with subtitles |
| Gear | Settings |
| List | Open/close the playlist window |

Drag anywhere on the window to move it, and drag an edge to resize it. When you change the volume or speed, the new value shows briefly in the middle of the screen.

**Right-click menu**

| Menu | What it does |
|---|---|
| Open file / Open folder | Pick a file or folder, add it to the list and play |
| Screen size | 50% · 100% · 150% · 200% of the video size, Full screen, Full screen (stretched) |
| Created by Kilho | Opens the website |

**Playlist window**

| Button | What it does |
|---|---|
| Repeat | Cycles No repeat → Repeat all → Repeat one |
| Shuffle | Turns shuffle on/off |
| + | Add — File / Folder |
| − | Remove — Selected files / Unselected files / All items / Missing files |

Double-click an item to play it; the `Delete` key removes the selected items from the list (the files themselves are not deleted). The item that is playing is shown in a different color.

### How to…

**Watch a series from episode 1 in order**
Just open one episode. KPlayer looks in the same folder for files whose names continue with a number (`Episode 1`·`Episode 2`, `S01E01`·`S01E02` and so on) and adds them to the list in numeric order — `2` comes before `10`. If you open episode 3, the list starts at episode 1 but playback starts at episode 3.
- Opening a video does not pull in music files from the same folder, and opening music does not pull in videos.
- To add every file of the same kind in the folder, set Settings → **General → Auto-add files in folder** to **All files**; to add only the file you opened, set it to **Off**.

**Start a fresh list / add to the end of the list**
Drop files on the **main window** and the current list is cleared and replaced with the dropped files, which start playing right away. Drop them on the **playlist window** and they are added after the existing list, playing from the first one added. A file already in the list is never added twice.

**Add a whole folder**
Drag a folder onto the window, or right-click → **Open folder**. KPlayer searches subfolders too and adds only the files it can play; images, documents and other files are skipped automatically.

**Open several files from File Explorer**
Select several files in File Explorer and press Enter: they all go to a single KPlayer window, the first file plays and the rest are added to the list. What happens when KPlayer is already open is set under Settings → **General → If already running**.
- **Play in running player** (default) — the newly opened file plays in the window that is already open.
- **Add to running playlist** — keeps playing what you were watching and only adds to the list. Handy for collecting songs while you listen.
- **Allow multiple** — opens a new window for each file. Use it to compare two videos side by side.

**Open M3U or PLS playlist files**
Open or drop a playlist file and the tracks listed inside are added to the list and play from the first one. Paths written relative to the playlist file's location work, and so do playlists saved in Notepad with non-English names.

**Shuffle your music**
Turn on the **Shuffle** button in the playlist window. No track repeats until the whole list has played; after a full cycle the list is reshuffled and playback continues. The previous button (⏮) goes back through the order you actually listened to. Hover over the button to see a description of the current mode.

**Repeat one track / loop the whole list**
Click the **Repeat** button in the playlist window to switch to **Repeat one** or **Repeat all**. Repeat one takes priority even when shuffle is on. With No repeat, playback stops at the end of the list, keeping the last frame on screen.

**Reorder the list**
Grab an item and drag it up or down. Select several items with `Ctrl` or `Shift` to move them together. Drag to the top or bottom edge and the list scrolls by itself.

**Keep files from a USB stick or network drive in the list**
Unplugging the drive does not remove its files from the list; those items are shown with their full path instead. When one comes up, a brief "File not found" notice appears on screen and KPlayer moves on to the next file. Reconnect the drive and the items return to normal on their own. To clear out files that are really gone, use **− → Missing files** in the playlist window.

**Keep the list for next time**
With Settings → **General → Save playlist** on (default), the list you had when you closed KPlayer comes back the next time. Even if you start KPlayer by double-clicking a file in File Explorer, that file plays, not the first track of the old list. To start with an empty list every time, set it to **Off**.

**Turn on subtitles**
Subtitles start out off. When you open a file with subtitles, a **subtitles button** appears at the bottom; click it or press `V`. Subtitle files with the same name as the video (`movie.srt`, `movie.en.srt` and so on) are loaded automatically.
- To always show subtitles, set Settings → **Subtitles → Show subtitles by default** to **On**.
- If there are several subtitle tracks, switch with `J` / `Shift+J`.
- For MKV files with several tracks, KPlayer picks subtitles in your Windows display language first, then English. To prefer other languages, list them in order in **Preferred subtitle languages**, for example `ja,jpn,en,eng`.

**Make subtitles easier to read, or change their size and position**
Under Settings → **Subtitles**, change the size, font, bold, text color, outline width and color, shadow, vertical position and alignment. Changes show on the player right away, so you can adjust while you watch. To move subtitles down into the black bar below the video, adjust **Vertical position**.
For styled subtitles with effects (ASS), such as karaoke subtitles, set **Prefer subtitle file style** to **On** so they look the way the subtitle file intends.

**Watch lectures and meetings faster**
`C` speeds up by 0.1×, `X` slows down, `]` / `[` change it by 10%, and `Z` returns to 1.0×. The range is 0.25× to 4×, and the current speed shows briefly in the middle of the screen each time you change it.

**Find the exact scene you want**
`Shift+←` / `Shift+→` move exactly 1 second, and `,` / `.` step one frame backward or forward. In videos with chapters, `Ctrl+←` / `Ctrl+→` jump between chapters, and the chapters are marked on the progress bar.

**Save a scene as an image**
Press `S` and the current frame is saved to your **Desktop** with a number added to the file name, like `movie.mp4-0001.jpg`. Change the folder and format (JPG/PNG) under Settings → **General → Screenshot folder / Format**. Choose PNG for lossless images.

**Watch in a small window while you work**
Click the **pin** button in the top bar and the window stays on top of other windows (the playlist window too). Shrink it and park it in a corner of the screen. Right-click → **Screen size → 50%** halves it to half the video size in one step.

**Choose the window size when a video opens**
Choose under Settings → **General → Window size on play**.
- **Keep last size** (default) — the size you always use.
- **Fit to video size** — sizes the window to each video's original size. If that is larger than the screen, it shrinks to fit while keeping the aspect ratio.
- **Full screen** — starts in full screen as soon as a video opens.

The window position and size are remembered after you close KPlayer, and if that monitor has been disconnected, the window opens on a screen you can see.

**Fill the screen with a video of a different aspect ratio**
Right-click → **Screen size → Full screen (stretched)** stretches the video over the whole monitor with no black bars. Leaving full screen restores the original ratio. If you use it often, set the double-click to **Stretched full screen / restore** under Settings → **Mouse**.

**Even out volume that jumps between videos**
**Volume normalization** is on by default: it raises quiet dialogue and tames loud effects. To narrow the gap further, set Settings → **Audio → Normalization strength** to **Strong**; to hear the original sound, set **Use volume normalization** to **Off**. The starting volume is set with **Default volume**.
Raising the volume while muted unmutes automatically.

**Seek with the wheel instead of changing the volume (change mouse actions)**
Under Settings → **Mouse**, pick a function for Left button single click, Left button double click, Middle button click, Wheel up and Wheel down. For example, set the wheel to **Seek forward / Seek backward**, a single click to **Play/Pause**, and the middle button to **Play next file**.

**Use keys you are used to**
Under Settings → **Shortcuts**, select an action, click the box below and press the key (or key combination) you want. **Clear** removes a key, and **Default shortcuts** restores the originals. You can also assign keys to **Playlist**, **Settings** and **Always on top**, which have no key by default. The default shortcuts are:

| Key | Action |
|---|---|
| `Space` | Play/Pause |
| `Enter` | Full screen (`ESC` to exit) |
| `←` / `→` | Back / Forward 5 s |
| `Shift+←` / `Shift+→` | Back / Forward 1 s (exact) |
| `Ctrl+←` / `Ctrl+→` | Previous / Next chapter |
| `,` / `.` | Previous / Next frame |
| `↑` / `↓` | Volume +5 / −5 |
| `0` / `9` | Volume +2 / −2 |
| `M` | Mute |
| `Page Up` / `Page Down` | Previous / Next file |
| `V` | Show/hide subtitles |
| `J` / `Shift+J` | Next / Previous subtitle track |
| `S` | Screenshot |
| `X` / `C` | Speed −0.1 / +0.1 |
| `[` / `]` | Speed −10% / +10% |
| `Z` | Speed 1.0x |
| `Ctrl+O` | Open file |
| `TAB` | Info panel (fixed) |

**See file details (codec, resolution, bitrate)**
Press `TAB` during playback to see the file name, format and size, the video codec, resolution and frame rate, whether hardware decoding is in use, the audio codec, channels and sample rate, the subtitle track and the volume on one screen. It refreshes every second; press `TAB` again to close it.

**Open video files with KPlayer when you double-click them**
Under Settings → **File types**, tick the extensions you want. **Common types** ticks the most-used formats and **Select all** ticks all 38; each is registered the moment you tick it. Files registered by KPlayer get a per-extension icon.
On Windows 10 and 11 you have to choose the default app yourself, so extensions whose default app is another program show a **[Not applied]** badge. Click the badge to open the Windows default app picker directly and choose KPlayer. **Open Windows default apps settings** opens Windows Settings so you can change them all at once.
- If you move the portable folder elsewhere, the associations follow the new location the next time you run KPlayer.
- Uninstalling the installed version restores every association KPlayer registered to what it was before.

**Reset settings**
Click **Default** at the bottom of the Settings window to return all settings, shortcuts and mouse actions to their defaults. File associations are not changed.

**Tune video output for your graphics card**
Under Settings → **Video**, choose **Hardware decoding** (Auto (safe) / Auto / Disabled), **Output driver**, **Graphics API** (Auto / Direct3D 11 / OpenGL / Vulkan), **Display sync**, **Upscaler** and **Deinterlace**. The defaults are best in most cases. Settings on this card take effect the next time you start KPlayer.

## Configuration

Settings are changed on the cards of the Settings window and saved immediately (the **Video** card takes effect after a restart).

| Card | Item | Default |
|---|---|---|
| General | Repeat mode · Shuffle | No repeat · Off |
| | Save playlist | On |
| | Auto-add files in folder | Related files only |
| | If already running | Play in running player |
| | Screenshot folder · Format | Desktop · JPG |
| | Always on top | Off |
| | Window size on play | Keep last size |
| Video | Hardware decoding · Output driver · Graphics API · Display sync · Upscaler · Deinterlace | Auto (safe) · gpu · Auto · Display resample · lanczos · Auto |
| Audio | Default volume | 100 |
| | Use volume normalization · Normalization strength | On · Medium |
| Subtitles | Show subtitles by default | Off |
| | Subtitle size · Preferred subtitle languages | 55 · Windows display language + English |
| | Font · Bold · Text color · Outline width · Outline color · Shadow · Vertical position · Alignment | (Default) · Off · White · 3 · Black · 0 · 100 · Center |
| | Prefer subtitle file style | Off |
| File types | Register per extension · Default app picker | Installer registers common types |
| Shortcuts | Keys for 30 actions | Table above |
| Mouse | Single click · Double click · Middle button · Wheel up/down | Do nothing · Full screen / restore · Do nothing · Volume up/down |

Settings and the playlist are stored in the same folder as the program, so moving the portable folder takes them along.

The interface language follows your Windows display language (Korean, English, Japanese, Chinese, Russian, Italian, French, Spanish, Arabic — English for other languages).

## Requirements

- Windows 10 or Windows 11, **64-bit**
- No codecs or other components to install.
- An internet connection is used only for new-version notices.

## Updates

KPlayer does **not** update itself. At startup it checks for a new version and shows a notice; if you choose to get it, the download page opens and the program closes. New versions are released manually after internal testing and announced on the [KPlayer page](https://kilho.net/kplayer). See the [update policy notice](https://en.kilho.net/archives/notice/2940).

## Building from Source

The source is available at [github.com/newkilho/KPlayer](https://github.com/newkilho/KPlayer). It is built with [Lazarus](https://www.lazarus-ide.org/) 4.x (FPC 3.2.2, Win64) and needs:

- [LibMPVDelphi](https://github.com/nbuyer/libmpvdelphi) — the libmpv binding units
- `laz.virtualtreeview_package` — the Virtual Treeview package that ships with Lazarus
- `libmpv-2.dll` next to `KPlayer.exe` at run time

Copy `Const-sample.inc` to `Const.inc` and build with `lazbuild KPlayer.lpi`. However, a shared library (klib) that handles update checks, translation and more lives outside the repository, so the repository alone does not produce an executable.

## Contributing

Please send bug reports and suggestions through GitHub issues or the [forum](https://kilho.top/forum/qna).

## License

The KPlayer program is **freeware**. You can use it free of charge anywhere — at the office, at home, in government offices or at school — and redistribute it freely anywhere.

The source code is licensed under the **GNU GPL v2 or later**. The open-source components used, including the playback engine libmpv (GPL-2.0-or-later), are listed in `THIRD-PARTY-NOTICES.txt` in the installation folder.

## Links

- Website: <https://kilho.net/kplayer>
- Source: <https://github.com/newkilho/KPlayer>
- Forum: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
