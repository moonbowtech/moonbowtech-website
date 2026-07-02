# Moonbow Website GitHub Workflow

This repository is a static website. GitHub Pages publishes the files from the `main` branch.

## Safe update procedure

### 1. Download a backup
On GitHub, open the repository and use:

`Code → Download ZIP`

Save that ZIP somewhere safe before making changes.

### 2. Edit locally
Unzip the working website folder on your computer.

Make edits to:
- `index.html`
- `style.css`
- page folders such as `sciresmethods/index.html`

### 3. Preview locally
Double-click `index.html`.

Check:
- homepage loads
- navigation links work
- SciResMethods page opens
- Enterprise link opens the methodology page
- buttons point to the intended LemonSqueezy / podcast links

### 4. Upload changed files to GitHub

For a simple GitHub web upload:

1. Open the GitHub repository.
2. Click `Add file → Upload files`.
3. Drag the changed files/folders.
4. Add a commit message, for example:

`Add SciResMethods pathway and dual-entry homepage`

5. Click `Commit changes`.

### 5. Verify live site
Wait 1–5 minutes, then open:

`https://moonbowtech.com/`

Refresh hard if needed:
- Windows: `Ctrl + F5`
- Mac: `Cmd + Shift + R`

## What changed in this release

- Homepage now has two clear pathways:
  - Enterprise Solutions
  - SciResMethods
- Added `/sciresmethods/`
- Added `/sciresmethods/podcast/`
- Added `/sciresmethods/toolkits/`
- Updated navigation
- Updated sitemap
- Preserved the B2B enterprise site architecture

## Important TODO

Replace the placeholder Spotify link in:

`sciresmethods/podcast/index.html`

The current placeholder is:

`https://open.spotify.com/show/033usLXmE0QENQGMiFOmX6`

Apple Podcasts link is already included:

`https://podcasts.apple.com/us/podcast/sciresmethods/id6786114372`

The LemonSqueezy store link used is:

`https://moonbow.lemonsqueezy.com`


## Production Links Added in v3

- LemonSqueezy store: https://moonbow.lemonsqueezy.com/
- Spotify: https://open.spotify.com/show/033usLXmE0QENQGMiFOmX6
- Apple Podcasts: https://podcasts.apple.com/us/podcast/sciresmethods/id6786114372
- Amazon Music: https://music.amazon.com/podcasts/87c30f8b-6719-43fe-804c-fe805aa6786e/sciresmethods
- YouTube Music: https://www.youtube.com/playlist?list=PLZbxyUEeB7G4

