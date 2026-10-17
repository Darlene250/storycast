# StoryCast

An accessible 3-page microsite showcasing audio and video stories.
Built with semantic HTML5, Sass and vanilla CSS. No frameworks.

## Project structure

- `index.html`: Home page (featured stories)
- `about.html`: About / Access page
- `story/story-1.html`: Story detail page (audio, transcript, related stories)
- `sass/`: partials (`_colors`, `_typography`, `_spacing`) and `main.scss`
- `css/main.css`: compiled styles
- `assets/`: media files (audio and images)

## Run locally

1. Install Node.js, then run `npm install -g sass`
2. Compile: `sass sass/main.scss css/main.css`
3. Open `index.html` in a browser

## Accessibility checklist

- [x] Semantic landmarks: header, nav, main, article, section, aside, footer
- [x] Logical headings (one h1, then h2, h3)
- [x] Transcript for the audio story
- [x] figure and figcaption for media descriptions
- [x] Alt text on all images
- [x] Skip link and visible keyboard focus
- [x] aria-label on navigation, aria-current on the active page
- [x] Contrast checked with WebAIM: #1a1a1a on #ffffff = 17.4:1 (AA and AAA pass)
- [x] Responsive layout with Grid, Flexbox and a container query

## Design links

- Sitemap and wireframes (Figma): https://www.figma.com/design/ZqtUy6ctvUjaJ8dgiPOmJg/StoryCast-Sitemap?node-id=0-1&t=8Od0biNby1DeQGca-1

## Credits

- Music: "Ambient Music" by leberch, from Pixabay (royalty-free)
- Photos: Pexels (free to use)