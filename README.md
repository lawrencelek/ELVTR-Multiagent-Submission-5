# DUMMIES — Prototype 6.10

**27 October 2026 · Lawrence Lek** · ELVTR Multi-Agent, Submission 5. Spec: GDD Edit 80.

- **Play:** https://lawrencelek.github.io/ELVTR-Multiagent-Submission-5/
- **Jump test:** https://lawrencelek.github.io/ELVTR-Multiagent-Submission-5/jump/
- **Control test:** https://lawrencelek.github.io/ELVTR-Multiagent-Submission-5/controls/
- Plain web pages: gamepads, touch and keys all work. Claude's hosted preview blocks gamepads.
- **Source:** [lawrencelek/ELVTR-dummies-agent-crew](https://github.com/lawrencelek/ELVTR-dummies-agent-crew/tree/assignment4/content-pipeline/prototypes), `p6/`, `jump/`, `controls/`.

## Files

- `index.html`: the game. Three districts: Parkland, Waterfront, Monument. One file; no server.
- `jump/index.html`: the jump test yard. Moving traffic, parked cars, barriers, a ruler, a side view of each jump.
- `controls/index.html`: the control test yard. Pads, touch, keys; three turn models.

## Controls

| | Keys | Gamepad | Touch (phones and tablets, landscape) | Unlocked by |
|---|---|---|---|---|
| Move | WASD / arrows | stick or d-pad | analog stick, left | — |
| Dash | SPACE or K | A (or RT) | A | start; Battery recharges it faster |
| Jump | L or SHIFT | B | B | Legs 1 |
| Pick up a cone | J or E, tap | X, tap | X, tap | Hands 1 (one cone), Hands 2 (two) |
| Put a cone down | J or E, hold 0.3 s | X, hold | X, hold | Hands 1 |
| Push off a car | I or Q, after a hit or beside a car | Y | Y | Arms 1 |
| Pause | ESC or P | START | ❚❚ PAUSE | — |
| Pad setup | G | hold START | — | — |

- Touch controls show only on touch screens. Add `#touch` to the address to force them.
- Press any button on a gamepad first: browsers list a pad only after a press.
- Pad without a standard mapping: press G, then DASH, JUMP, GRAB, PUSH in turn.
- The shop opens after each write-off. Tuning (T, desktop) installs ability levels for a test run.

## What 6.10 adds

- Hands (X), two levels: tap to pick up a cone, hold 0.3 s to put it down. Hands 1 carries one cone, Hands 2 two. No throw.
- Arms (Y), three levels: push off a car you just hit or touch, a ricochet you time.
  - Push: +160, +200, +240 u/s. Pushes before landing: 1, 2, 3. They refill on the ground.
  - Dash into a car, push off it into the next: a two-kind combo, ×2.
- With no Arms, the bounce off a car stays the Newtonian one.
- The throw, the hitch and the cone link are gone. Tuning (T) has every push value.

## 6.9

- Three abilities, three levels: Battery (dash charge 1 s, then 0.8, 0.7, 0.6), Legs (0.3, 0.4, 0.5 s in the air), Arms (carry, hold X to throw, hitch).
- Hitch: grab a passing car, ride it, let go at its speed, or sling off with A into the next car.
- Combos: mixing moves climbs faster (to ×5); jumps, bounces, slings and hitches hold the combo clock; a thrown cone into a car links; a meter shows the chain.
- Every value is in Tuning (T).

## 6.8

- Four levels per ability. Legs: 0.3 to 0.6 s in the air. Arms: carry 1 to 4 cones. Throw: +40 range a level. Battery: −0.1 s a charge a level.
- The shop shows one card per ability; A buys its next level.
- Hits bounce the dummy with Newtonian momentum: a head-on hit throws it far, into the next car for a combo. Tune it in Tuning (T).
- Jump test: [ and ] change the Legs level.

## 6.7

- The shop sells four abilities, one per button, three levels each: Battery (A), Legs (B), Arms (X), Throw (Y).
- Level 1 gives the ability. Every level cuts how much damage wears it, 25% a level.
- Battery levels speed the dash recharge: 0.8 s a charge, down to 0.41 s. Torso damage slows it.
- Walk and jump: a hop, it clears nothing. Run and jump to clear.
- Jump test: diagonal jumps. A running jump clears a handrail to 55° off square, a sedan to 32°.

## 6.6

- The screen fills the window at any scale, not only ×2 or ×3.
- Touch controls only on phones and tablets, drawn in the HUD's glass style.
- The jump keeps its take-off speed (Link's Awakening): standing 0, walking 41, running 81. B during a dash: a long jump, 162.
- A running jump clears a sedan broadside; a dash jump clears a van. A bus: never.
- Fixed: the dummy froze dashing past a stair head onto a walkway (Monument B2).
