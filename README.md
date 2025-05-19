# media-rules-with-min-width-and-max-width.# CSS Media-Query Demo

A tiny HTML page that shows how different **media queries** can change the
background colour based on the viewport width. Handy as a starter reference for
responsive-design practice.

## Live preview

Open `index.html` in your browser and resize the window (or use DevTools
responsive mode). You should see these colour changes:

| Width range (px) | Background |
| ---------------- | ---------- |
| ≥ 1601           | `seagreen` |
| 1201 – 1600      | `limegreen` |
| 481 – 1200       | `powderblue` |
| 320 – 480        | `lightsalmon` |
| \< 320           | `aquamarine` (default) |

## Files

- **index.html** – contains HTML markup *and* the CSS with media queries.
- *(optional)* `cat.jpeg`, `dog.jpeg` – sample images if you extend the page.

## How to run locally

```bash
# clone your repo
git clone https://github.com/your-username/your-repo.git
cd your-repo

# open the page
# double-click index.html or serve with a simple HTTP server
python -m http.server    # then open http://localhost:8000
