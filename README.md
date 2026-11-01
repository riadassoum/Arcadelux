# Arcadelux

**An audio arcade built to be played by ear.**

Arcadelux brings reflex games, puzzles, sports, card games, cozy pastimes and simulation together in fifteen themed worlds. Track a moving target by its sound, land a spacecraft, solve a Sudoku, run a railway, fold a basket of laundry or chase a gold medal. Explore through spoken menus or walk an arcade floor where each cabinet calls out from its own place in the room.

Designed for blind and low-vision players, Arcadelux combines keyboard controls, screen-reader speech and braille, spatial audio and adjustable presentation. Alongside the arcade, you can restore and manage your own venue, build custom games in the Workshop, collect instruments to play, keep replays of your best runs, or join other players on a player-hosted server.

**Version:** 2.0.1  
**Developer:** Riad Assoum  
**Primary platform:** Windows

## Getting started

### Play the Windows release

1. Download a packaged Windows release from the [Arcadelux releases page](https://github.com/riadassoum/Arcadelux/releases).
2. Extract the entire archive to a folder where you have write permission. Keep the executable and its accompanying folders together.
3. Start your screen reader, if you use one, then launch `Arcadelux.exe`.
4. Open **Getting started** on the main menu for an introduction. Visit **Options** to choose your language, speech settings, sound engine and preferred controls.
5. Choose a cabinet, listen to its instructions and start playing. Use Practice or Spectator mode when you want to learn its sounds first.

The Windows release is ready to run and does not require Python or programming tools.

Stereo headphones are recommended: many games communicate direction, distance and movement through sound. Single-player play works offline; online multiplayer and downloading updates require a network connection.

## Explore the arcade

Each world groups cabinets around a different kind of play:

- **Rhythm Row:** timing, pitch and musical memory, including Beatstar, Count Them In and DJ Booth.
- **Neon Alley:** reflexes, racing and stereo tracking.
- **Classic Corner:** audio adaptations of Snake, Pong, Breakout, Space Invaders and other arcade favourites, with Pipe and Blast Chamber after Oriol Gómez's Arcade Room and BSC Games.
- **Deep Space:** flight, docking, orbital challenges and astronomy cabinets built around planetary and lunar calculations.
- **Puzzle Parlour:** Sudoku, Minesweeper, 2048, sliding puzzles, logic grids and other thinking games.
- **Carnival Row:** sideshow challenges, from coconut shies and ring tosses to claw machines and Musical Chairs.
- **The Night Shift:** sorting, dispatching, cooking and keeping services running under pressure.
- **Sound Lab:** listening challenges involving pitch, timbre, rhythm, direction and musical instruments.
- **Number Hall:** arithmetic, sequences, fractions and number puzzles with spoken questions.
- **Sports Arena:** athletics, swimming, bowling, pool, golf, football and other sporting events.
- **The Games Room:** cards, dice and board games, including Pig, Farkle, Hearts, Scopa, Reversi and backgammon.
- **The Great Outdoors:** foraging, farming, fishing, exploration and rescue challenges.
- **Parallel Universe:** overlapping dimensions, spatial puzzles and experiments in cause and effect.
- **Clockwork City:** railway dispatch, harbour operations, emergency response, assembly lines and power management.
- **The Cozy Corner:** gentle pastimes with nothing at stake — no clock and no game over — from folding laundry and cooking a Sunday lunch to tending a little garden, knitting a scarf or settling a cat to sleep.

Some cabinets are available immediately; others unlock through coins, levels or progression. Cabinet instructions explain the objective and controls. Where available, Hardcore changes the challenge and keeps separate records and medals. Press **D** on a cabinet's instructions screen to open its DIP-switch settings.

## More ways to play

### Challenges and local play

Play individual cabinets, work through a World Tour or take on modes such as Party Mode, Marathon, Boss Rush, Gauntlet and the sports Decathlon. Modes unlock as you progress.

Daily and Weekly Challenges use shared cabinet selections and layouts. Share a score code with other players and check their codes in the game. Daily missions, the hourly Hot Cabinet and visit streaks provide additional goals and rewards. Press **F6** at any time to hear the bonuses working for you now and the current Hot Cabinet.

**Party Night** supports up to eight people at one computer, taking turns with the keyboard or controller. Each player receives the same layout for a round.

**Practice Room** provides a place to learn without normal score and life pressure. **Spectator** lets you listen to the arcade demonstrate a cabinet.

### Replays, challenges and your story

Every time you set a new personal best, Arcadelux keeps the run as a **replay** — the layout its world was dealt and every key you pressed — and plays it back exactly as you played it, each sound in its place. Share a replay with other players, or copy a short **challenge code** that gives them your very layout and your score to beat. **Your Arcadelux story** is a letter the arcade writes you about how you play: your hours and games, the cabinet you could not leave alone, your home world and what you have collected.

### Arcade Owner

Restore an inherited arcade, reopen its halls and develop the business. Set prices, hire staff, maintain machines, fulfil visitors' requests and host events. Build improvements and renovations — a snack bar, a cafe, an ice-cream parlour, a bakery, a cinema — and, once they are built, treat yourself there with tickets. Longer-term progression includes tournaments, leagues, branches, seasonal activity and pages from the previous owner's diary.

### The Arcade Workshop

Create a cabinet from a template or build a Custom game using lanes, a grid or a ring of spatial sound. Define objects, movement, rules, counters and levels; choose sounds and music; then write the instructions and add your author name.

Workshop games can be shared as codes or files. Online servers also provide a Workshop shelf for exchanging creations.

### The Music Shop

Collect real instruments at the Ticket Booth — strings, flutes, reeds, brass, keys and drums, from the recorder and harmonica to the sitar, koto, darbuka and pipe organ. Hear one before you buy it, play any you own yourself (the arrows walk a scale in major, minor, pentatonic or the maqamat Rast, Bayati and Hijaz, and each arrow is a stroke of its own on the drums), and carry one with you so it plays a flourish whenever you win.

### Online multiplayer

Arcadelux uses player-hosted servers rather than a central matchmaking service. Join with an invite code, then enter a public or private room:

- **Race:** compete on the same cabinet and layout.
- **Party:** play a sequence drawn from the room host's unlocked cabinets.
- **Show:** listen to another player's game as it happens.
- **Tables:** play supported tabletop games against other players, turn by turn.

Hosting a server requires level 20 and 25 gold medals. Opening a room normally requires level 5; server owners can raise requirements and moderate their servers. The developer can authenticate with a signing key to receive a visible developer role with moderation powers; the key is private and is never part of the game, so the role cannot be forged.

A host must be reachable by the other players. The default server port is **TCP 47820**. The game can attempt automatic router port mapping; some networks require manual router or firewall configuration. An invite code alone does not guarantee that a server is reachable.

## Controls

These are the default keyboard controls. Individual cabinets may use additional keys, which are described in their instructions. Core controls can be reassigned in Options.

| Key | Action |
| --- | --- |
| Arrow keys | Navigate menus or move in a cabinet |
| Enter | Select or confirm |
| Space | Main game action |
| Escape | Go back or leave the current activity |
| P | Pause during play |
| T | Time remaining in a cabinet that is timed; the Arcade Clock once unlocked |
| F1 | Help |
| F2 | Game status |
| F3 or Ctrl+R | Repeat the last spoken message |
| F6 | Read the bonuses working for you now and the Hot Cabinet |
| Ctrl+K | Read the global shortcut list |
| Ctrl+L | Change language |
| Ctrl+S | Toggle speech |
| Ctrl+M | Toggle music |
| Page Up / Page Down | Adjust music volume |
| Ctrl+G | Toggle the Genny sound engine |
| Ctrl+V | Toggle self-voicing; paste when entering text |

### Cabinet lists

Mark a favourite with **period** and hide a cabinet with **comma**. Reorder cabinets or worlds with **Alt+Up/Down**. In long lists, **Left/Right** jumps ten entries at a time.

On a selected cabinet:

- **Shift+I:** read its instructions.
- **Shift+P:** enter Practice.
- **Shift+S:** enter Spectator.
- **Shift+H:** toggle Hardcore.
- **Shift+N:** toggle No Hints.

### Review buffers

Review spoken messages without leaving the current activity. Buffers separate game messages, menus, results, achievements and rewards, with additional status and volume buffers.

- **Ctrl+Left/Right:** change buffer.
- **Ctrl+Up/Down:** move through entries, or adjust a selected volume buffer.
- **Shift** with these navigation shortcuts: jump to the first or last item.
- **Ctrl+C:** copy the selected entry.

Bracket keys can also change buffers, and comma/period can move through entries. In cabinet lists, comma and period retain their hide and favourite functions.

### Controllers

Gamepad support includes menu navigation and game controls. By default, **A** selects and **B** goes back in menus. During play, **A** performs the main action, **Y** confirms, **Start** pauses and **Back** quits. Other buttons map to the cabinet's additional controls, and a right-stick click opens a number pad for cabinets that take typed numbers. Controller mappings can be adjusted in Options.

## Accessibility and languages

Arcadelux is designed around spoken information and audio cues. Menus, instructions, game status and results are available without relying on the visual display.

Speech and braille are provided through **Prism**, with support for Windows screen readers including NVDA and JAWS and system-voice fallback. Speech calibration helps align message timing with your reader. Genny self-voicing is also available in English and Spanish.

Visual settings include resizable presentation, text scaling up to 250 percent and colour themes including high contrast. Favourite, hidden, recent and unplayed cabinet lists help make the catalogue easier to navigate.

Language files are included for **English, Arabic, Simplified Chinese, French, Hungarian, Portuguese and Spanish**. Translation coverage varies by language and version. The game reports incomplete coverage and can generate a file of entries still needing translation.

To contribute a translation, work with the `.lng` files in the `Languages` folder. Translate the text to the right of each `=` while keeping the keys and named placeholders in braces unchanged. You can use the game's generated list of untranslated entries to identify missing text.

## Sound and music

Arcadelux generates much of its sound from oscillators, envelopes, filters and noise. Procedural music gives cabinets their own moods and tempos, while spatial processing communicates the position and movement of sound sources.

Sound options include:

- **Synthesis voices:** chip, analog, FM, acoustic and hybrid characters.
- **Genny:** Oriol Gómez Sentís's synthesiser, effects and announcer, bundled with permission.
- **Studio:** sampled instruments and drums from the GeneralUser GS SoundFont.
- **Unlockable effect banks and music styles:** alternative sound palettes earned through play.

Some themes are rendered in advance for immediate playback. Studio uses recorded instrument samples, so the game combines real-time synthesis with prepared and sample-based audio.

## Progress and backups

Earn experience, coins, tickets and gems; unlock cabinets and modes; collect prizes and instruments; and pursue bronze, silver and gold medals. Achievements and the completion tracker provide longer-term goals alongside personal bests and Hardcore records. Up to five save slots let you keep several arcades side by side, each with its own progress.

Use **Options** to back up or restore your progress. The normal portable save location is `savedata/profile.dat` beside the game. When moving a portable copy, preserve its `savedata` folder. A fresh installation can also offer to import progress it finds from a previous copy.

Back up your progress before replacing an installation or restoring an older save.

## Troubleshooting and bug reports

### No speech or unexpected speech behaviour

Check that speech is enabled with **Ctrl+S**, verify the selected speech settings in Options and confirm that your screen reader is running. Use speech calibration if messages are being interrupted or leave long pauses.

### Missing audio or unclear positioning

Check your output device and the game's volume settings. Make sure your headphones are connected in stereo and that left and right channels are the right way round. Try another sound engine to help identify whether the problem is specific to one engine.

### Diagnostic report

From a command prompt in the game folder, run:

```bat
Arcadelux.exe --diagnose
```

This writes `diagnose.txt` beside the program with version, speech and audio information.

Report problems through the [project issue tracker](https://github.com/riadassoum/Arcadelux/issues). Include the game version, Windows version, screen reader, selected sound engine, affected cabinet or mode, and the steps needed to reproduce the problem. Describe what you expected and what actually happened, and attach the diagnostic report when relevant. Review logs before sharing them publicly.

## Credits

**Design, code, music and sound design:** Riad Assoum.

**Development assistance:** portions of the engineering — game balancing, localisation tooling, test harnesses and refactoring — were carried out with the assistance of Claude, an AI assistant by Anthropic, working under the author's direction.

**Technologies and resources:**

- **Python**, with **NumPy** for real-time waveform synthesis and **pygame** for audio playback and input.
- The binaural elevation cues are informed by the **MIT KEMAR** head-related transfer function measurements (Gardner & Martin, 1994).
- Breakout, Snake (COIL), Pong, Space Invaders, Asteroids, Missile Command, Tennis, Math Star, Beatstar (Dynamic Beatstar) and Pipe are ports of games from [Oriol Gómez's Arcade Room](https://github.com/ogomez92/arcade_room), released into the public domain, with thanks.
- Blast Chamber is an original cabinet after **Blast Chamber (Pipe 2)** by **BSC Games**, whose game mechanics have long been public; its story, names and sound are Arcadelux's own.
- [Genny](https://github.com/ogomez92/genny), Oriol Gómez Sentís's synthesiser and voice, is bundled with his kind permission.
- [Maqamusic](https://github.com/riadassoum/maqamusic), my maqam keyboard for NVDA, gives the arcade its maqamat, their quarter tones and its iqa'at: Name the Maqam, Quarter Tone, Iqa Echo, the maqam themes, the piano's maqam mode and the Music Shop's scales.
- [BASS and BASSMIDI](https://www.un4seen.com/) by Un4seen Developments, free for non-commercial use, play the Studio engine's SoundFont when present (arcadelux/native).
- [GeneralUser GS](https://www.schristiancollins.com/generaluser) by S. Christian Collins, a SoundFont free to use in software, gives the Studio engine and the Music Shop their instruments (licence in arcadelux/STUDIO_LICENSE.txt).
- The Sports Arena, Bowling, Table Tennis, the real Pool table, flights you can hear, controller remapping, the Music Shop's collectable instruments, 2048, the Escopa variation of Scopa and much more were suggested by **KenshiraTheTrinity**; the Cozy Corner of relaxing games by **Adina** and **aziz1media**; Gator Bop by **Quasar**; and Just One More and Lost and Found by **germanico**, all of the audiogames.net community.
- Twenty-four cabinets new in 1.6 (Boxing, Slalom, Ice Hockey, Street Ball, Gridiron, Depth Charge, Bombs Away, Orbit, The Matador, Rock Paper Beat, Hammurabi, Awari, The Tower, Hexapawn, Hunt the Hurkle, Kinema, Acey Ducey, Splat, Gomoko, Chomp, Reverse, Mugwump, Be Random and Bouncing Ball) are rebuilt for the ear from games in **David H. Ahl's BASIC Computer Games**, as kept in the public domain by the **coding-horror/basic-computer-games** project under the Unlicense.
- Minesweeper, Codebreaker, Bowling, Spot The Sound, Statues, The Throw, Mystery Boxes, Mirror Image, Key Cutter, Make Change, The Nail, Valve Room, Traffic Count, Railroad, Rolling Die, Sundial, Axe Throw, Guess the Number, Pitch Sort, Cursed Doors, Launch Control, Checkpoint and Tree Scout are adapted from ideas in **Crazy Party** by Pragma; all code, sound and text are Arcadelux's own.
- The Cozy Corner's kitchen cabinets reuse the cooking engine of **Culinary Horizons**, the author's own unfinished kitchen game, rebuilt on Arcadelux's sounds.
- Portuguese translation by **JP**, Simplified Chinese translation by **nicotomia**, and Hungarian translation by **arnold18**, all of the audiogames.net community.
- Screen-reader speech and braille via **Prism** (Ethin Probst), which includes the NVDA controller client and covers every major reader and the system voices.

## Copyright and third-party licences

Copyright © 2026 Riad Assoum. All rights reserved.

Bundled third-party code, libraries and assets remain subject to their respective licences and permissions. See [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md), `arcadelux_vendor/licenses/`, `arcadelux/STUDIO_LICENSE.txt`, `arcadelux/HIJRI_LICENSE.txt` and `genny/PERMISSION.txt`.

Arcadelux is closed-source. The player release contains no source code: it is compiled to native code, and may not be copied, decompiled, republished or presented as anyone else's. Third-party licences apply to their respective components and do not grant rights to Arcadelux as a whole.
