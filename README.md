# Requirements Composer

A single-file, browser-based editor for writing product and business requirement documents.

- **Templates:** Blank, Product Requirements (PRD, 12 sections) and Business Requirements (BRD, 11 sections), each with example rows so you only replace the bracketed text.
- **Editor:** headings, bold/italic, lists, callouts, tables (with add-row), dividers, and Markdown-style shortcuts (`#`, `##`, `###`, `-`, `1.`, `>` followed by a space).
- **Documents:** sidebar with search, status (Draft / In review / Approved), autosave and delete.
- **Export:** Markdown and PDF (via jsPDF + jspdf-autotable).
- **Storage:** uses the claude.ai artifact `db` capability when available (per-user), otherwise falls back to `localStorage` in the browser.

## Usage

Open `index.html` in a browser. No build step is needed.
