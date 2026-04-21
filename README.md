# MDpad
A fast, minimal Markdown editor that runs entirely in your browser *(this README was written with it)*.

## Features

**Editor**
- Live split-pane preview with resizable divider, plus edit-only and preview-only modes
- Auto-saves to `localStorage` — content persists across sessions
- Status bar with word, character, line counts, and cursor position

**Formatting**
- Keyboard shortcuts: `⌘B` bold, `⌘I` italic, `` ⌘` `` inline code, `⌘1/2/3` headings
- Right-click context menu on selected text
- Sidebar with all formatting options organized by category
- 6 built-in templates (README, Blog post, Meeting notes, Changelog, Tech doc, Daily journal) + save your own

**Command Palette (`⌘K`)**
- 33 commands across Format, Templates, Clean, View, and Tools groups
- Fuzzy search with keyboard navigation — formatting commands wrap selected text even after navigating the palette

**Find & Replace (`⌘F`)**
- All matches highlighted inline in the editor without stealing focus
- Navigate matches with `↑` / `↓`, replace one or all at once (case-insensitive)
- Capped at 1,000 matches to prevent slowdown

**Clean tools** — fix spacing, trim blank lines, title/sentence-case headings, strip to plain text

**Export** — styled HTML, `.md` file, or copy raw Markdown to clipboard

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `⌘K` | Command palette |
| `⌘F` | Find & replace |
| `⌘B` / `⌘I` / `` ⌘` `` | Bold / Italic / Inline code |
| `⌘1` / `⌘2` / `⌘3` | Heading 1 / 2 / 3 |
| `Esc` | Close palette / find bar / modal |

## Usage
Visit [manucovr.github.io/MDpad](https://manucovr.github.io/MDpad/). To self-host, push the repo and enable GitHub Pages from the `main` branch root.

## Stack
Single HTML file — HTML, CSS, and vanilla JS. Only external resources are two Google Fonts (`DM Sans` and `JetBrains Mono`).

## Privacy
Everything stays in your browser. Content is saved to `localStorage` only — nothing is ever sent anywhere.

## License
MIT © 2025 Manuel Bernardes
