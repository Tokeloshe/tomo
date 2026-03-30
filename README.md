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
│   ────────────────────────     │
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
Tomo v2.6.0
友 (tomo) means "friend" in Japanese.
(c) 2026 James Edward Honiball
```

Tap [shelf] on the home screen, then [settings]. All sharing is opt-in. Export your data or leave Tomo at any time.

## Installation

1. Download the latest release from the [Releases](https://github.com/Tokeloshe/tomo/releases) page
2. Unzip it to get the tomo.koplugin folder
3. Connect your e-reader via USB
4. Copy tomo.koplugin into /mnt/onboard/.adds/koreader/plugins/
5. Restart KOReader
6. Open the menu and find Tomo under Tools

Requires KOReader 2025.10 or later.

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
