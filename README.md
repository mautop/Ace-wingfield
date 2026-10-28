# Ace Wingfield

A side-scrolling biplane dogfight that runs in the browser. Fly a fox pilot through day, night and storm skies, shoot down six kinds of sky pirate, dodge with a loop, and survive three tiers of 100 waves to earn the bronze, silver and gold star medals.

Play it: https://YOUR-USERNAME.github.io/ace-wingfield/

## Controls

| | Keyboard | Touch |
|---|---|---|
| Fly | Arrow keys or WASD | Drag on the sky |
| Fire | Automatic | Automatic |
| Loop (no hits mid-loop) | Shift | The big LOOP button |
| Use a stored power-up | 1 to 4 | The round buttons above LOOP |
| Pause | P or Esc | The small pause button at the top |
| Pick your plane color | Left and right arrows on the title screen | Tap a color on the title screen |

All the touch buttons live inside the sky, in one column on your thumb side: power-ups on top and the big LOOP button at the bottom, with the bomb farthest from LOOP so it is hard to hit by accident. Turn a phone sideways for a bigger playfield (there is also a Full screen button on the title screen). The column moves to the other side when you rotate the phone the other way, so it suits left and right thumbs. You can also use Swap side (title screen) or Swap button side (pause menu). Each sky has its own music. To keep it on your phone's home screen, use your browser's "Add to Home Screen".

## Ranks

Each wave takes 8 kills. Pass wave 20 for **Ace**, wave 40 for **Double Ace**, wave 60 for **Triple Ace**, and wave 80 for **Quadruple Ace**. Clear all 100 waves to become the **Ace of Aces** and earn the tier's star medal.

## Tiers, medals and plane colors

The game has three tiers of 100 waves each. Hearts, score and your plane carry over.

| Tier | Sky | Weather | Reward for clearing it |
| --- | --- | --- | --- |
| 1. The Meadow | Day, night, storm | Rain in the storm | Bronze star |
| 2. The Snowfield | Day, polar night, blizzard | Snow | Silver star |
| 3. The Desert | Day, dusk, sandstorm | Blowing sand | Gold star, and the game ends |

Tiers 2 and 3 are a little harder, and the boss fights get tougher. The bosses also change colors: icy indigo in the snowfield, and black with crimson and gold in the desert. If you lose in tier 2 or 3 you restart at wave 1 of that tier. Once you own a medal, a **Tier** button on the home screen lets you pick which tier to start in.

Plane colors: Teal, Sunshine and Sky Blue are free. The bronze star unlocks Midnight, Bubblegum and Snow. The silver star unlocks Cherry and Graphite. All eight show on the home screen, and locked ones can be previewed but not flown. Medals are saved in your browser.

Testing shortcuts (add to the page address): `?medal=bronze`, `?medal=silver` or `?medal=gold` unlocks the medals, `?tier=2` or `?tier=3` picks the start tier, and `?wave=90` starts a new run at that wave.

## Bonus rounds

After the first boss, and each time you earn an ace title, a 15-second **Balloon Rally** begins. There are no enemies. Fly through balloons (golden ones count double). Catch 6 for a bonus heart, 12 for a shield too, and 18 for rapid fire and spread shot as well. You can skip it, but skipping gives no rewards.

## Power-ups

Hearts heal the moment you pick them up. Everything else is stored, up to 2 of each kind, and you choose when to use it: stars give rapid fire, shields absorb a hit, the spread shot fires three ways, and bombs clear the screen. Tap the round buttons on the side away from LOOP, or press 1 to 4 on a keyboard. A full slot turns an extra pickup into 25 points. Stored power-ups reset when you move on to the next tier.

## Hazards

From wave 10, hazard mines drift across the sky. They hurt you and any enemy plane near the blast, and they burst into a ring of bullets. Bosses are not affected.

## Files

`index.html` is the whole game, with no build step. `manifest.webmanifest` and the three `icon-*.png` files let phones install it like an app. Upload all of them.

## Notes

- Your best score, best rank and plane color are saved in your browser.
- Fonts (Bungee and Fredoka, SIL Open Font License) load from Google Fonts.
- Music and sound effects are generated in the browser, so there are no audio files.
