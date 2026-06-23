# Osu64
Demake of Osu!mania 4k for the Nintendo 64. This project isn't affiliated with Nintendo or Ppy.

---

[![Gameplay Presentation](https://img.youtube.com/vi/9iPliT3w0Cg/0.jpg)](https://www.youtube.com/watch?v=9iPliT3w0Cg)
[![Update Presentation](https://img.youtube.com/vi/UstAvXwbtPM/0.jpg)](https://www.youtube.com/watch?v=UstAvXwbtPM)
---

Osu64 is a native 4K rhythm game demake of *osu!mania*, developed for the Nintendo 64 console. This project is built using the open-source **Libdragon** SDK and compiles into a standard `.z64` ROM compatible with both emulator and real hardware.

---

## Technical Features (v1.4)

*   **Audio-Buffered Synchronization:** Note scrolling is synchronized directly with the console's DMA audio buffer. This eliminates audio-video drift and guarantees consistent timing regardless of frame rate fluctuations.
*   **PAL & NTSC Compatibility:** The audio-buffered sync allows the game to run at its native speed on both 60Hz NTSC (JAP/US) and 50Hz PAL (EU) systems. On PAL hardware, the game renders at 50 FPS while keeping identical musical timing.
*   **Optimized ROM Footprint:** The compiled ROM size has been optimized down to **19.9 MB (160 Megabits)**, housing 19 playable tracks with high-quality compressed audio and custom textures.
*   **Visual Enhancements:** Implemented dynamic camera tilt effects triggered by key presses, star particle bursts on hit, and a dedicated options screen supporting both "Circles" and "Bars" skins.

---

## Controls & Keybindings

Osu64 is designed to be played with a standard Nintendo 64 controller. The 4K gameplay layout is mapped symmetrically across the controller:

| Gameplay Lane | N64 Controller Input |
| :--- | :--- |
| **Lane 1 (Far Left)** | **L-Button** (Left Shoulder) |
| **Lane 2 (Mid Left)** | **D-Pad Down** |
| **Lane 3 (Mid Right)** | **A-Button** |
| **Lane 4 (Far Right)** | **R-Button** (Right Shoulder) |

### Menu Navigation:
*   **Analog Stick / D-Pad:** Navigate menus
*   **A-Button:** Select / Confirm / Calibrate
*   **B-Button:** Go back / Return to Title Screen
*   **Start-Button:** View Credits (from Title Screen)
*   **Z-Button:** Access Settings / Offset Sync (from Title Screen)
*   **L + R + Analog Stick Up:** Secret code (Title Screen)

---

## Open Source Status & Distribution

Please note that **Osu64 is not open-source.** The source code is not publicly available, and this repository is used solely for ROM distribution, documentation, tracking issues, and managing community feedback. 

This decision was made due to two primary factors:
1.  **Content Management & Licensing:** Because this project utilizes custom-converted community beatmaps and music, keeping the distribution centralized in a single compiled ROM allows me (the dev) to quickly and efficiently handle any takedown, modification, or credit requests from original mappers and artists without managing public forks or branches.
2.  **Personal Preference:** As a solo hobbyist developer, I prefer to keep the raw codebase private at this stage of development. 

I thank you for your understanding. The compiled `.z64` ROM remains, and will always remain, 100% free to download and play.

---

## Compatibility Notes

### Emulators
*   **Project64 is NOT supported.** High-level emulators cannot properly run ROMs compiled with modern versions of the Libdragon SDK.
*   It's officially recommended using low-level emulators such as **Ares** or **Gopher64** for a stable 60 FPS (NTSC) experience on PC.

### Real Hardware
*   The ROM is fully compatible with real Nintendo 64 hardware.
*   It can be run using modern flashcarts such as the **SummerCart64** or **EverDrive 64** on NTSC, NTSC-J, and PAL consoles.

---

## Song List & Credits

Osu64 features custom-converted 4K charts. All credits for the original note placements go to the following mappers from the *osu!* community:

| Song Title | Original Artist | osu!mania Beatmapper |
| :--- | :--- | :--- |
| **Doodle** | Zachz Winner | *nixii cant acc* |
| **Nani ga Warui** | Bocchi the Rock! | *Begin* |
| **Night of Knights** | beatmario | *alocat* |
| **Otsukimi** | t-pazolite & nanahira | *[TCD]Dzar03* |
| **Pokkan Color** | Kikuo | *fvrex* |
| **Pumpin' Junkies** | t-pazolite | *Draftnell* |
| **Tengu Man** | Capcom Sound Team | *Pereira006* |
| **Senpai, Notice Me** | Camellia & Nanahira | *SaltyLucario* |
| **Sugar Loli** | Slax | *NikoSek* |
| **Delta Dan** | Various Artists | *Res_ett* |
| **Triple Baka** | Hatsune Miku | *Quick Draw* |
| **Playing with Ruby** | NIWASHI | *Down* |
| **Never Gonna Give You Up** | Rick Astley | *Flade* |
| **Timeless** | Remeses B | *Alacat* |
| **More! Jump! More!** | Hatsune Miku | *Yuiazu* |
| **Unravel** | Ado (Cover) | *Scotty* |
| **Blue Zenith** | xi | *Famoss* |
| **Happy End of the World** | xi | *Fullerene* |
| **Freedom Dive** | xi | *Gluenshurtlyn* |

---

## Takedown Policy

Osu64 is a non-profit fan project. If you are the original creator or mapper of any asset, music track, or chart featured in this ROM and want your content removed, please contact me by opening an issue on this repository or on discord at `neo_luigi`. I will immediately remove your assets in the next revision.
