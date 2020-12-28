For SVGs,
1. Insist on square-shaped SVG icons (viewbox = "0 0 X Y) where X and Y are equal
4. Minimise its size using ohmysvg by Jake Archibald
3. Remove the width and height attributes
2. You can use tailwind's h-N and w-N classes to replace the width and height attributes to make it tailwind-responsive
5. Colour the svg using the 'fill current' class and the [text-colour]-[shade] classes or use the fill propery on the svg path