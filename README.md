# ⬡ Bookmark Manager

A fast, self-contained bookmark manager that runs entirely in the browser — no build step, no server, no accounts. One HTML file. Host it anywhere.

---

## Features

### Import
| Source | Formats |
|---|---|
| Browser export | `.html` — Chrome, Firefox, Edge, Safari (Netscape format) |
| Chrome JSON | `.json` — preserves folder structure |
| Plain URLs | `.txt` — one URL per line |
| Paste | Paste URLs directly into the text field |
| Drag & drop | Drop any supported file onto the import zone |

Duplicate URLs are detected and skipped automatically on import.

### Folders
- Create nested folder hierarchies
- Rename or move folders at any time
- Drag a bookmark row onto a sidebar folder to move it instantly
- Deleting a folder moves its bookmarks to Uncategorized (nothing is lost)
- Folder counts show the total including all sub-folders

### Bookmarks
- Add bookmarks from the top bar with title, URL, and folder assignment
- Edit title, URL, folder, and optional notes per bookmark
- Drag to reorder within any view
- Multi-select with checkboxes — bulk move, bulk delete
- Right-click context menu on any row

### Export
| Format | Use case |
|---|---|
| **HTML (flat)** | Import into any browser — Netscape bookmark format |
| **HTML (with folders)** | Import into any browser, folder structure preserved |
| **JSON** | Full data backup — title, URL, folder, date, notes |
| **CSV** | Open in Excel / Sheets |
| **Markdown** | Documentation, wiki pages |
| **Plain text** | URL list only |

Export scope options: all bookmarks, selected only, current search results, or active folder.

### Search & Sort
- Instant search across title, URL, domain, and notes
- Sort by title, domain, date added (newest/oldest), or manual drag order
- Search is scoped to the active folder when one is selected

---

## Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl+F` | Focus search |
| `Ctrl+N` | Open add bookmark bar |
| `Ctrl+S` | Save (when edit modal is open) |
| `Ctrl+A` | Select all visible bookmarks |
| `Escape` | Close any open modal or panel |

---

## Getting Started

### Option 1 — GitHub Pages (recommended)

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your manager is live at `https://your-username.github.io/repo-name`

### Option 2 — Run locally

Download `Advanced_Bookmark_Manager.html` and open it in any modern browser. No server needed.

### Option 3 — Any static host

Upload the single HTML file to Netlify Drop, Cloudflare Pages, or any web server. No configuration required.

---

## Data & Privacy

All data is stored in your browser's `localStorage`. Nothing is sent to any server. There are no analytics, no tracking, and no external requests except for favicon images (fetched from Google's favicon service — can be removed by editing the source).

Clearing browser data or switching browsers will clear your bookmarks. Use **Export → JSON** as a backup.

---

## Browser Support

Works in all modern browsers. Requires JavaScript enabled.

| Browser | Supported |
|---|---|
| Chrome / Edge | ✓ |
| Firefox | ✓ |
| Safari | ✓ |
| Mobile browsers | ✓ |

---

## File Structure

```
bookmark-manager/
└── Advanced_Bookmark_Manager.html   # The entire app — HTML, CSS, and JS in one file
└── README.md
```

No dependencies. No `package.json`. No build step.

---

## Importing Your Existing Bookmarks

**From Chrome:**
Chrome menu → Bookmarks → Bookmark Manager → ⋮ → Export bookmarks
Import the `.html` file — folder structure is preserved.

**From Firefox:**
Bookmarks menu → Manage Bookmarks → Import and Backup → Export Bookmarks to HTML
Import the `.html` file.

**From Safari:**
File → Export → Bookmarks…
Import the `.html` file.

---

## License

MIT — do whatever you want with it.
