<!-- © 2026 James Edward Honiball. All Rights Reserved. -->
<!-- Tomo™ (友) — Social Reading Companion for Kobo -->

# Tomo

A social reading companion for Kobo and Kindle e-readers.

Tomo (友, friend) is a plugin for KOReader that adds quiet social presence to your reading life. It is not a social network. It has no feed, no algorithm, no engagement metrics. It is simply a place where readers can be together.

## A place for readers

Imagine a small bookshop at the edge of your neighbourhood. You visit when you want to. It is always there. It never calls to you. Inside, eight rooms (one for fantasy, one for romance, one for literary fiction, and five more) where readers leave notes for each other between the shelves.

Tomo is that bookshop, living inside your e-reader.

**Genre rooms.** Eight permanent rooms where readers gather around what they love: Fantasy and Sci-Fi, Romance, Literary Fiction, Thriller and Mystery, Non-Fiction, Horror, Historical Fiction, and Young Adult. Messages are paginated like book pages. Tap to turn.

**The Conservatory.** When two or more readers are reading the same book at the same time, a room blooms automatically. No one creates it. It simply appears, like wildflowers. When readers drift apart, the room fades. The Conservatory is where you find these rooms.

**Pen pal letters.** On devices that support drawing, you can be matched with another reader who shares your taste. Exchange handwritten ink letters drawn on your screen. Letters take hours to arrive, not because the network is slow, but because that is how letters work.

**Postcrossing.** Draw a letter and send it into the world. After you send one, you receive one from a different reader somewhere. Like postcrossing, but for people who read.

**The 24 Sekki.** Tomo follows the ancient Japanese calendar of 24 micro-seasons. The current season appears quietly on the home screen. On colour devices, the background shifts subtly through the year. You may never notice. That is the point.

## What it looks like

### Home screen

```
友 tomo                    春分 · Vernal equinox     [shelf]

READING NOW
Gods, Wasps and Stranglers
Mike Shanahan
─────────────────────────────────────────────
ROOMS
Fantasy & Sci-Fi
Romance
Literary Fiction
Thriller & Mystery
Non-Fiction
Horror
Historical Fiction
Young Adult
─────────────────────────────────────────────
Conservatory
─────────────────────────────────────────────
PEN PAL
Find a reader to write to
Send a letter to a stranger
Letters sent: 4 · Letters received: 0
Letters received
```

The home screen shows everything at a glance. The current sekki season sits in the header. Tap it for details. Tap any room name to enter it. Tap [shelf] to see your profile.

### Inside a genre room

```
← Fantasy & Sci-Fi                      Page 1 of 1

  driftwood42                           2 hours ago
  Started reading!

  quietshore                           yesterday
  The magic system in this one is so
  well thought out

  ─────────────────────────────────────
  Started reading! | Great point | Tell me more

  Write something...
```

Messages are paginated like book pages. Quick reply buttons sit below the messages for fast responses. Tap the text field to type your own message. Tap the back arrow to return home.

### Drawing a letter

```
← Letter to driftwood42

  ┌─────────────────────────────────┐
  │                                 │
  │     (your handwritten ink       │
  │      drawing appears here)      │
  │                                 │
  │                                 │
  └─────────────────────────────────┘

  ink · sepia · blue · rose · brown · green · plum · amber

                [Clear]    [Send]
```

On devices with a stylus, draw with the pen at 4px width. On touchscreen devices, draw with your finger at 8px width. The colour palette (washoku colours) appears on colour devices. On greyscale devices, you draw in black ink. Tap Send to seal the letter.

### The Conservatory

```
← Conservatory

         The conservatory is quiet.

    When two readers open the same book,
    a room blooms here, a space to share
    the experience of reading together.

    Rooms fade gently after seven days
    of stillness.
```

This is the empty state. When someone else is reading the same book as you, a room appears here automatically. No action needed. Just keep reading.

### The 24 Sekki

```
┌──────────────────────────────────┐
│                                  │
│         二十四節気                │
│                                  │
│         The 24 Sekki             │
│                                  │
│   Tomo follows the ancient       │
│   Japanese calendar of 24        │
│   micro-seasons, each marking    │
│   a shift in the natural world.  │
│                                  │
│   ──────────────────────────     │
│                                  │
│   Previous                       │
│   啓蟄 Keichitsu                 │
│   Insects awaken                 │
│   ~ March 5                      │
│                                  │
│   Current                        │
│   春分 Shunbun                   │
│   Vernal equinox                 │
│   ~ March 20                     │
│                                  │
│   Next                           │
│   清明 Seimei                    │
│   Pure brightness                │
│   ~ April 5                      │
│                                  │
└──────────────────────────────────┘
```

Tap the sekki greeting on the home screen to see this. Shows the previous, current, and next micro-season. Tap anywhere to dismiss.

### Settings

```
← Back

Tomo reads nothing you do not choose to share.

NOTIFICATIONS
While reading [off]
Pen pal letters [on]

READING
Share current book [on]

DISPLAY
Font size [small]
Message spacing [close]

ACCOUNT
Export my data
Leave Tomo

ABOUT
Tomo v2.7.3
友 (tomo) means "friend" in Japanese.
(c) 2026 James Edward Honiball
```

Tap [shelf] on the home screen, then [settings]. All sharing is opt-in. Export your data or leave Tomo at any time.

## Installation

### Before you begin

Tomo is a plugin for [KOReader](https://koreader.rocks/), an open source reading application for e-ink devices. It is not a standalone app. You need KOReader installed on your Kobo or Kindle before Tomo can run.

If you do not have KOReader yet, visit the [KOReader installation wiki](https://github.com/koreader/koreader/wiki) for step by step guides for your specific device. Installation takes a few minutes and does not modify your device permanently.

Requires KOReader 2024.07 or later.

### Steps

1. Download the latest release from the [Releases](https://github.com/Tokeloshe/tomo/releases) page.

2. Unzip it. You get a folder named `tomo.koplugin`. The name matters: it must be exactly `tomo.koplugin`. If your unzip tool wrapped it inside an outer folder, open that outer folder and use the `tomo.koplugin` folder from inside it.

3. Connect your e-reader to your computer with a USB cable. If the device asks, tap Connect. It appears on your computer as an ordinary USB drive, named `KOBOeReader` on Kobo or `Kindle` on Kindle.

4. On that drive, find KOReader's plugins folder:

   |  | Kobo | Kindle |
   | --- | --- | --- |
   | Windows | `H:\.adds\koreader\plugins\` | `H:\koreader\plugins\` |
   | Mac | `/Volumes/KOBOeReader/.adds/koreader/plugins/` | `/Volumes/Kindle/koreader/plugins/` |
   | Linux | `<mount point>/.adds/koreader/plugins/` | `<mount point>/koreader/plugins/` |

   On Windows the drive letter (`H:` in the examples) will be whatever your computer assigned. Look for the drive by name.

   Some guides write the Kobo path as `/mnt/onboard/.adds/koreader/plugins/`. That is the same place. `/mnt/onboard` is simply what the Kobo calls its own storage; from your computer, the USB drive itself is `/mnt/onboard`.

   If you cannot see the `.adds` folder, it is because Mac and Linux hide folders whose names start with a dot. In Finder, press `Cmd+Shift+.` to show hidden files. In most Linux file managers, press `Ctrl+H`. Windows shows the folder normally.

   You are in the right place when you see other folders whose names end in `.koplugin`.

5. Copy the whole `tomo.koplugin` folder into `plugins`.

6. Safely eject the drive, then restart KOReader. Exit it completely and open it again; putting the device to sleep is not a restart.

7. Open the top menu, go to the Tools tab (the wrench icon), and find Tomo.

You only need to do this once. From then on, Tomo updates itself over Wi-Fi.

### Quick install (Windows)

If you prefer, one PowerShell command does all of the steps above: it downloads the latest release, finds your connected e-reader on any drive letter, and installs the plugin. Connect your e-reader first, then paste this into PowerShell and press Enter:

```powershell
[Net.ServicePointManager]::SecurityProtocol='Tls12'; $v=Invoke-RestMethod 'https://raw.githubusercontent.com/Tokeloshe/tomo/main/version.json'; $tmp=Join-Path $env:TEMP 'tomo-install'; Remove-Item $tmp -Recurse -Force -ErrorAction SilentlyContinue; New-Item $tmp -ItemType Directory | Out-Null; Invoke-WebRequest $v.url -OutFile "$tmp\tomo.zip"; Expand-Archive "$tmp\tomo.zip" "$tmp\x" -Force; $src=Get-ChildItem "$tmp\x" -Recurse -Directory -Filter 'tomo.koplugin' | Select-Object -First 1; $dst=Get-PSDrive -PSProvider FileSystem | ForEach-Object { "$($_.Root).adds\koreader\plugins"; "$($_.Root)koreader\plugins" } | Where-Object { Test-Path $_ } | Select-Object -First 1; if(-not $src){ throw 'tomo.koplugin folder not found in the download.' }; if(-not $dst){ throw 'No connected e-reader with KOReader found. Connect it via USB, tap Connect on the device, and check KOReader is installed.' }; Remove-Item "$dst\tomo.koplugin" -Recurse -Force -ErrorAction SilentlyContinue; Copy-Item $src.FullName $dst -Recurse -Force; Remove-Item $tmp -Recurse -Force; Write-Host "Tomo v$($v.version) installed to $dst. Safely eject the drive, then fully restart KOReader."
```

When it finishes, safely eject the drive and restart KOReader. The same command also updates an existing install to the latest version.

### If Tomo does not appear

- **Check the second page of the Tools menu.** KOReader paginates its menus, and Tomo may be on page two.
- **Check the folder nesting.** The file `main.lua` must be at `plugins/tomo.koplugin/main.lua`. If it ended up at `plugins/tomo.koplugin/tomo.koplugin/main.lua`, move the inner folder up one level.
- **Check the folder name.** It must be exactly `tomo.koplugin`, not `tomo.koplugin-v2.7.3` or `tomo`.
- **Restart properly.** Exit KOReader fully and reopen it.

## Supported devices

Tomo works on any device that runs KOReader. What you can do depends on your hardware:

**Colour and stylus.** Full experience with handwritten colour ink letters. Kobo Libra Colour.

**Stylus.** Handwritten letters in greyscale. Kobo Sage, Elipsa, Elipsa 2E, Kindle Scribe.

**Colour, no stylus.** Draw letters with your finger, in colour. Kobo Clara Colour, Kindle ColorSoft.

**Touchscreen.** Draw letters with your finger. Kobo Clara HD, Clara BW, Clara 2E, Libra 2, Forma, Nia, and most Kindles.

**Older devices.** All social features work. Letters are typed instead of drawn. Kobo Touch, Glo, Glo HD, Aura, and older Kindles.

Tested and developed on a Kobo Libra Colour.

## Privacy

Tomo knows the minimum necessary about you.

Your device is identified by a one-way hash. Your reading progress stays on your device. Messages are visible only to members of the room. Ink letters are stored privately and visible only to the recipient.

There is no analytics. No telemetry. No third-party tracking. Crash reports contain only technical data (device model, error details) to help improve the app. No reading data, messages, or personal content is ever included.

## The seasons

Tomo is seasonally conscious. It follows Japan's 二十四節気 (nijushi sekki), the ancient calendar of 24 micro-seasons. Each lasts about fifteen days. The current sekki appears on the home screen, a quiet thread tying the digital to the physical world.

Tap the seasonal greeting to learn which sekki you are in, what came before, and what comes next.

---

Copyright (c) 2026 James Edward Honiball. All Rights Reserved.
