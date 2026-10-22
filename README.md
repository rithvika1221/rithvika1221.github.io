# rithvika1221.github.io

Personal website of Rithvika Devisetti, served at https://rithvika1221.github.io

The site tells her story as a PostgreSQL write-ahead log being replayed, one chapter at a time.
Everything lives in one self-contained file, `index.html` (no build step).

## Updating
Edit `index.html` and commit to `main`. GitHub Pages republishes in a minute or two.
- Each chapter is a `<section class="chapter" data-title="...">`; the `data-title` feeds the "replayed through" status bar.
- All the detailed data (projects, experience, awards, research, academics…) lives in the `DB` object
  inside the `<script>`. Edit a row there and it updates both the inline query results in each chapter
  and the interactive `psql` tab.
- Each chapter's `<details class="q" data-sql="...">` runs that SQL against `DB` and shows the result.
