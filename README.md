<p align="center">
  <img src="docs/apple-touch-icon.png" width="128" height="128" alt="Dofi Player app icon">
</p>

<h1 align="center">Dofi Player</h1>
<p align="center"><b>Plays almost every video, fast and light. Finds subtitles from any file name. No ads, no account, no tracking. Free, with nothing locked.</b></p>

<p align="center">
  <a href="https://github.com/shajib-bh/dofi-player/releases/latest"><b>Download for Mac</b></a> ·
  <a href="https://shajib-bh.github.io/dofi-player/">Website</a>
</p>

Dofi Player is a native video player for Apple-silicon Macs, built in Swift on the mpv engine.

## Why people choose Dofi

- **Plays almost everything, fast and light.** MKV, MP4, MOV, AVI, WebM and dozens more open with a double-click, including 4K and HEVC with hardware decoding. In our side-by-side test on a MacBook Pro, Dofi showed the first frame in 0.86 seconds; IINA took 1.39. A 4K HEVC movie plays on less than a quarter of one CPU core.
- **Subtitles from the messiest file name.** Got `The.Godfater.1972.1080p.BluRay.x265-YTS.MX.mkv`? Press ⌘F. Dofi strips the release tags, fixes the typo to The Godfather (1972) and searches OpenSubtitles, Podnapisi and, for TV episodes, Addic7ed. Subtitles made for your exact copy come first; machine-translated ones sink to the bottom.
- **Two subtitles at once**, each with its own size, colour, position and background. Out of sync? Fix sync re-times the whole file from two points. Your own SRT, ASS and VTT files work too.
- **Any link, and a clip of just the best part.** Paste a YouTube, Vimeo, X or Reddit link with ⌘U. Mark a start and an end, and Dofi saves that moment as a clip, downloading only the part you marked. Its link engine updates itself every few days.
- **See before you jump.** Hover over the timeline and a frosted glass card shows the scene under your pointer.
- **Your movie on more than one screen.** Press ⇧⌘D and the same movie plays on every display, in sync. Or stretch it across all your monitors, black out the other screens, or send it to another display.
- **Beautiful on your Mac.** 11 themes, with real Liquid Glass on macOS 26, and a frosted Glass look for the player controls. Picture in Picture, a corner mini player, screenshots at your file's full resolution, and Dofi's own icons for 44 file types.
- **Resume, playlists, multiple windows** and one-click updates.
- **Free. Really free.** No ads, no account, no tracking, and no Pro version: every feature is in the free download.

## How Dofi compares

Checked 18 October 2026 from each player's own site, release notes or source. "–" means we couldn't confirm it either way.

| | Dofi 1.0 | IINA 1.5 | VLC 3.0 | Infuse 8.5 | Movist Pro 2.21 | Elmedia 8.24 |
|---|---|---|---|---|---|---|
| Subtitle search that fixes messy, misspelled file names | **Yes**, 3 sources | Search, raw file name | Add-on menu | Needs a library match | – | Search |
| Two subtitles at once | **Yes** | Yes | No (planned for VLC 4) | No | Yes | – |
| YouTube and web links | **Yes**, link engine updates itself | Yes | No (removed Sept 2026) | No | Pro only | No |
| Save a clip | **Yes**, even from YouTube | Plug-in | Yes | No | – | – |
| Picture in Picture | **Yes** | Yes | No (planned for VLC 4) | Yes | Pro only | PRO only |
| Same movie on every screen, one click | **Yes** | No | No (clone windows you place by hand) | – | – | – |
| Price | **Free, everything** | Free | Free | Free, Pro $16.99/yr | $17.99 | Free, PRO $19.99 |

## Requirements

- A Mac with Apple silicon (M1 or newer)
- macOS 14 Sonoma or later

## Install

1. Download the latest `.dmg` from [Releases](https://github.com/shajib-bh/dofi-player/releases/latest) and open it.
2. Drag **Dofi Player** into **Applications**.
3. Open the picture **View the setup guide** in the same window. It shows the one-time steps with the real macOS screens:
   - Open Dofi Player. macOS says it was not opened: click **Done** (not Move to Trash).
   - Go to **System Settings → Privacy & Security**, scroll down and click **Open Anyway**.
   - Click **Open Anyway** once more, then confirm with Touch ID or your password.

You only do this once. macOS asks because Dofi is made by an independent developer without Apple's paid developer program, so it isn't notarized. After that, updates install with one click.

## Privacy

No ads, no account, no tracking. Dofi goes online only to check for updates (for Dofi and its link engine), to search subtitles when you ask, and to play links you paste.

## Open source

Dofi Player plays video with [mpv](https://mpv.io/) and [FFmpeg](https://ffmpeg.org/), used under the GNU LGPL. Every release includes their source and a kit to rebuild Dofi with your own version of them.

## Credits

Designed & built by **[Shajib Bhuiyan](https://www.linkedin.com/in/shajib-bhuiyan/)**.

<sub>Keywords: Mac video player, free video player for macOS, MKV player for Mac, subtitle downloader for Mac, mpv player, IINA alternative, VLC alternative, Apple silicon video player.</sub>
