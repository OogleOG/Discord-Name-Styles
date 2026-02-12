# Discord Display Name Styles Preview

A web-based tool for previewing Discord's Nitro Display Name Styles. See exactly how your name will look with different effects, colours, and fonts — rendered in a realistic Discord chat environment.

**[Live Demo →]](https://oogleog.github.io/Discord-Name-Styles/))**

![Discord Display Name Styles Preview](https://img.shields.io/badge/Discord-Name%20Styles-5865F2?style=for-the-badge&logo=discord&logoColor=white)

## Features

- **5 Effects** — Solid, Gradient, Neon, Toon, and Pop with accurate animations
- **Live Chat Preview** — See your styled name in a realistic Discord chat with messages, timestamps, and grouped messages
- **Profile Card View** — Preview how your name appears on your Discord profile
- **Member List** — See your name alongside other users in the sidebar
- **All Effects Comparison** — View every effect side-by-side with your current settings
- **20 Preset Colours** + custom hex input and native colour picker
- **Dual Colour Support** — Gradient effect uses two colours with an animated shimmer sweep
- **7 Font Options** — gg sans, Serif, Handwritten, Monospace, Display Bold, Italic Serif, Rounded
- **Dark / Light Theme Toggle** — Preview in both Discord themes
- **Surprise Me** — Randomise everything for inspiration

## Effects

| Effect | Description |
|--------|-------------|
| **Solid** | Clean flat colour applied evenly across your name |
| **Gradient** | Smooth animated blend between two colours with a shimmer sweep |
| **Neon** | Glowing neon sign effect with a soft pulsating light bloom |
| **Toon** | Cartoon cel-shaded style with thick dark outlines and flat fill |
| **Pop** | Retro comic pop-art with halftone texture, bold outline, and bounce |

## Setup

No build step required. It's a single HTML file using React via CDN.

### GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch** → `main` → `/ (root)`
4. Your site will be live at `https://yourusername.github.io/discord-name-styles/`

### Local

Just open `index.html` in your browser. That's it.

## Tech

- React 18 (CDN)
- Babel Standalone (in-browser JSX compilation)
- Pure CSS animations (no external libraries)
- Zero dependencies, zero build step

## Note

Display Name Styles is a **Discord Nitro** feature. This tool is a preview/planning tool only — it is not affiliated with or endorsed by Discord. To actually apply styles to your name, you'll need an active Nitro subscription and to configure it through Discord's settings.

## License

MIT
