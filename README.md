# Oral Presentations

A collection of interactive English oral presentations about science, space, and the questions that make us look up.

## Live Site

Open the presentation index here:

**https://sonickseven.github.io/oral_presentations/**

The site is published with GitHub Pages and serves `index.html` from the repository root.

## Presentations

### How Fast Is Light?

An 8-slide interactive presentation covering:

- The speed of light and why massive objects cannot reach it
- Time dilation and special relativity
- Voyager 1's journey to one light-day
- Light crossing the 100,000-light-year span of the Milky Way
- Looking into the past when we observe distant stars
- The final limits of speed and energy

Open it directly: [b2_8_oral_presentation.html](b2_8_oral_presentation.html)

## Features

- Self-contained HTML presentations with no build step
- Interactive canvas animations for the Voyager 1 and Milky Way journeys
- Keyboard navigation and fullscreen presentation mode
- Responsive layout for desktop and mobile
- Animated landing page linking to every presentation

## Project Structure

```text
.
├── index.html                    # Landing page and presentation index
├── b2_8_oral_presentation.html   # How Fast Is Light? presentation
└── README.md
```

## Presentation Controls

| Key | Action |
| --- | --- |
| `Right Arrow` / `Page Down` / `Space` | Next slide |
| `Left Arrow` / `Page Up` | Previous slide |
| `Home` | First slide |
| `End` | Last slide |
| `F` | Toggle fullscreen |
| `Esc` | Exit fullscreen |

## Run Locally

Open `index.html` directly in a browser, or serve the folder with any static file server. For example:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000/`.

## Adding a New Presentation

1. Add the presentation HTML file to the repository root.
2. Add a new card to the presentation list in `index.html`, linking to the file.
3. Commit and push to `main` to publish through GitHub Pages.
