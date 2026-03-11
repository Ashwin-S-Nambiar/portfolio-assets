# portfolio-assets

This repository serves as the static asset store for [ashwin.co.in](https://ashwin.co.in), a personal portfolio website. All assets are served via the [jsDelivr](https://www.jsdelivr.com/) CDN, which provides fast and reliable delivery by pulling directly from this GitHub repository.

## CDN Usage

Assets are referenced in the portfolio using the following URL pattern:

```
https://cdn.jsdelivr.net/gh/ashwin-333/portfolio-assets@main/<path-to-asset>
```

For example:

```
https://cdn.jsdelivr.net/gh/ashwin-333/portfolio-assets@main/profile/profile-image.webp
```

## Repository Structure

```
portfolio-assets/
├── profile/                  # Profile images used on the main portfolio page
│   ├── profile-image.webp
│   └── profile-gif.gif
│
├── projects/                 # Per-project screenshots, mockups, and showcase videos
│   ├── AddToCart/
│   ├── BlogSpace/
│   ├── ColorSchemeGenerator/
│   ├── MemeGenerator/
│   ├── MovieVault/
│   ├── Quillify/
│   ├── QuizzMe/
│   ├── Tenzies/
│   └── TravelJournal/
│
└── showcase/                 # Cover images and demo videos for featured showcases
    ├── magnetic-button/
    ├── spotify/
    └── trakt/
```

Each project folder typically contains:
- Cover image (`*-cover.webp`)
- Mockup image (`*Mockup.webp`)
- Individual screenshots (`*-1.webp`, `*-2.webp`, ...)
- Showcase video (`*-showcase.mp4`)

## Asset Formats

Images are stored in `.webp` format for optimal compression and loading performance. Videos are stored as `.mp4` files.

## Notes

- This repository is public to allow jsDelivr to serve its contents without authentication.
- Do not store sensitive files or credentials here.
- When adding new assets, use lowercase hyphenated filenames for consistency.
