# Lissajous

A Lissajous oscilloscope synthesizer for iPhone. Built for touch.

## Files

```
index.html       — the instrument
manifest.json    — PWA manifest
sw.js            — service worker (offline support)
icon-192.png     — app icon
icon-512.png     — app icon (large)
```

## Hosting on GitHub Pages (free, ~5 min)

1. Create a new repository at github.com (public)
1. Upload all five files to the repository root
1. Go to **Settings → Pages → Source** and select `main` branch, `/ (root)`
1. Your URL will be `https://yourusername.github.io/repositoryname/`

## Installing to iPhone home screen

1. Open the URL in **Safari** (must be Safari, not Chrome)
1. Tap the **Share** button (box with arrow)
1. Tap **Add to Home Screen**
1. Tap **Add**

It will launch full-screen with no browser chrome, like a native app.  
Works offline after first load.

## Hosting alternatives

- **Netlify**: drag the folder to netlify.com/drop
- **Vercel**: `npx vercel` in the folder
- **itch.io**: upload as an HTML game (set frame size to device dimensions)

## Controls

**Top row** — SCREEN / TIME / SCALE / ENV pages  
**Plot area** — touch and drag to move the selected dot; flick to throw  
**Bottom buttons** — LFO / CLK / VCO modules  
**Left fader (shape)** — LFO waveform morph  
**Right fader (wet)** — dry/wet balance for delay + reverb  
**Vertical strip (right)** — pitch / parameter Y axis
