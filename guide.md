# Thinkr guide

Open `index.html` in your browser. In this guide, **Mod** means **Ctrl** on Windows/Linux or **Cmd** on Mac. Canvas shortcuts apply when you are not typing in a note.

## Write

- Press **N** or double-click empty canvas space to create a note and start typing.
- Paste text or Markdown onto the workspace to create a populated note. Paste inside an open note to insert it there.
- Double-click a note, or select it and press **Enter**, to edit.
- **Enter** inserts a newline, including on empty lines. Lists and quotes continue automatically; Enter on an empty item exits them.
- Press **Mod + Enter** or **Esc** to finish. Notes grow as content is added.

Markdown formats live. Its markers appear when your cursor is on the relevant element and hide when you move away; the formatting stays visible.

| Format | Type |
| --- | --- |
| Heading | `# Heading` through `###### Heading` |
| Bold / italic | `**bold**` / `*italic*` |
| Strikethrough | `~~text~~` |
| Bullet / numbered list | `- Item` / `1. Item` |
| Checklist | `- [ ] Task` or `- [x] Done` |
| Quote | `> Quote` |
| Link | `[Label](https://example.com)` |
| Inline code | Text surrounded by single backticks |
| Code block | Opening and closing lines of three backticks; optionally add a language after the opening fence |
| Horizontal rule | `***` on its own line |
| Math | `$x^2$` inline; `$$x^2$$` on its own line for display math |
| Table | Pipe-separated rows with a separator row such as `| --- | --- |` |

Use **Mod + B/I** for bold/italic, the editing toolbar for formatting, or type **/** for the insertion menu. Use arrow keys and Enter to choose a menu item. Click checklist boxes to toggle them.

## Images and files

Paste an image onto the workspace or into an edited note. You can also choose **Add image** in the command palette or use the image control while editing.

Drag an image’s bottom-right corner to resize it without changing its proportions. Hover over an image to add a caption; click an existing caption to edit it. Standalone images also offer **Edit caption** in their three-dot menu.

Drop images, `.md`, `.markdown`, or `.txt` files onto the canvas to create elements. Drop `.thinkr` files to import canvases. Pasted and uploaded images are stored with the canvas and included in `.thinkr` exports.

## Move and organize

- **Pan:** Space + drag, middle-button drag, or scroll over the canvas.
- **Zoom:** Mod + `+` / `-`, Mod + wheel, trackpad pinch, or the bottom-right controls. Press **F** to fit everything.
- **Move:** drag a note’s thin top bar or a standalone image.
- **Resize a note:** drag its bottom-right corner.
- **Select:** click an element. Shift-click adds/removes selection; drag empty space to select an area. **Mod + A** selects all.
- **Navigate:** Tab / Shift + Tab cycles notes; arrow keys navigate nearby notes.
- **Duplicate / delete:** Mod + D / Delete or Backspace.
- **Undo / redo:** Mod + Z / Mod + Shift + Z. Mod + Y also redoes.

Moving elements snap to the grid and nearby alignment guides. Hold **Alt** while dragging to bypass snapping.

Select multiple elements and press **Mod + G** to group them, optionally with a label. Drag the group header or a selected member to move the group. Alt-drag a member to move it independently. Use the group menu to rename it, or **Mod + Shift + G** to ungroup.

The selected-element toolbar offers actions and monochrome border styles. Each element’s **···** menu and the canvas right-click menu expose contextual actions.

## Connect and link

For visible connections, drag a note’s small side square onto another note. Alternatively, select notes and press **C**; with one selected, click the destination. Select a connection and press Delete to remove it.

For a clickable link inside text, edit or select a text note and press **Mod + L**, then choose another note. Click the link to jump there; while editing, use Mod-click. Open **Links & backlinks** from a note’s menu to see incoming and outgoing links.

## Canvases and controls

Use the sidebar buttons to create canvases and folders. Click a canvas to open it; use `[+]` / `[-]` to expand or collapse folders.

Each sidebar item’s **···** menu offers rename, duplicate, move, and delete. Drag canvases above/below other canvases to reorder them, or onto a folder to move them. The top-left menu button collapses the sidebar.

- **Mod + K:** search the current canvas, including image captions. Choose a result to center and highlight it.
- **Mod + P:** open the command palette for app actions, including theme switching and recovery.
- **?:** show keyboard help.
- **Esc:** close a menu, finish editing, or clear selection.

## Save, recover, and export

Thinkr saves automatically in this browser. Watch the save status before closing. Browser data clearing, private browsing, or changing browsers/devices can make locally saved work unavailable; use exports for backups.

Open **Recovery history** from the command palette. Thinkr keeps up to 20 checkpoints per canvas. Choose **Save recovery checkpoint** for a manual version. Select a checkpoint to restore it; use **All canvases · include deleted** to recover deleted canvases. The current version is saved before restoration, and restoration can be undone.

Use **Export** to download:

- **Thinkr:** the portable backup, preserving notes, embedded images, captions, groups, links, connections, and layout. Use **Import** to reopen it. External image URLs must be downloadable for Thinkr to embed them; paste/upload inaccessible images locally first.
- **Markdown:** note contents with embedded image data, without the canvas layout.
- **PNG:** a visual snapshot. Equations appear as LaTeX source; inaccessible remote images may become labels.

Local notes work without an account or backend. KaTeX math rendering requires its CDN to load; the original math source remains available offline.
