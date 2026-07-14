# Barker Family Website

Personal site for Garry (AG7SB) and Mitzi Barker — amateur radio, writing, and Haiti.

**Content © Garry & Mitzi Barker.** Please do not reuse photos without permission.

## Live site

https://erasmusb.github.io/ErasmusBWebPage-github.io/

## Pages

| File | Content |
|------|---------|
| `index.html` | Home — introductions |
| `amateur.html` | Ham radio history, call signs, Worked All States |
| `writings.html` | Books and links |
| `haiti.html` | Haiti story and photos |

## Repository layout

```text
├── index.html, amateur.html, writings.html, haiti.html
├── css/
│   └── styles.css
├── images/
│   ├── garry/      # Portraits of Garry
│   ├── mitzi/      # Portraits of Mitzi
│   ├── haiti/      # Haiti photos
│   ├── writing/    # Book covers
│   ├── radio/      # Ham radio photos (add when ready)
│   └── general/    # Shared / miscellaneous images
├── docs/
│   └── worked-all-states.md   # WAS notes (source of truth for remaining states)
├── README.md
└── .gitignore
```

## Edit and publish

1. Edit HTML/CSS, or add images under the matching `images/` folder.
2. Commit and push to `master`:

```bash
git add .
git commit -m "Describe your change"
git push
```

3. Wait about a minute, then reload the live site.

See [images/README.md](images/README.md) for photo naming and size tips.

## Notes

- Filenames use lowercase and hyphens (e.g. `mitzi-cartoon.jpeg`).
- Keep web photos reasonably small (ideally under ~500 KB each). Store full-resolution originals outside this repo.
- GitHub Pages serves from the `master` branch root.
