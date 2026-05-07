# PDF Editor

Single-file browser-based PDF editor. No install, no server, no dependencies — open `index.html` and go.

## Features

| Feature | Details |
|---|---|
| Open PDF | File picker or drag & drop |
| Page thumbnails | Sidebar with drag-to-reorder, right-click context menu |
| Page management | Move up/down/first/last, delete pages (undo-able) |
| Text annotations | Click to place, inline edit, drag to reposition, color + font size |
| Freehand draw | Canvas overlay per page, configurable color + stroke width |
| Eraser | Erase parts of freehand drawing without clearing the whole page |
| Signatures | Draw with mouse/touch or type name with font picker |
| Undo / Redo | Full history — text, signatures, drawing, delete, page reorder |
| Zoom | 50% – 200% via dropdown or keyboard shortcuts |
| Page jump | Click the page indicator (e.g. "3 / 12") to type a page number |
| Save | Downloads modified PDF with all annotations embedded |

## Keyboard shortcuts

| Key | Action |
|---|---|
| `V` | Select tool |
| `T` | Text tool |
| `D` | Draw tool |
| `E` | Erase tool |
| `S` | Sign tool |
| `+` / `Ctrl+=` | Zoom in |
| `-` / `Ctrl+-` | Zoom out |
| `←` / `→` | Previous / next page |
| `Del` / `Backspace` | Delete selected annotation |
| `Escape` | Deselect / close menus |
| `Ctrl+O` | Open PDF |
| `Ctrl+S` | Save PDF |
| `Ctrl+Z` | Undo |
| `Ctrl+Y` / `Ctrl+Shift+Z` | Redo |

## Stack

- [PDF.js](https://mozilla.github.io/pdf.js/) — render pages
- [pdf-lib](https://pdf-lib.js.org/) — embed annotations and save
- Vanilla JS, no framework, no build step
