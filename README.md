# Projects

The source for **projects.jdunne.au**: a landing page that navigates to the apps and experiments hosted on the site. Plain HTML, CSS and JavaScript, with no build step.

## Layout

| Path | What it is |
|---|---|
| `index.html` | The landing page: a card for each live app |
| `framewise/index.html` | Framewise, a video study workspace |
| `planit/buildexamples.html` | planit build cost examples (estimated totals only). Not linked from the landing page |

Each app lives in its own folder and is served at `projects.jdunne.au/<folder>/`.

## Adding a project

1. Create a folder with an `index.html` for the app.
2. Copy an existing `<li>` card in `index.html`, then change the link, name, description and address.
3. Update the "live" count in the section header.
4. Commit and push to `main`.

## Publishing

Cloudflare Pages, connected to this repo's `main` branch. No build command; build output directory `/` (leave it blank).

## Notes

- `planit/buildexamples.html` is a deliberately reduced page. It shows only the estimated total cash cost for each example and column. Do not add line items, assumptions or planit prices to this public repo.
