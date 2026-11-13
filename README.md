# MK3D Online test builds

Test versions of [MK3D Online](https://github.com/Jstackzz/MK-3D-rollback)'s games. A test build changes a game to
try something out before it ever reaches everyone. It is not an update for MK3D Online: keep it in a folder of its own.

## Deadly Alliance test 19 (based on MK3D Online 1.0.4)

Download it from [Releases](https://github.com/Jstackzz/test-builds-/releases).

This test version has **no matchmaking** and never connects to the MK3D server. Train on your own, or play a friend
straight from your PC to theirs with **Direct match**: no server, no VPN.

New in test 19:

- **Every jukebox song loops as game music does, forever.** Its intro plays once, then its loop over and over, the way
  the original game played it: the launcher finds where each song comes back around in its soundtrack rip and makes
  the jump back seamless, and a rip's fade-out or silence at the end is never played. A song that never repeats runs
  to the end of its music and blends back into its beginning.
- From test 18: a song never plays over itself, and on a stage your song is the round music (the round-end sting and
  the "Finish him" music are the game's own). From test 17: the songs play as loud as the game's own music, the select
  screen plays your song from the start, and Deadly Alliance's Acid Bath never sprays acid. Test 19 plays copies of
  tests 17 and 18.

Also in it:

- **JUKEBOX**, like Tekken 8's, in all three games. Put each soundtrack in a folder of its own inside
  `Music\MK3D Jukebox` (m4a, mp3, wav or flac files). Pick what a game plays: its original music, a soundtrack as
  its preset (each stage gets the song that fits it best, the menus that game's menu and select-screen music) or
  shuffled (new songs each time the game starts), every soundtrack shuffled, or My Playlist 1, 2 or 3 with a song
  from any game for each stage, the main menu and the select screen, each to hear first. The soundtracks are listed
  in the order the games came out. Online only you hear your choice.
- **VERSUS** on the Single Player page: the two-player select screen with every fighter, costume and stage unlocked,
  player 2 on the controller you choose there.
- Older tests are still on the releases page.

Deception and Armageddon are the normal 1.0.4 games (only Deception's Yin Yang Island keeps its own music).

### Installing

1. Unzip it to a new folder of its own, not over your normal MK3D Online.
2. Start `MK3DLauncher.exe` there and point it at your games on BUILD GAME as usual (your own discs).
3. The first time, Deadly Alliance prepares its code (about a minute): let it finish.

It can sit beside your normal MK3D Online, and both can be open at once.

### Training

SINGLE PLAYER, then Practice.

### Direct match

1. Both of you pick the same game at the top.
2. One of you presses **HOST** and sends the code it shows to the other.
3. The other pastes the code and presses **JOIN**.
4. Pick your fighters on the game's own select screen. Rematches follow until one of you presses LEAVE or closes
   the game.

The host's rounds and death traps are played, and the larger input delay of the two.

If it doesn't connect:

- The first time, Windows asks whether to let MK3DLauncher and the game through its firewall: **allow it**, or
  hosting can't work.
- The host's router lets the game in by itself on most home networks (UPnP). If it doesn't, the joiner's launcher
  shows a **reply code** after a few seconds: send it to the host, who pastes it under "Friend's reply code" and
  presses USE.
- Still nothing: swap, and let the other one host. Two players who are both behind carrier-grade NAT (some phone and
  5G home internet) can't play this way.
- Both of you need this same test version: the launcher tells you when your friend's is different.

Each of you sees the other's IP address: it is what the code carries, as in any direct connection. To make the code,
the launcher asks a public STUN server (Google's or Cloudflare's) for your public address. The game uses UDP port 7101
(SETTINGS).

### Updates

A test copy never updates itself. New test versions are posted here.
