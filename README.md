# MG3
## Devlog
1. What are the default values for floats, ints, bools, and strings?
The default value for a float is 0, for an int is 0, for a bool is false, and for a string is null. In Unity's Inspector, a string may appear as an empty text field.
2. How does the Update method get called?
The Update() method is automatically called by Unity once every frame when the script is active. We do not need to call it ourselves. Unity handles this during gameplay.
3. Explain how either the KickWeapon or TimerText class uses the timer. Mention the Update() method.
In the TimerText class, the timer starts when the game begins. The Update() method checks whether the timer has finished. If the time runs out, it calls the GameOver() method. It also updates the timer text on the screen to show how much time is left.

## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)
