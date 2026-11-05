# MK3D Online test builds

Test versions of [MK3D Online](https://github.com/Jstackzz/MK-3D-rollback)'s games. A test build changes a game to
try something out before it ever reaches everyone. It is not an update for MK3D Online: keep it in a folder of its own.

## Deadly Alliance test 5 (based on MK3D Online 0.1.25)

Download it from [Releases](https://github.com/Jstackzz/test-builds-/releases).

This test version has **no matchmaking** and never connects to the MK3D server. Train on your own, or play a friend
straight from your PC to theirs with **Direct match**: no server, no VPN.

### What changed in Deadly Alliance

The block lock comes three frames later. If you are still holding block when the attacker's next hit in a string
starts, the game locks you in block until that hit lands: your buttons do nothing, and if you let go meanwhile, block
drops just before the hit and it lands in full. In this test the lock starts three frames later, so there is more time
to let go of block and interrupt a string.

On Hsu Hao's 1,1,2 and Jax's 2,2,LT, counting frames from the second hit being blocked:

| | Normal game | Test 5 |
|---|---|---|
| Let go of block | +0 to +3 (4 frames) | +0 to +6 (7 frames) |
| Let go later than that | Locked, the third hit lands in full | Same |
| Latest press, Bo' Rai Cho's 2 | +7 | Same |
| Latest press, Hsu Hao's 1 | +9 | Same |
| Keep holding block | You block the third hit | Same |

- Press at least one frame after you let go.
- If the attacker's third button comes too late, there is no third hit and no lock, as before.
- Letting go also frees you to do anything else in those frames, not only attack.
- It applies to every fighter's strings. Other strings have their own numbers, as the lock comes when their next hit
  starts. A fighter the computer plays is as it always was.

Everything else in Deadly Alliance is the normal 0.1.25 game, with its lag fixes and its rules against infinites. Test
5 replaces test 4: test 4's select screen picture is gone, as in the normal game. Deception and Armageddon are the
normal 0.1.25 games. Test 5 plays only other copies of test 5.

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
