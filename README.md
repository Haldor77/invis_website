# invis_website

This project converts a Jupyter notebook into a simple static webpage.

## Regenerating `website.html`

1. Install Jupyter and nbconvert:
   ```bash
   pip install jupyter nbconvert
   ```
2. Run nbconvert to produce HTML:
   ```bash
   jupyter nbconvert website.ipynb --to html --output website.html
   ```
3. Open `website.html` in a browser. The page uses `style.css` for basic styling.

The repository already contains a generated `website.html` for convenience.
