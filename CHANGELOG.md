# Changelog

## [1.1.0] - 2026-03-26

### Added
- **Deep content search** — search bar now indexes full text content of all 319 notes on first keystroke (lazy-built for performance). Matches nav titles, data-search attributes, AND note body content. Debounced at 120ms for low-resource clients. Match count displayed below search bar.
- **Collapsible sidebar toggle** — cat logo in the sidebar header functions as a toggle to collapse/expand the navigation pane. Caret indicator rotates to show state. Sidebar collapses to 52px showing only the cat icon.
- **Back-to-top button** — floating button appears after scrolling 400px in the content pane. Smooth-scrolls to top on click.
- **Breadcrumb navigation** — shows `Home / Category / Note Title` at the top of the content pane when viewing a note. Home link is clickable.
- **Collapse/Expand All** — toolbar button above the nav groups toggles all 28 categories open or closed at once.
- **Recently viewed notes** — collapsible "Recent" section tracks the last 5 visited notes in session memory. Persists collapse state when navigating between notes. No localStorage used.
- **In-note table of contents** — auto-generated from h2/h3 headings for notes with 3+ headings. Collapsible `<details>` block at the top of note body with smooth-scroll to headings.
- **Copyable code blocks** — all 3,265 `<pre><code>` blocks have a "Copy" button that appears on hover. Copies to clipboard with "Copied!" confirmation.
- **Styled Obsidian callouts** — 582 callout markers (`[!tip]`, `[!warning]`, `[!important]`, `[!exam]`, `[!info]`, `[!danger]`, `[!critical]`, `[!check]`, `[!note]`) converted to color-coded callout boxes with icons and labels.
- **Blockquote rendering** — 623 plain blockquote lines (`> text`) converted from raw `&gt;` text to proper `<blockquote>` elements with existing CSS styling.
- **PortableJPTv2 external link** — Dashboard section includes a link to https://awcl.github.io/PortableJPTv2/ that opens in a new tab.
- **Responsive content pane** — content area uses `max-width: min(900px, 100%)` with `clamp()` padding for half-screen and mobile layouts.

### Changed
- **SlabFile renamed to Quick Reference** — category renamed and repositioned directly below Dashboard in the sidebar navigation. Section headers inside notes updated to match.
- **Cheat Sheets cleaned up** — removed 2 duplicate `ejpt-cheat-sheet` entries (near-identical ~90KB copies). Section now contains 3 items: CheatSheets MOC, eJPT Cheat Sheet (enriched), GTFOBins.
- **JavaScript minified and optimized** — replaced 321+ individual nav-link click listeners with single document-level event delegation. Cached DOM queries. Debounced search input. No comments or unnecessary whitespace, but structure remains readable and modifiable.
- **CSS cleaned up** — removed duplicate rules, eliminated conflicting inline styles, consolidated sidebar transition definitions.
- **Note count updated** — 321 → 319 to reflect removed duplicates.
- **Search placeholder** — updated to "Search notes & content..." to reflect deep search capability.

### Removed
- Duplicate `ejpt-cheat-sheet` section (90KB)
- Duplicate `ejpt-cheat-sheet-cheat-sheets` section (91KB)
- Old hamburger menu button
- Redundant CSS definitions

### Security
- JavaScript contains no `eval()`, no `document.cookie`, no `localStorage`, no external API calls
- Only external resource: Google Fonts import
- All shell/payload references in study notes are HTML-entity-escaped educational content
- AV webshell alerts are false positives on signature strings in pentesting study material

## [1.0.0] - 2026-03-25

### Initial Release
- 321-note offline reference site built from Obsidian vault
- Single self-contained `index.html` file
- 28 navigable categories with collapsible sidebar
- Instant keyword search across note titles
- 1,492 internal cross-links between notes
- Nmap Cheatsheet rebuilt from ekol-x9/nmap-cheatsheet
- Cat logo branding
- Ctrl+K search shortcut, Esc to clear
- Hash-based URL navigation
- Mobile-responsive layout
- BSD 3-Clause license
