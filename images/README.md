# Images

Photos and graphics used on the Barker Family website.

## Folders

| Folder | Use for |
|--------|---------|
| `garry/` | Photos of Garry |
| `mitzi/` | Photos of Mitzi |
| `haiti/` | Photos from Haiti |
| `writing/` | Book covers and writing-related images |
| `radio/` | Ham radio (shack, gear, QSL cards) |
| `general/` | Shared images used across pages |

## Naming

Use **lowercase** and **hyphens**:

- Good: `garry-shack-2024.jpg`, `haiti-market.jpg`
- Avoid: `IMG_1234.jpg`, `Photo Copy 2.JPG`, mixed case

## Adding photos

1. Put the file in the right folder.
2. Resize for the web if needed (about 1200–1600 px on the long edge is plenty).
3. Aim for under **1–2 MB** per image (under ~500 KB is better).
4. Reference it in HTML:

```html
<img src="images/haiti/market-day.jpg" alt="Market in Haiti">
```

5. Commit and push so it appears on the live site:

```bash
git add images/
git commit -m "Add new Haiti photos"
git push
```

## Originals

Keep full-resolution camera files **outside** this repository (for example `~/Pictures/Barker-Originals/`). Only web-sized copies belong here.
