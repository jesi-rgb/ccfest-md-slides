# Implementing native GIF saving in p5.js

#### Jesús Enrique Cartas Rascón — March 25th, 2023

---

# Who are you again?

- It's Jesús here! Digitally known as @jesi_rgb mostly everywhere.

- I am a designer, web developer, animator and musician! All things art, but make it digital.

- So far, I've mainly done mathematical animation and web design.

![bg left](media/duggish.jpg)

---

# So, GIFs

## What?

- Pronounced like /GIF/
- Lossless image compression format
- Lighter, video like (sometimes)
- _Very_ old format
- Palette based

---

# So, GIFs

## Why?

- Excellent meme format
- Excellent WIP sharing format
- True and tested, supported mostly everywhere
- Everyone is familiar with it
- Most webpages are comfortable with it

---

# So, GIFs

## How?

- **Bucket list**:
  - Fast, as fast as possible
  - Very easy to use
  - Somewhat reliable
  - Responsive.
    - _Please, do not freeze my computer_

---

# So, GIFs

## How?

- Gather every **frame** from your animation

- Generate a global **palette**

- **Apply** the palette to every frame

- Smash **holes** wherever applies

- **Encode** each frame

- Enjoy! 🥳 🎉

---

# Global Palette Generation

![bg left opacity:.4](media/tourney.gif)

<!-- GIF or image of an ancient book "the gif specs" -->

## Why?

In order to build any given GIF file, we must comply with the GIF specs. And specs tell us that we must use a maximum of 256 colors.

We can use a default one that has a mediocre representation of _all_ the colors, or we can generate one ourselves. It is not _that_ hard and yields much better results.

---

# Global Palette Generation

---

# Applying a palette

---

# Important optionals

## ✨Transparency optimization✨
