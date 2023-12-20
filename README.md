# gamescene 2.2

A simple library made to replicate gamescene in 2.2 using event triggers.

## macros

Here, i will refer to the platformer buttons as "plat. buttons".

- `button(target)` spawns the `target` every time either p1/p2 jump buttons get pressed.
- `button_end(target)` spawns the `target` every time either p1/p2 jump buttons get released.
- `button_a(target)` spawns the `target` every time the p1 jump button gets pressed.
- `button_b(target)` spawns the `target` every time the p2 jump button gets pressed.
- `button_a_end(target)` spawns the `target` every time the p1 jump button gets released.
- `button_b_end(target)` spawns the `target` every time the p2 jump button gets released.
- `button_a_left(target)` spawns the `target` every time the p1 left plat. button gets pressed.
- `button_a_right(target)` spawns the `target` every time the p1 right plat. button gets pressed.
- `button_b_left(target)` spawns the `target` every time the p2 left plat. button gets pressed.
- `button_b_right(target)` spawns the `target` every time the p2 right plat. button gets pressed.
- `button_a_left_end(target)` spawns the `target` every time the p1 left plat. button gets released.
- `button_a_right_end(target)` spawns the `target` every time the p1 right plat. button gets released.
- `button_b_left_end(target)` spawns the `target` every time the p2 left plat. button gets released.
- `button_b_right_end(target)` spawns the `target` every time the p2 right plat. button gets released.
- `init(hide_players, disable_death_sfx)` hides the players and disables death sfx whether the corresponding options are set to true (they are true by default).

## example

I put together a [quick example](./example.spwn) that demonstrates how most of the macros work. The code just maps all of the presses and releases to counters which you can later use.
