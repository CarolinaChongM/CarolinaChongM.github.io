# carolinachongm.github.io

Personal website of Carolina Chong-Montenegro, live at <https://carolinachongm.github.io>.

It's plain HTML and CSS. There's nothing to install or build. Edit a file, push it to GitHub, and the site updates in a minute or two.

## What's where

| File | What it holds |
| --- | --- |
| `index.html` | All the page content: intro, About, Research, Publications, Experience, Contact |
| `assets/css/style.css` | Colours, fonts and layout. The colours are at the top under `:root` |
| `assets/img/` | Photos: `wreck-*.webp` (the opening image), `portrait.jpg`, `og-image.jpg` (the preview shown when the link is shared) |
| `resume.pdf` | The CV behind the "Download CV" button. Replace this file to update it, and keep the same name |
| `publications/`, `experience/`, `projects/`, `author/`, `authors/` | Redirects, so links to the old site's pages still work |

## Common updates

Open `index.html` in any text editor. RStudio, VS Code and TextEdit (in plain-text mode) all work.

**Add a publication.** Search for `pub-year`. Copy a whole `<li class="pub"> … </li>` block, paste it at the top of the right year, and change the link, title, authors and journal. For a new year, copy a whole `<div class="pub-year"> … </div>` block. Put your own name in `<b> </b>` and species names in `<i> </i>`. Then update the count in the sentence above the list ("Twelve peer-reviewed articles…").

**Change your job or bio.** Edit the intro paragraph near the top, the About section and the first entry under Experience.

**Update the CV.** Replace `resume.pdf` with the new file, keeping the same name.

**Change the date in the footer.** Search for `Last updated`.

## Preview before publishing

Double-click `index.html` to open it in your browser. Refresh after each edit.

## Publish

With GitHub Desktop: write a short summary of what you changed, click **Commit to main**, then **Push origin**. The site updates within a couple of minutes.

From Terminal:

```
git add -A
git commit -m "Describe what you changed"
git push
```

## Credits

Fonts: [Spectral](https://github.com/productiontype/Spectral) and [Archivo](https://github.com/Omnibus-Type/Archivo). Both use the SIL Open Font License; see `assets/fonts/LICENSE.txt`.
