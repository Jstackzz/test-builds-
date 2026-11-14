# MK3D Online test builds

Test versions of [MK3D Online](https://github.com/Jstackzz/MK-3D-rollback)'s games. A test build changes a game to
try something out before it ever reaches everyone. It is not an update for MK3D Online: keep it in a folder of its own.

## Test 20 (MK3D Online 1.0.7)

Download it from [Releases](https://github.com/Jstackzz/test-builds-/releases).

This test version has **no matchmaking** and never connects to the MK3D server. Train on your own, or play a friend
straight from your PC to theirs with **Direct match**: no server, no VPN. All three games are in it.

New in test 20:

- **Tech rolls in practice.** Press **F6** in a practice fight to make the dummy tech roll when you knock it down: up,
  then down, then back (away from you), then one of the three at random, then not at all again. It is the game's own
  roll, as a player holding that direction as they land. F8 still makes the dummy block.
- **The other colours of a costume.** Hold **LT** (L1) while you pick a fighter: LT and A for the first costume's
  other colours, LT and START for the second costume's. Your opponent sees them too. When both players end up with
  the same fighter in the same costume and colours, player 2 gets the other colours.
- **SOUND settings**: sliders for the master volume, music, sound effects, fighter voices, announcer and the arenas'
  own sounds. 100 % is each game as it sounds on its own; the master goes louder than the games themselves.
- **Fatality track** in the jukebox for Deadly Alliance and Deception: pick a song for it in a playlist like any
  stage; a soundtrack's preset or a shuffle gives it MK1's, MK2's or MKX's fatality song. Your playlists stay as they
  were.
- The three games play as the next MK3D Online update will have them: Deadly Alliance is the normal game now, not the
  test version of tests 14 to 19. Test 20 plays only other copies of test 20.

Also in it:

- **JUKEBOX**, like Tekken 8's, in all three games. Put each soundtrack in a folder of its own inside
  `Music\MK3D Jukebox` (m4a, mp3, wav or flac files). Pick what a game plays: its original music, a soundtrack as
  its preset or shuffled, every soundtrack shuffled, or My Playlist 1, 2 or 3 with a song from any game for each
  stage, the main menu, the select screen and the fatality. Online only you hear your choice.
- **VERSUS** on the Single Player page: the two-player select screen with every fighter, costume and stage unlocked,
  player 2 on the controller you choose there.
- Older tests are still on the releases page.

### Installing

1. Unzip it to a new folder of its own, not over your normal MK3D Online (over test 17, 18 or 19 is fine: your
   settings and playlists stay).
2. Start `MK3DLauncher.exe` there and point it at your games on BUILD GAME as usual (your own discs). A game the
   folder never had needs BUILD GAME once.
3. The first time, each game prepares its code (about a minute): let it finish.

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
