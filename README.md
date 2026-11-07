# MK3D Online test builds

Test versions of [MK3D Online](https://github.com/Jstackzz/MK-3D-rollback)'s games. A test build changes a game to
try something out before it ever reaches everyone. It is not an update for MK3D Online: keep it in a folder of its own.

## Deadly Alliance test 10 (based on MK3D Online 0.1.28)

Download it from [Releases](https://github.com/Jstackzz/test-builds-/releases).

This test version has **no matchmaking** and never connects to the MK3D server. Train on your own, or play a friend
straight from your PC to theirs with **Direct match**: no server, no VPN.

- **A fighter who has been knocked down can't block until they are back on their feet.** In the normal game, holding
  block while lying on the floor or landing from a knockdown blocks the next hit and stands you straight up.
- **Jax's string (2,2,LT, 4, back+2, back+2, 4,4,LT, tonfa swings) is much easier to land all the way through.** The
  kicks and tonfa swings reach further while the opponent is still reeling, and a button pressed right after LT waits
  for the style change instead of cancelling it.
- **The Throw / special button (BLACK) works as on the PS2 version:** no wait, its move can come out again as soon as
  the last one ends.
- **Scorpion's Hellfire reaches a little further from the spot it marks.** In the normal game a fighter getting up can
  slide just out of its reach for a few frames, so the same setup sometimes missed. Walking away still dodges it.
- **Bo' Rai Cho's Puke Puddle can come out again as soon as the last one is gone from the floor,** or as soon as a
  combo ends after someone slipped. In the normal game it stays locked for about a second after the puddle is gone, so
  the input comes out as a plain 2.
- **An attack over the puddle now slips:** a fighter kicking with a foot on the floor and their body over the puddle
  trades with it, instead of going right over it.

Test 10 replaces test 8. Deception and Armageddon are the normal 0.1.28 games. Test 10 plays only other copies of
test 10.

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
