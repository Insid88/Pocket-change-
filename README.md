# Pocket-change-

A simple guide for people who need a read-only GitHub personal access token
for repository contents in the Dark Order organization.

Open `index.html` to use the guide. Its button sends you to GitHub's token
creation form with the Dark Order organization, token name, 45-day expiration,
and read-only contents permission prefilled. GitHub creates and manages the
token; this project does not collect or store tokens.

Review the organization and permissions on GitHub before creating a token.
Store the token securely and never share it.

## Publishing

Pushes to `main` deploy `index.html` to GitHub Pages via
`.github/workflows/pages.yml`. Enable it once under Settings → Pages →
Source: "GitHub Actions". Note that Pages sites are public by default.
Before sharing, click through the button to confirm the prefilled form works
and that the organization allows fine-grained tokens.
