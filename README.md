# Module 1 — Bonus Project

You've finished the first project with time to spare, you whipper-snapper!

This **optional** project is similar to the first project, it asks you to implement a UI from a mockup, using HTML and CSS.

Here's the mockup:

![Mockup of website](./mockup.png)

(This design was heavily inspired by this illustration on Dribbble: https://dribbble.com/shots/11079922-AdWords-Single-Fold-Layout)

# Design Tool

Optionally, you can use Figma to quickly derive various sizes and colours. No more guesstimation!

The Figma project link is here: https://www.figma.com/file/ecS0s64TeWE2KDmLrCfFJ8/HTML-CSS-Extra

# Notes

- You'll want to use the "Lato" font from Google Fonts.
- We haven't provided any starter files, so you'll need to create an HTML and CSS file to get started.
- You are given a few assets in this directory: a hamburger menu, several quirky shapes. You'll notice you are missing a few: the half-circle logo, the blue triangle in the top right. You can recreate these with CSS, using tools like `border-radius`, `overflow: hidden`, and `transform: rotate`.
- The search input _appears_ to contain a button, but this is not valid HTML. Instead, you'll want to put the input beside the button, and apply some styles (the box shadow) to the containing element.
- The colourful tiles are the trickiest part of this mockup. Your best bet is to use CSS Grid. We haven't covered CSS grid, so you might want to first spend some time learning the tool. You're also welcome to attempt it using flexbox; it's certainly possible, but it will be a steeper hill to climb.
- The random shapes and medical researcher have weird positions within their tiles. You can use `position: absolute` and `overflow: hidden` to get it to look right.

# Stretch goals

What if you get through all of the above, with time to spare? Here are some ideas:

- **Tile Animations**: Make each tile grow on hover. It should get bigger and also gain a subtle box shadow.
- **Mobile responsive**: How could the tiles be arranged to work on a mobile device? How about a tablet? Create 3 separate arrangements for each viewport size. Heads up: this is _pretty darn tricky._
