# Hunting Run — Gameplay Update09

[Play in a phone or desktop browser](https://wasiqnkhurshid.github.io/HuntingRunGame-WebGL/)

32 m/s for 90 seconds, Prototype08 Closer camera, and displacement-based touch input with held gesture chaining. Swipe to change lanes, jump or duck; tap Shoot. Keyboard: A/D or arrows, W/Space jumps, S ducks, Enter shoots, Escape pauses.

Shooting retains finite arrows and a 2.2-second cooldown. Control Lab remains available for isolated movement and shooting tests. Hunter V3 Prototype04 and Jungle Prototype06 artwork are preserved.

Source: `e587a92689d62436558be77ce2ac2c6dd401ec0f`. Build: `gameplay09-0.9.2` (Unity 6000.6.0f1 / URP / WebGL). This public repository contains compiled files only. Physical Android/iPhone feel and sustained performance still require device testing; browser checks used desktop Chrome touch simulation. WebGL haptics remain unavailable.

Profile saves are preserved. Older interruption snapshots are discarded because the speed changes the generated layout. Prototype08 saves remain isolated in their original database and its repository/history is retained.

## Rollback

Restore tag `pre-gameplay09-fdd96eb` into a new commit on main and push. This restores the previous Prototype07 files without rewriting history. The previous release is also retained at tag `prototype07-97e2e44`.
