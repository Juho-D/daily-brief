# daily-brief

Daily brief archive for Advanced Packaging and SI/PI topics.

## Structure

- `docs/`: GitHub Pages site. Publish this folder from the `main` branch.
- `docs/digest_YYYY-MM-DD.html`: mobile-first full daily HTML reports.
- `obsidian/`: Markdown copies for Obsidian knowledge management.
- `scripts/`: future automation helpers.

## GitHub Pages Setup

1. Create an empty GitHub repository named `daily-brief`.
2. Push this local repository to GitHub.
3. In GitHub, open `Settings -> Pages`.
4. Set source to `Deploy from a branch`.
5. Select branch `main` and folder `/docs`.
6. The report URL will look like:

   `https://Juho-D.github.io/daily-brief/digest_2026-05-28.html`

Do not store webhook secrets or tokens in this repository.
