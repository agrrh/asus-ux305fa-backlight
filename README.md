# asus-ux305fa-backlight
Script to manipulate backlight of ASUS Zenbook UX305FA.

Just bind some commands on desired key combinations:

    ./asus-ux305fa-backlight up
    ./asus-ux305fa-backlight down

    ./asus-ux305fa-backlight min
    ./asus-ux305fa-backlight max

    ./asus-ux305fa-backlight 100
    ./asus-ux305fa-backlight 900

Please, do not try to set up a level of 0 or other values less than ~50.

Same effect could be reached via `xbacklight`:

    xbacklight -inc 10
    xbacklight -dec 10

Sadly, I found it 1 hour after script was done. :)
