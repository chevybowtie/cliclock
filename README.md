# Cli clock
- install curses if not already installed: `sudo apt install libncurses5-dev libncursesw5-dev`
- Compile with `$cc clock.c -o clock -lcurses`
- Centered clock with seconds, 24h format
- User can change fg color with -c or --color parameter
- Use 'q' to quit

Fork of the tty-clock by xorg62.
