# MDpad

A fast, minimal Markdown editor that runs entirely in your browser. No accounts, no servers, no uploads — just open and write.

## Features

**Editor**
- Live split-pane preview (resizable by dragging the divider)
- Edit-only and preview-only view modes
- Monospace editor with syntax-aware caret
- Auto-saves to `localStorage` — content persists across sessions
- Word, character, and line counts in the status bar
- Cursor position (line / column)

**Formatting**
- Right-click context menu on selected text
- Keyboard shortcuts: `⌘B` bold, `⌘I` italic, `` ⌘` `` inline code, `⌘1/2/3` headings
- Sidebar with all formatting options organized by category
- 6 built-in templates (README, Blog post, Meeting notes, Changelog, Tech doc, Daily journal)
- Save any document as a custom reusable template

**Command Palette (`⌘K`)**
- 33 commands across Format, Templates, Clean, View, and Tools groups
- Fuzzy search, keyboard navigation (`↑↓`), run with `↵`
- Preserves your text selection — formatting commands wrap the selected text even after navigating the palette

**Find & Replace**
- Highlight overlay renders all matches in purple directly in the editor without stealing focus
- Navigate matches with `↑` / `↓` buttons while continuing to type in the search field
- Current match highlighted with a stronger accent + glow
- Replace one at a time or all at once (case-insensitive)
- Capped at 1,000 matches to prevent browser slowdown

**Clean tools**
- Fix spacing (collapse excess blank lines)
- Trim leading / trailing blank lines
- Title-case or sentence-case all headings
- Strip all Markdown to plain text

**Export**
- Export as styled standalone HTML file
- Export as `.md` file
- Copy raw Markdown to clipboard

**Other**
- Light / dark theme toggle
- Skeleton loading screen
- Unsaved changes pulse indicator

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `⌘K` | Open command palette |
| `⌘B` | Bold |
| `⌘I` | Italic |
| `` ⌘` `` | Inline code |
| `⌘1` / `⌘2` / `⌘3` | Heading 1 / 2 / 3 |
| `⌘F` | Find & replace |
| `Esc` | Close palette / find bar / modal |

## Usage

Just open `index.html` in a browser. No build step, no dependencies, no install.

To host on GitHub Pages: push the repo and enable Pages from the `main` branch root. Done.

## Stack

Single HTML file — HTML, CSS, and vanilla JS. No frameworks, no bundler, no build step. The only external resources are two Google Fonts loaded at runtime (`DM Sans` and `JetBrains Mono`).

## Privacy

Everything stays in your browser. Content is saved to `localStorage` only. Nothing is ever sent anywhere.

## License

MIT
