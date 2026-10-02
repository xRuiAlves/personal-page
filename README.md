# Personal Page

Source of my personal page at [ruialves.net](https://ruialves.net). It is one static page with my contacts and links to my GitHub, LinkedIn, résumé and blog.

## Development

There is no build step. To see the page locally, serve the repository root:

```sh
python3 -m http.server 8000  # local server at http://localhost:8000
```

## Update the page

- `index.html` and `style.css` hold the whole page. The page must fit the viewport with no scroll.
- `foto.jpg` is the profile photo. Keep it about 1600px wide and remove its EXIF data.
- `og-image.jpg` is the social preview image (1200x630). Make it again when the page content changes.
- `thesis.pdf` and `enei-2025.pdf` are hosted at `/thesis.pdf` and `/enei-2025.pdf`. The page does not link to them.

## Deploy

- Build command: none
- Output directory: the repository root
