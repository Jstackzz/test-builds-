# MK3D Online test builds

Test versions of [MK3D Online](https://github.com/Jstackzz/MK-3D-rollback)'s games. A test build changes a game to
try something out before it ever reaches everyone. It is not an update for MK3D Online: keep it in a folder of its own.

## Deadly Alliance test 4 (based on MK3D Online 0.1.20)

Download it from [Releases](https://github.com/Jstackzz/test-builds-/releases).

This test version has **no matchmaking** and never connects to the MK3D server. Train on your own, or play a friend
straight from your PC to theirs with **Direct match**: no server, no VPN.

### What changed in Deadly Alliance

Taking out the infinites:

- **Bo' Rai Cho:** the Puke Puddle (back, forward + 2) can't come out while the opponent is in a combo: from the first
  hit until they are back on their feet standing, walking, attacking or blocking. Being down or getting up after a knockdown
  counts, and so does slipping in a puddle. No more puddle as they get up, a hit while they slip, a knockdown, the
  puddle again. Against an opponent who isn't in a combo, the puddle works as before. *(Test 4: was 2 hits or more.)*
- **Drahmin:** the Ground Smash (back, down + 4) likewise can't come out while the opponent is in a combo, so it no
  longer stands a downed opponent back up for another combo. *(New in test 4.)*
- **Sonya:** the Kiss of Death (down, back + 1) can't come out while the opponent is in a combo of 9 hits or more, or
  is still down or getting up from one.
- **Frost:** a player knocked down by her slide (down, forward + 4) can tech roll when landing, by tapping up or down,
  like after other knockdowns.

Character select screen:

- A new background picture, and no fire along the bottom of the screen.

Deception and Armageddon are the normal 0.1.20 games.

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
