# Transit

An animated SVG logo of a portal: a violet stone gate around a swirling blue vortex, with
twinkling sparkles. It works at every size, down to a 16 px favicon.

![Transit logo](portal-logo.svg)

With its name, in two layouts:

![Client Portal, horizontal](client-portal.svg)

![Client Portal, stacked](client-portal-stacked.svg)

## Download

- [portal-logo.svg](https://raw.githubusercontent.com/ddahan/transit/main/portal-logo.svg)
  (right-click › Save link as…), or:

```bash
curl -LO https://raw.githubusercontent.com/ddahan/transit/main/portal-logo.svg
```

- [client-portal.svg](https://raw.githubusercontent.com/ddahan/transit/main/client-portal.svg)
  (horizontal) ·
  [client-portal-stacked.svg](https://raw.githubusercontent.com/ddahan/transit/main/client-portal-stacked.svg)
  (stacked)

## Notes

- Animated with CSS inside the SVG; the animation stops when the system asks for reduced motion.
- The name is drawn with strokes, not text, so it looks the same without any font installed.
  Its colors follow the system's light or dark mode.
- Used as a favicon (`<link rel="icon" type="image/svg+xml" href="portal-logo.svg">`), it
  animates in Firefox; Chrome and Safari show its first frame.
