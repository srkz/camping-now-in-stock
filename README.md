# Burbank Amateur Radio Club (BARC)

> This project is vibe-coded, use at your own risk.

Static website for the Burbank Amateur Radio Club — a new, free, family-friendly
amateur radio club for Burbank, California and the surrounding media district.

## Stack

Plain HTML5 and CSS. No build step, no JavaScript, no dependencies. Open any
page in a browser.

```
.
├── index.html         # Home / About
├── membership.html    # Join the club
├── repeaters.html     # Planned UHF repeater + neighbors
├── calendar.html      # Nets, classes, events
├── css/style.css      # Shared styles (design tokens up top)
└── images/
    ├── logo.svg       # Shiba Inu + radio-wave mark
    └── favicon.svg    # Simplified mark for browser tabs
```

## Design goals

- **Retro-modern**: warm paper tones, masthead serif, monospace for callsigns
  and frequencies, schematic-blue accents — but on a clean, responsive grid
  with modern spacing and focus styles.
- **Accessible**: semantic HTML5, skip links, labelled nav, visible focus,
  sufficient color contrast, `prefers-reduced-motion` respected, real table
  headers and form labels, descriptive SVG `title`/`desc`.
- **Low-maintenance**: design tokens live in CSS custom properties at the top
  of `css/style.css`; edit once to rethemed the whole site.

## Local preview

```
python3 -m http.server 8000
```

Then open <http://localhost:8000/>.
