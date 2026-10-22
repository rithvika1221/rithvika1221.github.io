# rithvika1221.github.io

Personal website of Rithvika Devisetti, served at https://rithvika1221.github.io
(same psql-terminal design as rithvika.dev, with updated content).

The whole site is one self-contained file: `index.html` (no build step).

## Updating
Edit `index.html` and commit to `main`; GitHub Pages republishes in a minute or two.
- Each section is a `<section id="...">` with a SQL "query" heading (about, research, opensource, projects, experience, academics, awards, skills).
- The interactive shell's tables are the `const DB = {...}` object in the `<script>`; update it alongside the sections.
