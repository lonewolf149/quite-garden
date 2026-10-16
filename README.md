# The Quiet Garden

An interactive flower garden under a gloomy sky, made as a surprise gift. Roses, tulips, sunflowers, daisies and lavender grow in the grass, birds and butterflies drift by, and a handwritten note waits on a wooden stake. The visitor can plant more flowers and blossom trees, change the weather, and listen to soft background music.

Single file, no build step, no dependencies. Fonts load from Google Fonts.

## Customise

Open `index.html` and edit the `CONFIG` block near the top of the script:

- `to`: who the garden is for
- `from`: how the note is signed
- `intro`: the line on the opening card
- `message`: the paragraphs of the note
- `signoff`: the line before your name

## Publish with GitHub Pages

1. Create a new repository on GitHub, for example `quiet-garden`.
2. Upload `index.html` and `README.md` to the repository root.
3. Go to Settings, then Pages. Under Build and deployment, choose Deploy from a branch, select `main` and `/ (root)`, then Save.
4. After a minute the site is live at `https://YOUR-USERNAME.github.io/quiet-garden/`.

## Notes

- Music needs a click first (browser rule), so the opening card has an Enter button.
- Flowers planted by the visitor are remembered in their own browser only.
