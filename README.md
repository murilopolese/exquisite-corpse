# Exquisite Corpse

> A game in which each participant takes turns writing or drawing on a sheet of paper, folding it to conceal his or her contribution, and then passing it to the next player for a further contribution. The game gained popularity in artistic circles during the 1920s when it was adopted as a technique by artists of the Surrealist movement to generate collaborative compositions.

[MoMA article](https://www.moma.org/collection/terms/exquisite-corpse)

## What?

We're playing Exquisite Corpse with the axidraw!

## How?

### Drawing

1. Go to https://editor.p5js.org/
2. Install [p5.js-svg](https://github.com/zenozeng/p5.js-svg)
3. Make a 400x200 canvas
4. Start your drawing at the "top center" and end at the "bottom center"
5. Set both stroke and background to white
6. Export SVG

This will generate an SVG that our print script is expecting!

### Printing

![** UNDER CONSTRUCTION **](https://strongautomotive.com/wp-content/uploads/2016/10/Website-Under-Construction.jpg)

The script `print` will print the 3 first items of the `files` array.

Make `print` executable (when running for the first time):

```
chmod +x print
```

Run `print`:

```
./print
```
