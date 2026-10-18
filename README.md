# Hunting Run — Gameplay19

[Play the mobile portrait prototype](https://wasiqnkhurshid.github.io/HuntingRunGame-WebGL/). Start → Boy/Girl → Play → Prototype Run → Start Run. No installation or account required.

Swipe left/right to change lane, up to jump, down to duck. Tap Shoot to begin a 180 ms draw. Current posture at launch determines release height: duck 0.45 m, standing 1.10 m, airborne 2.25 m. The physical arrow starts at the posed bow attachment. Movement remains independent; swipes on/across Shoot move, holding does not repeat, and independent fingers remain supported. Mouse/Enter shoot; A/D/arrows move, W/Space jumps, S ducks, Escape pauses.

Main economy: 10 starting arrows, 20 capacity, +2 pickups, 2.2-second cooldown between accepted taps. Accepted draws reserve an arrow; canceled/interrupted draws spend that reserved arrow. No experimental lab menus. 32 m/s, 90 seconds, Closer camera, 84 dp Shoot and 18 dp segmented gestures remain unchanged.

Starter bow: Range 40, Accuracy 50, speed 140 m/s, gravity 5 m/s². Effective range is 20 + 0.5 × Range metres. Beyond it, the same collidable arrow progressively loses momentum under linear drag 8/s and reaches terrain. Incidental animal hits remain valid during descent; extra travel is bounded. Actual swept collisions determine a single hit or stop. Existing nonviolent effects are preserved. Safety lifetime: 6 seconds.

Source **6431b61882c1dfff206521f83fbf941fcb8699a4**; finalized main integration based on Gameplay18. Existing main save key, schema and filesystem identity remain unchanged. Gameplay13–18 sites remain archived and unchanged. WebGL2/WebAssembly required. Physical Android/iPhone, Safari and sustained mobile performance still require device testing. A following camera may leave late descent behind the player; the arrow remains physically active.

## Rollback

**pre-gameplay19-main** preserves the exact previous main build. Restore that tag's tracked files into a new main commit and push, without force-pushing. The private source repository has the same rollback tag for its previous main source. Do not modify archived Gameplay13–18 deployments.
