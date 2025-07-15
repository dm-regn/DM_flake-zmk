# Anywhy Flake Based

starting off with Flake-M from [anywhy-io](https://github.com/anywhy-io/flake-zmk-module).

successfully added a n!n_v2 with 1.3" oled display as central dongle with the flake-m now acting as peripherals. 
using [englmaxi](https://github.com/englmaxi/zmk-dongle-display) for dongle stuff.

![quick pic](/quick_pic.jpg)

seems stable, it's been up and running without issues.
- POM cherry profile keycaps
- Durock ice king linear switches (stock)
- PLA case (no plate, bare PCB)

layout notes:
- running a modified version of aptmak
- layers: alpha, steno, navigation, number+symbols, quick, gaming
- looking into implement more combos using [ARTSEY](https://keymapdb.com/keymaps/ARTSEY/) as an example

next steps:
- wire in battery with rocker switch
- wire in bootloader / reset momentary switch
- design and print dongle case (adjustable tilt for display, magnet accommodations)
- design and print new cases for peripherals (add in tenting, bigger battery, magnet accommodations)
