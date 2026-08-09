# X (Twitter) Clone

A front-end clone of X (Twitter)'s home feed, built with plain HTML and Tailwind CSS. It recreates X's current light-theme UI — icon-only sidebar, post composer, and timeline — using custom SVG icons and interactive hover states.

> This is a static front-end clone built for learning and practice purposes only. It has no backend, no real authentication, and no real data — all posts, avatars, and stats are placeholders.

## Features

- Icon-only left sidebar — Home, Search, Notifications, Messages, Explore, Premium, Profile
- Post composer with 8 custom SVG action icons (Media, GIF, Generate image, Poll, Emoji, Schedule, Location, Content warning), each with an animated scale and name tooltip on hover
- "Show new posts" live-update divider
- 8-post scrollable timeline with a mix of text-only and image posts, each carrying its own hashtags
- Right sidebar with Today's News, What's Happening (trending hashtags), and Who to Follow
- Working post engagement icons (reply, repost, like, views, bookmark, share) with hover color states
- Light theme matching X's current design
- Blank, placeholder avatars throughout — no third-party profile photos used
- Generic, non-identifying account names — no real public figures

## Tech Stack

- HTML5
- [Tailwind CSS](https://tailwindcss.com/) via CDN
- [Google Material Symbols](https://fonts.google.com/icons) outlined icon set
- [Inter](https://fonts.google.com/specimen/Inter) Google Font
- Custom inline SVGs for the composer toolbar icons

## File Structure

```
.
├── index.html
└── README.md
```

## Getting Started

No build step or dependencies are required since this is a static site.

1. Clone or download this repository.
2. Open `index.html` directly in your browser, or serve it with any static file server / live-reload extension.
3. Since the file is named `index.html`, GitHub Pages can serve it automatically once enabled in the repository settings.

## Limitations

- Not responsive yet — built for a fixed desktop width and doesn't adapt to smaller screens.
- Static only — the composer, tabs, and buttons are visual and don't persist state or submit data.
- Images are sourced from the picsum.photos placeholder service.

## License

Released under the MIT License. Free to use, modify, and distribute.