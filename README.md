# Article Notes

A web app for working through a folder of scientific PDFs: short notes on every paper, search across them, and a PDF viewer that jumps straight to the quoted passage and highlights it.

- Notes as editable blocks: headings, bullets, coloured callouts, quotes tied to a PDF page, images pasted with Ctrl+V
- Reading progress for every paper: unread / reading / read, with a progress bar
- Search by words, authors, years and tags; filter by folder, importance and progress
- Built-in PDF viewer (pdf.js): the article page only, zoom, fit to width, selectable text, the quote highlighted
- Translator both ways, including text selected in the PDF
- Dark theme

All notes and PDFs stay on your own computer. Nothing is uploaded to this repository.

## Getting started

1. Put `index.html` and the `pdfjs/` folder next to your PDFs.
2. Open `index.html` in Chrome and load your `notes_data.json` — or start from an empty one.
3. Connect the articles folder (button in the PDF panel) so PDFs open inside the page.
4. Save the file now and then: notes are written back to `notes_data.json`.

SDI · LAMMC — Department of Orchard Plant Genetics and Biotechnology
