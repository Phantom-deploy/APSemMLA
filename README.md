# MLA Citation Builder

A single-page, dependency-free site that turns source details into MLA citations, using the
formulas from `MLA Cheat Sheet.pdf`.

- **Nine source types** — book (1 or 2 authors), anthology, a work within an anthology,
  print magazine/newspaper article, scholarly journal article, page on a website,
  article on a website, YouTube video.
- **Blank fields are skipped**, per the cheat sheet tip ("when a source is missing one of the
  required items, skip it").
- **Live preview** of the citation plus the matching parenthetical (in-text) citation.
- **Source list** saved in your browser (`localStorage`) — edit or delete any entry.
- **Combined page** — tick the sources you want and copy a full *Works Cited* or
  *Works Consulted* page: alphabetized, hanging indent, double spaced.
  "Copy formatted" preserves italics and indenting when pasted into Google Docs or Word.

## Use it

Open `index.html` in any browser, or serve the folder:

```
python3 -m http.server
```

No build step, no dependencies, no network requests — one ~20 KB HTML file.
