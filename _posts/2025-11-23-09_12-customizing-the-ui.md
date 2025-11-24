---
type: posts
title:  "11/23 - 09:12 : Customizing the UI"
---

![Sunrise](/images/bear_and_moose.png)

# Initial setup

## Cloned

These directories were cloned from the [mmistakes/minimal-mistakes](https://github.com/mmistakes/minimal-mistakes) GitHub repository:

- _sass/*
- _layouts/*

## Created

- _posts/
- _pages/
- images/

---

# Custom Colors

The **Colors** section near the top of the file sets the colors for the theme.

- [Neon Skin file](_sass/minimal-mistakes/skins/_neon.scss) - `_sass/minimal-mistakes/skins/_neon.scss`.


## Navigation Button Colors


The line below (from the *Neon Skin file* file) shows where to change the color of the *Previous* and *Next* button colors.

```
    background-color: #2c3a10;
```

Here's the old line:

```
    background-color: $primary-color; 
```

## Wallpaper Color

```
$background-color: #141010 !default;
```

## HTML Link Color

```
$link-color: #0084ff !default;
```

---

# Links

- [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) on GitHub