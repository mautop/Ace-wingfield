# Ace Wingfield

A side-scrolling biplane dogfight that runs in the browser. Fly a fox pilot through day, night and storm skies, shoot down six kinds of sky pirate, dodge with a loop, and survive 100 waves to become the Ace of Aces.

Play it: https://YOUR-USERNAME.github.io/ace-wingfield/

## Controls

| | Keyboard | Touch |
|---|---|---|
| Fly | Arrow keys or WASD | Drag on the sky |
| Fire | Automatic | Automatic |
| Loop (no hits mid-loop) | Shift | LOOP button |
| Pause | P or Esc | Pause button |
| Pick your plane color | Left and right arrows on the title screen | Tap a color on the title screen |

Turn a phone sideways for a bigger playfield. Pause and LOOP float together over a bottom corner (there is also a Full screen button on the title screen), and it moves to the other side when you rotate the phone the other way, so it suits left and right thumbs. You can also use Swap side (title screen) or Swap LOOP side (pause menu). Each sky has its own music. To keep it on your phone's home screen, use your browser's "Add to Home Screen".

## Ranks

Each wave takes 8 kills. Pass wave 20 for **Ace**, wave 40 for **Double Ace**, wave 60 for **Triple Ace**, and wave 80 for **Quadruple Ace**. Clear all 100 waves to become the **Ace of Aces**, then the game starts over.

## Bonus rounds

After the first boss, and each time you earn an ace title, a 15-second **Balloon Rally** begins. There are no enemies. Fly through balloons (golden ones count double). Catch 6 for a bonus heart, 12 for a shield too, and 18 for rapid fire and spread shot as well. You can skip it, but skipping gives no rewards.

## Power-ups

Hearts heal, stars give rapid fire, shields absorb a hit, the spread shot fires three ways, and bombs clear the screen.

## Hazards

From wave 10, hazard mines drift across the sky. They hurt you and any enemy plane near the blast, and they burst into a ring of bullets. Bosses are not affected.

## Files

`index.html` is the whole game, with no build step. `manifest.webmanifest` and the three `icon-*.png` files let phones install it like an app. Upload all of them.

## Notes

- Your best score, best rank and plane color are saved in your browser.
- Fonts (Bungee and Fredoka, SIL Open Font License) load from Google Fonts.
- Music and sound effects are generated in the browser, so there are no audio files.
