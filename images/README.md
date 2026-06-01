# Images Folder

This is where you put photos and images that will appear on the Barker Family website.

## Folder Organization

- `haiti/` — Photos from your time in Haiti
- `radio/` — Ham radio related photos (shacks, equipment, QSL cards, etc.)
- `garry/` — Photos of Garry
- `mitzi/` — Photos of Mitzi
- `general/` — Any other images used across the site

You can add more folders later if needed (for example `family/`, `events/`, etc.).

## How to Add Photos

1. Drag and drop your photos into the appropriate folder above.
2. Use clear, descriptive filenames, for example:
   - `haiti-1980-port-au-prince.jpg`
   - `garry-shack-2024.jpg`
   - `mitzi-garden-01.jpg`
3. Avoid names like `IMG_1234.jpg` or `photo copy 2.jpg` — they become hard to manage.

## How to Use Images on the Website

Once a photo is in this folder, reference it in any HTML file like this:

```html
<img src="images/haiti/market-day.jpg" alt="Market in Haiti, 1980">
```

Example for Garry's photo on the home page:

```html
<img src="images/garry/portrait-2023.jpg" alt="Garry Barker, AG7SB">
```

## After Adding Photos

You must commit and push the new images so they appear on the live website:

```bash
git add .
git commit -m "Add new Haiti photos"
git push
```

Then wait 30–60 seconds and reload the site.

## Tips

- Keep file sizes reasonable (under 1–2 MB per photo is plenty for web use).
- You can resize photos on your Mac using Preview or Photos app before adding them.
- If you have many large original files you want to keep but not publish, put them in a separate folder outside this repo (for example in `~/Pictures/Barker-Originals/`).

---

Happy to help organize or add any of these images to the actual pages when you're ready.
