# textart

Converts images to html or terminal text

By James Reynolds
www.magnusviri.com

    Usage: textart [-h] [-w <width>] (<file>|raw_colors|color_wheel|color_gradients) [(<file>|etc)..]

    -h print html page instead of terminal escape sequences (terminal is default).
    -w width in characters (height is based on width).
    <file> the image file to display.
    raw_colors - (see https://en.wikipedia.org/wiki/ANSI_escape_code#8-bit)
    color_wheel - shows a color wheel
    color_gradients - shows nice gradients

I drew inspiration from these websites.

- https://gist.github.com/donatj/1353237
- http://paulbourke.net/dataformats/asciiart/
- https://en.wikipedia.org/wiki/ANSI_escape_code#8-bit

Examples:

![logo](https://raw.githubusercontent.com/magnusviri/textart/master/examples/magnusviri.png)

![logo as text](https://raw.githubusercontent.com/magnusviri/textart/master/examples/magnusviri_text.png)

HTML source of the above image: https://raw.githubusercontent.com/magnusviri/textart/master/examples/magnusviri.html

Run these commands in Mac OS X terminal (or iTerm2) for more examples:

    curl https://raw.githubusercontent.com/magnusviri/textart/master/examples/color_wheel.txt
    curl https://raw.githubusercontent.com/magnusviri/textart/master/examples/earth-at-night-asia.txt
    curl https://raw.githubusercontent.com/magnusviri/textart/master/examples/magnusviri.txt
    curl https://raw.githubusercontent.com/magnusviri/textart/master/examples/poppy-2444596.txt
    curl https://raw.githubusercontent.com/magnusviri/textart/master/examples/sunrise-2445150.txt

Note, on iTerm2 it looks best if the ANSI color for black is black. Otherwise it will look wrong. Some of the color presets change the color of black and so yeah.
