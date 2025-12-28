# How to Change Favicon

Quick guide to change the favicon for your Jekyll Chirpy theme blog.

## Quick Steps

1. **Prepare a square image** (recommended 512×512px or larger)

2. **Generate favicon files** using [RealFaviconGenerator](https://realfavicongenerator.net/):
   - Upload your image
   - Customize platform-specific settings (optional)
   - Download the generated package

3. **Place files** in `assets/img/favicons/` directory:
   ```
   assets/img/favicons/
   ├── android-chrome-192x192.png
   ├── android-chrome-512x512.png
   ├── apple-touch-icon.png
   ├── favicon-16x16.png
   ├── favicon-32x32.png
   ├── favicon.ico
   ├── mstile-150x150.png
   ├── site.webmanifest
   └── browserconfig.xml
   ```

4. **Commit and push** changes:
   ```bash
   git add assets/img/favicons/
   git commit -m "Update favicon"
   git push
   ```

5. **Verify** after GitHub Pages rebuilds (clear browser cache if needed)

## Required Files

Minimum required files for Chirpy theme:
- `favicon.ico` - Traditional browser icon (32×32)
- `favicon-16x16.png` - Small tab icon
- `favicon-32x32.png` - Standard tab icon  
- `apple-touch-icon.png` - iOS home screen icon (180×180)
- `android-chrome-192x192.png` - Android icon
- `android-chrome-512x512.png` - Android HD icon
- `mstile-150x150.png` - Windows tile
- `site.webmanifest` - PWA configuration
- `browserconfig.xml` - IE/Edge configuration

## Recommended Tools

- **[RealFaviconGenerator](https://realfavicongenerator.net/)** - Most comprehensive
- **[Favicon.io](https://favicon.io/)** - Simple and fast
- **ImageMagick** - Command-line option for local generation

## Troubleshooting

**Favicon not updating?**
- Hard refresh: Ctrl+F5 (Windows) or Cmd+Shift+R (Mac)
- Clear browser cache
- Test in incognito/private mode

**Mobile icon not updating?**
- iOS: Delete and re-add home screen icon
- Android: Clear Chrome app data

## For Detailed Guide

See the complete Chinese documentation: [如何更改Favicon.md](./如何更改Favicon.md)
