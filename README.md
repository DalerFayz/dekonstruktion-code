# Dekonstruktion.kode — Terminal-Style Developer Profile

A retro-futuristic, terminal-native developer profile / business-card site.
No gradients, no shadows, no blurred layers — pure monospace TUI aesthetic
with binary-on-hover interactivity and ASCII graphics.

## Brand guidelines applied

- **Palette**: warm charcoal `#201d1d` + crisp porcelain `#fdfcfc`, inverted on
  interaction, respecting `prefers-color-scheme` light/dark.
- **Typography**: 100% monospace (`Berkeley Mono` → fallback chain).
- **UI**: 1px hairline borders, max `4px` radius, text-based TUI assets,
  ASCII hero logotype, `-> / <- / | / [+] / [-]` markers.

## Tech

- Vanilla HTML/CSS/JS — no build step, no dependencies.
- Google Fonts `Space Mono` as the only external asset (fallback chain handles
  systems with Berkeley Mono / JetBrains Mono installed).
- Fully responsive, works on mobile and desktop.

## Deploy

```bash
git clone https://github.com/DalerFayz/dekonstruktion-code.git
cd dekonstruktion-code
git checkout -b gh-pages
git push -u origin gh-pages
```

Then enable **GitHub Pages** for the `gh-pages` branch at
https://github.com/DalerFayz/dekonstruktion-code/settings/pages.

## License

MIT — free to reuse with attribution.
