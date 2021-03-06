# Asteroids

Remake of the Asteroid classic retro game with Lua and [Love2D](https://love2d.org). This is a prototype, still under development.

![Screenshot](media/cover.png)

## Download

You can download the game at [florimondmanca.itch.io](https://florimondmanca.itch.io/asteroids).

## Installation

These are more advanced instructions for installing and building the game yourself.

1. Make sure you have installed [Love2D](https://love2d.org).

2. Clone the repo.

3. Open the `makelove` shell script and insert the path to your Love2D executable in the `$LOVE` variable.

## Run the game

Use the `makelove` script to generate a `asteroids.love` executable file and run it.

```bash
$ sh makelove
# or (may require $ chmod +x makelove)
$ ./makelove
```
Enjoy !

![Screenshot](media/screenshot2.png)

## References

Assets: [Kenney Space Shooter Redux](http://kenney.nl/assets/space-shooter-redux).

Third-party Lua packages: [lume](https://github.com/rxi/lume), [hump](http://hump.readthedocs.io/en/latest/gamestate.html)
