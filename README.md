# MK3D Online test builds

Test versions of [MK3D Online](https://github.com/Jstackzz/MK-3D-rollback)'s games. A test build changes a game to
try something out before it ever reaches everyone. It is not an update for MK3D Online: keep it in a folder of its own.

## Test 23 (MK3D Online 1.0.13)

Download it from [Releases](https://github.com/Jstackzz/test-builds-/releases).

This test version has **no matchmaking** and never connects to the MK3D server. Train on your own, or play a friend
straight from your PC to theirs with **Direct match**: no server, no VPN. All three games are in it.

New in test 23, Deadly Alliance's costumes:

- **A third costume for four fighters.** On the select screen, hold **LT** (L2 on a PlayStation controller) and press **X** (Square) instead of A: RAIDEN in red and white; SCORPION in black and yellow (yellow mask, yellow trim along his gi, gold studs, yellow rims on his gear); BO' RAI CHO with a navy vest and sleeves, a mustard sash and black pants; JAX with a red vest, red boxing gloves, black pants, a black beret and red bands on his boots (on his own model: the same reach and collision as ever). A still picks the first costume and START the second, LT with either giving that costume's other colours.
- **RAIDEN's first costume is a deeper, royal blue** (it was teal): in fights, on the select screen and in every mode.
- Two players picking the same fighter's costume 3: the second gets its other colours (RAIDEN in black, SCORPION in white and yellow with the plates round the skulls on his thighs black), or the fighter's regular alternate outfit for BO' RAI CHO and JAX. One in costume 3 and the other in the fighter's first costume both keep theirs.
- The costumes are made on your PC from your own game files when Deadly Alliance starts (in `games\mkda\costumes`); nothing from the disc comes with the download. On the select screen costume 3 shows the first costume's picture.
- The three games are MK3D Online 1.0.13's, Deadly Alliance with the costumes. Test 23 plays only other copies of
  test 23.

Also in it:

- From test 21: Finish Him music for the old Mortal Kombat songs (a soundtrack's `Finish Him` folder), and the
  **FINISH HIM** jukebox track.
- **JUKEBOX**, like Tekken 8's, in all three games. Put each soundtrack in a folder of its own inside
  `Music\MK3D Jukebox` (m4a, mp3, wav or flac files). Pick what a game plays: its original music, a soundtrack as
  its preset or shuffled, every soundtrack shuffled, or My Playlist 1, 2 or 3 with a song from any game for each
  stage, the main menu, the select screen, Finish Him and the fatality. Online only you hear your choice.
- From test 20: tech rolls in practice (**F6**), the other colours of a costume (hold **LT** while you pick a
  fighter) and the **SOUND** settings.
- **VERSUS** on the Single Player page: the two-player select screen with every fighter, costume and stage unlocked,
  player 2 on the controller you choose there.
- Older tests are still on the releases page.

### Installing

1. Unzip it to a new folder of its own, not over your normal MK3D Online (over test 17 to 22 is fine: your settings
   and playlists stay).
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
4. Pick your fighters on the game's own select screen (LT and X for costume 3). Rematches follow until one of you
   presses LEAVE or closes the game.

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
