# Display font

The redesign uses **M PLUS Rounded 1c Black** (weight 900), a rounded display
alternative to the lettering in the visual concept. It is not an exact font
match to the generated concept.

## Source and license

- Original font: [Google Fonts — M PLUS Rounded 1c Black](https://github.com/google/fonts/blob/main/ofl/mplusrounded1c/MPLUSRounded1c-Black.ttf).
- Original license: [Google Fonts — Rounded M+ OFL](https://github.com/google/fonts/blob/main/ofl/roundedmplus1c/OFL.txt).
- Copyright 2016 The Rounded M+ Project Authors.
- Licensed under the SIL Open Font License 1.1; the complete license is included
  in `MPLUSRounded1c-OFL.txt`. The license permits web embedding and redistribution
  with the site. The font must remain under the OFL and must not be sold by itself.

`m-plus-rounded-1c-black.woff2` is a local WOFF2 subset of the original font, created
with FontTools. Latin, Cyrillic, digits, and available common punctuation and
symbols are retained. Japanese and other unused characters were removed to keep
the file at 48,188 bytes. FontTools verified the full Russian alphabet, including
Ё/ё, Latin letters, and digits in the resulting `cmap` table. The original does
not contain the ruble sign (`₽`), so a fallback font renders that symbol.

## CSS

```css
@font-face {
  font-family: "M PLUS Rounded 1c";
  src: url("/fonts/m-plus-rounded-1c-black.woff2") format("woff2");
  font-style: normal;
  font-weight: 900;
  font-display: swap;
}

.display-heading {
  font-family: "M PLUS Rounded 1c", sans-serif;
  font-weight: 900;
}
```
