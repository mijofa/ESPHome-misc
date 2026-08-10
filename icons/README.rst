These all came from https://fonts.google.com/icons
At size 96, color '#E3E3E3' (the default), downloaded as svg, then I ran this sed replacement across them::

    sed -i 's/path d=/path stroke-width="16" stroke="black" d=/' *svg

This should give them all an outline border so they should be visible even if it's white-on-white
