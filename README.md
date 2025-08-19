# pomegranate
Releases for https://git.sr.ht/~sheepy/pomegranate


## Latest release QR code
Scan this with FBI!!

<img width="164" height="164" alt="image" src="https://github.com/user-attachments/assets/16e9d901-16f0-47a3-a712-a46ec2d76d8a" />

## Images

<img width="400" height="480" alt="playing" src="https://github.com/user-attachments/assets/44484cdd-5d04-4b8f-bd01-9c30fd82f315" />


<img width="400" height="480" alt="menu" src="https://github.com/user-attachments/assets/9c96906c-3531-4aa0-b19e-eb7bfe12d689" />

## Features

- [x] Audio playback
    - [x] flac
    - [x] mp3
    - [x] m4a
    - [x] Pausing
    - [x] Seeking
- [x] Track metadata
- [x] Album art
    - [x] From metadata
    - [x] From indexing
- [ ] Bumper controls
    - [x] Pause/play
    - [ ] Next / previous
- [ ] Playlists
    - [x] Enqueuing songs
    - [ ] Loop
    - [ ] Shuffle
- [x] Music organization
    - [x] Folder-based navigation
    - [x] Metadata-based indexing navigation
- [x] Cool UI

---
## Usage

### Indexing

Indexing organizes your music by artist -> album -> tracks by looking at the metadata of every file recursively from your selected root directory.

To get started:
- go to the settings menu,
- choose a music library folder,
- go to the the CD menu,
- scroll to the bottom,
- and press "reindex."

This process *will* take quite a bit of time (~1-5 sec/song, depending on the format!).

### Bumper controls

| Input               | Action              |
| ------------------- | ------------------- |
| double (2x) tap R   | pause or play       |
| double (2x) tap L   | stop playback       |
| triple (3x) tap R   | next song           |
| triple (3x) tap L   | previous song       |

---

## Credits

### Backgrounds

- Pomegranate sheep: Commission from [DOOMVEGA](https://doomvega.art/) ([KoFi](https://ko-fi.com/doomvxga/commissions))
- Cartoon sky: [source](https://www.freepik.com/free-vector/valentine-theme-with-hearts-pink-sky_6550809.htm)
- Clouds 95: Windows 95 wallpaper, [source](https://archive.is/csDCl)

### Icons

- CD, CD case, folder, & cog: Strawberry, GPL-3.0 [source](https://github.com/strawberrymusicplayer/strawberry/tree/master/data/icons)
- Pomegranate fruit: adapted from Ivar Leidus, CC BY-SA 4.0 [source](https://commons.wikimedia.org/wiki/File:Pomegranate_fruit_-_whole_and_piece_with_arils.jpg)
- Battery, volume, clock: Micro Heroicons, MIT [source](https://heroicons.com/micro)


### Audio

- Banner audio: Cipher by Kevin MacLeod, [source](https://www.incompetech.com/music/royalty-free/index.html?isrc=usuan1100844)

---

## Building

Please see https://git.sr.ht/~sheepy/pomegranate/#building for building instructions.
