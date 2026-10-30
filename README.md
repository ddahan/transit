# Transit

The Client Portal logo, animated SVG: the name, its "o" a swirling indigo and cyan portal with
twinkling stars, and that portal on its own.

![Client Portal](portal-text.svg)

![Portal](portal-o.svg)

## Download

- [portal-text.svg](https://raw.githubusercontent.com/ddahan/transit/main/portal-text.svg): the name
- [portal-o.svg](https://raw.githubusercontent.com/ddahan/transit/main/portal-o.svg): the portal alone, square

```bash
curl -LO https://raw.githubusercontent.com/ddahan/transit/main/portal-text.svg
```

```bash
curl -LO https://raw.githubusercontent.com/ddahan/transit/main/portal-o.svg
```

## Colors

Two colors, from Tailwind's palettes (Nuxt UI's): **indigo** as primary, **cyan** as secondary,
plus white. In Nuxt UI: `ui: { colors: { primary: 'indigo', secondary: 'cyan' } }`.

## Notes

- The name is set in Quicksand (SIL Open Font License), converted to paths: it looks the same
  without the font installed. Its colors follow the system's light or dark mode.
- Animated with CSS inside the SVG; the animation stops when the system asks for reduced motion.
- As a favicon (`<link rel="icon" type="image/svg+xml" href="portal-o.svg">`), it animates in
  Firefox; Chrome and Safari show its first frame.
