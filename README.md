# MK3D Online test builds

Test versions of [MK3D Online](https://github.com/Jstackzz/MK-3D-rollback)'s games. A test build changes a game to
try something out before it ever reaches everyone. It is not an update for MK3D Online: keep it in a folder of its own.

## Test 21 (MK3D Online 1.0.10)

Download it from [Releases](https://github.com/Jstackzz/test-builds-/releases).

This test version has **no matchmaking** and never connects to the MK3D server. Train on your own, or play a friend
straight from your PC to theirs with **Direct match**: no server, no VPN. All three games are in it.

New in test 21:

- **Finish Him music for the old Mortal Kombat songs.** When a stage plays a song from MK1, MK II, MK3, UMK3 or MK4
  whose finish theme you have, the fight's Finish Him plays that song's own finish him music (MK II's Dead Pool on a
  stage, then The Dead Pool's finish theme), then the game's own sting as the round ends. In all three games, in your
  playlists, a soundtrack's preset and a shuffle. The JUKEBOX marks such a song "+ finish him"; the FINISH HIM track's
  song plays on the stages whose song has none.
- **Where the finish music goes**: a folder called `Finish Him` inside the soundtrack's folder (for example
  `Music\MK3D Jukebox\mk2\Finish Him`), each file named after its stage as game rips name them: "The Dead Pool
  Finish Theme", "Wasteland Finish Theme, The Pit II Finish Theme", "The Well (Finish Him)", "The Temple Gate - Loop".
  "The", Roman numerals and a plural s don't matter. Where the names don't match, a soundtrack.json can name it
  (`"finish": "Finish Him/<file>"`).
- Short finish themes loop on their phrase, without the rip's fade.
- The **FINISH HIM** jukebox track (one song for every stage's Finish Him) is in the test version now too.
- The three games are MK3D Online 1.0.10's. Test 21 plays only other copies of test 21.

Also in it:

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

1. Unzip it to a new folder of its own, not over your normal MK3D Online (over test 17 to 20 is fine: your settings
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
