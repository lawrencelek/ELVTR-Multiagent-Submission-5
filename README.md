# DUMMIES — Prototype 7.8

**28 October 2026 · Lawrence Lek** · ELVTR Multi-Agent, Submission 5. Spec: GDD Edit 89.

- **Play:** https://lawrencelek.github.io/ELVTR-Multiagent-Submission-5/
- **Jump test:** https://lawrencelek.github.io/ELVTR-Multiagent-Submission-5/jump/
- **Control test:** https://lawrencelek.github.io/ELVTR-Multiagent-Submission-5/controls/
- **Prototype 7.7:** https://lawrencelek.github.io/ELVTR-Multiagent-Submission-5/p7-7/
- **Prototype 7.6:** https://lawrencelek.github.io/ELVTR-Multiagent-Submission-5/p7-6/
- **Prototype 7.5:** https://lawrencelek.github.io/ELVTR-Multiagent-Submission-5/p7-5/
- **Prototype 7.4:** https://lawrencelek.github.io/ELVTR-Multiagent-Submission-5/p7-4/
- **Prototype 7.3:** https://lawrencelek.github.io/ELVTR-Multiagent-Submission-5/p7-3/
- **Prototype 7.2:** https://lawrencelek.github.io/ELVTR-Multiagent-Submission-5/p7-2/
- **Prototype 7.1:** https://lawrencelek.github.io/ELVTR-Multiagent-Submission-5/p7-1/
- **Prototype 7 (before 7.1's economy):** https://lawrencelek.github.io/ELVTR-Multiagent-Submission-5/p7/
- **Prototype 6.10 (before the modes):** https://lawrencelek.github.io/ELVTR-Multiagent-Submission-5/p6-10/
- Plain web pages: gamepads, touch and keys all work. Claude's hosted preview blocks gamepads.
- **Source:** [lawrencelek/ELVTR-dummies-agent-crew](https://github.com/lawrencelek/ELVTR-dummies-agent-crew/tree/assignment4/content-pipeline/prototypes), `p7/`, `p6/`, `jump/`, `controls/`.

## Files

- `index.html`: the game, Prototype 7.8. Arcade and Story. One file; no server.
- `p7-7/index.html`: Prototype 7.7, frozen.
- `p7-6/index.html`: Prototype 7.6, frozen.
- `p7-5/index.html`: Prototype 7.5, frozen.
- `p7-4/index.html`: Prototype 7.4, frozen.
- `p7-3/index.html`: Prototype 7.3, frozen.
- `p7-2/index.html`: Prototype 7.2, frozen.
- `p7-1/index.html`: Prototype 7.1, frozen.
- `p7/index.html`: Prototype 7, frozen.
- `p6-10/index.html`: Prototype 6.10, frozen.
- `jump/index.html`: the jump test yard. Moving traffic, parked cars, barriers, a ruler, a side view of each jump.
- `controls/index.html`: the control test yard. Pads, touch, keys; three turn models.

## Controls

| | Keys | Gamepad | Touch (phones and tablets, landscape) | Unlocked by |
|---|---|---|---|---|
| Move | WASD / arrows | stick or d-pad | analog stick, left | — |
| Dash | SPACE or K | A (or RT) | A | start; Battery recharges it faster |
| Jump | L or SHIFT | B | B | Legs 1 (by drone) |
| Pick up a cone | J or E, tap | X, tap | X, tap | Hands 1 by drone (one cone), Hands 2 (two) |
| Put a cone down | J or E, hold 0.3 s | X, hold | X, hold | Hands 1 |
| Push off a car | I or Q, after a hit or beside a car | Y | Y | Arms 1 (by drone) |
| Pause | ESC or P | START | ❚❚ PAUSE | — |
| Pad setup | G | hold START | — | — |

- ESC, START or ❚❚ pauses. **Options** (sound, palette, full screen, tuning, pad setup) and **Controls** (for the keyboard, pad or touch you are using) are in the pause menu.
- Touch controls show on touch screens, and appear at your first touch on any phone (S Pen phones too). Add `#touch` to the address to force them.
- On a phone, tap any menu item, card, tile or button. A mouse click works too.
- Touch: Pause › Controls › Adjust layout. Drag the stick or the buttons anywhere, size them (60–160%), Reset. Saved in your browser.
- Press any button on a gamepad first: browsers list a pad only after a press.
- Pad without a standard mapping: press G, then DASH, JUMP, GRAB, PUSH in turn.
- The shop opens after each write-off. Tuning (T, desktop) installs ability levels for a test run.

## What 7.8 changes

- Touch everywhere: every menu answers a tap. Touch controls appear at the first touch, also on S Pen phones (Galaxy S25 Ultra).
- Story has no credits now. Points level the dummy up: level 2 at 6,500 points, up to level 9. Each level gives one upgrade.
- LEVEL UP flashes across the screen in play, with a fanfare. The top-right box shows your points, level and a bar to the next.
- The workshop: your next chassis stands in the middle, its parts around it. Tap a part, then FIT. Parts a drone has not brought yet stay hidden ("???").
- Arcade keeps credits, in the same workshop.

## What 7.7 changes

- Save games. STORY opens a save screen: NEW GAME and three slots.
- Each slot shows its name, the date and time of its last save, where the story stands (map, tile, tiles cleared), points, credits, upgrades and chassis.
- CONTINUE, RENAME (up to 12 characters) or ERASE a slot. Erasing and overwriting ask twice.
- Type the name on a keyboard; on a pad, use the letter grid; on a phone, tap the keys or tap the name for the phone's keyboard.
- The game saves by itself after every write-off, clear, gift and purchase. A story from 7.6 in your browser appears in slot 1.

## What 7.6 changes

- One top edge: BODY, the game screen and a new POINTS · CREDITS box line up. The chassis sits under the box. Arcade's box: POINTS · CARS LEFT.
- The objective moves to the top strip. The map panel reads the map and tile, e.g. MONUMENT · A1.
- Touch: small PAUSE and FULL chips, top left. Everything fits the 16:9 centre.
- Touch: move and size the stick and the buttons yourself (Pause › Controls › Adjust layout). On a wide phone such as the S25 Ultra, put them in the side margins.

## What 7.5 changes

- A clean screen: nothing under the game. Options and controls moved into the pause menu.
- The pause menu's Controls page shows the device you are holding: keyboard, gamepad or touch.
- BODY is as tall as DASH, so the map sits higher and the touch stick has room. No FARSIGHT logo in play.

## What 7.4 changes

- Story: traffic is tuned tile by tile. The opening tiles and Parkland's quiet ones get more cars. Arcade keeps one level per map.
- Every highway has a staircase, and a lit gap in the railing over each road below: walk off it to drop onto the cars.
- Waterfront's bridges gain a staircase from the beach.
- Cones sit beside the road where you can see them: never on the road, under a highway or behind a building.

## What 7.3 changes

- Verbs are given, levels are bought. Legs 1, Hands 1 and Arms 1 arrive by drone; the shop never sells them.
- Story: Monument hands out a verb every three tiles: Legs 1 at C1, Hands 1 at A2, Arms 1 at C3.
- Arcade: the same verbs in the same order, one after each write-off.
- You see the drone bring it: a glowing case under the drone, lowered onto the dummy.
- Then a gift screen: the dummy's body, large; the new part falls onto it with a flash, rays and a fanfare. A continues; the drone carries you on.

## What 7.2 changes

- By default the dummy has two dashes, the standard recharge and recoil, and no other ability.
- Story: the upgrade tracks fill only at the end of Waterfront. 35 bodies certify the city.
- Hits throw the dummy less: a head-on hit slides it about a lane, not across the screen.
- After a clear, a Farsight drone carries the dummy into the next tile and sets it down off the road.
- Bounded edges glow yellow, as in Zelda; nothing blocks the road. Cleared tiles stay open.
- Maps: uncleared tiles grey, the live tile ringed in yellow.
- Cars speak in bubbles again. The objective sits on the bottom line.

## What 7.1 changes

- One credit for every body destroyed, in both modes.
- Story upgrades: level 1 costs 3 credits, level 2 costs 4, level 3 costs 5. Arcade keeps 1, 2, 3.
- Each story tile wants its own number of write-offs, 1 to 3: 62 bodies to certify the city.
- Only the last hit counts against Farsight's brief. Arcade plays one district a run.

## What 7 adds

- The title offers two modes.
- **ARCADE:** the 6.10 game. Pick Parkland, Waterfront or Monument; each district is a whole run.
- **STORY:** the Test City, tile by tile. Monument, then Parkland, then Waterfront: 27 tiles.
  - Each tile tells how that part of the city came to be, and gives Farsight's brief.
  - Write-offs that meet the brief clear a tile. Other write-offs score but don't count.
  - The tile is fenced until it is cleared. The fences can't be jumped. Cleared tiles stay open.
  - Every body pays a credit. Some tiles bring a gift.
  - The map opens one tile at a time. Progress is saved in your browser.

## Menus

| | Keys | Gamepad | Touch |
|---|---|---|---|
| Choose | arrows | stick or d-pad | stick |
| Select, begin | SPACE | A | A |
| Back | SHIFT | B | B |

## 6.10

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
