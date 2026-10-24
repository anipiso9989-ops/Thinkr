# Workspace — Beginner's User Guide

Workspace is a visual, offline-friendly app for collecting notes, connecting ideas, managing tasks, and organizing information across canvases. **A canvas** is the open space where you place items; **a workspace** contains your folders and canvases.

## 1. Start here (2 minutes)

1. Open Workspace. Use **+** in the sidebar to create a **folder** or **canvas**. A folder organizes canvases; a canvas holds your content.
2. Open a canvas and **double-click empty space** (or press **N**) to add a note.
3. Type your idea. Click **Done** or press **Ctrl/⌘ + Enter** to finish editing.
4. Drag your note to move it. Double-click a note (or select it and press **Enter**) to edit again.
5. Make a second note. Select notes and press **C** to connect them, or drag from a note's connection port to another note. Drag a port into empty space to create a connected note.
6. Press **F** to fit your notes on screen. Your changes save automatically in this browser.

**Tip:** Ctrl is for Windows/Linux; ⌘ is for Mac. Shortcuts generally work when you're *not* typing inside a note.

## 2. Find your way around

| Area | What it does |
| --- | --- |
| **Sidebar** (☰) | Browse folders and canvases; create, rename, move, duplicate, or delete them. |
| **Canvas** | Add, edit, move, connect, and group items. |
| **+ Note** | Create a new note. |
| **Menu ▾ / Tools** | Open tags, cleanup, bookmarks, portals, and other canvas utilities. |
| **Actions** | Work with selected items: style, group, organize, transfer, export, or delete. |
| **Search** | Find notes across canvases (**Ctrl/⌘ + K**). |
| **Commands** | Search for actions by name (**Ctrl/⌘ + P**); great when you can't find a button. |
| **?** | See the built-in keyboard reference. |

### Move around the canvas

- **Pan:** hold **Space** and drag, middle-mouse drag, or scroll/gesture on a trackpad.
- **Zoom:** **Space + mouse wheel**, **Ctrl/⌘ + wheel**, trackpad pinch, or the **− / +** controls.
- **Fit everything:** press **F** or click the fit icon. Click the zoom percentage to reset zoom.
- **Select items:** click one note; **Shift-click** to add more, or drag a selection rectangle on empty canvas. Press **Ctrl/⌘ + A** to select all matching visible notes.
- **Undo / redo:** **Ctrl/⌘ + Z** / **Ctrl/⌘ + Shift + Z**.

## 3. Write and format notes

Click a note to select it, then **Enter** or double-click to edit. Use the editor toolbar for **bold**, *italic*, headings, lists, checklists, links, math, code blocks, and images. You can also type or paste Markdown:

```md
# Heading
**Bold** and *italic*
- Bullet point
- [ ] Task to check
[Website](https://example.com)
`inline code`
$E=mc^2$
```

Type **/** while editing to open the insert menu. Use **Ctrl/⌘ + B** for bold and **Ctrl/⌘ + I** for italic. Click **Done** to stop editing. Notes can also contain linked notes, images, and mathematical expressions; equations render offline.

### Images and files

Drag an **image** or **Markdown (.md)** file onto the canvas, or choose **Add image** from commands. Resize an image by dragging its corner and edit its caption in the caption area. With an image selected, open **Image presentation** to adjust crop, rotation, borders, or shadow. Use **Menu ▾** for **Add PDF…**; click the PDF note's **Open** control to read pages, or **Link page** to reference a particular page. Imported content remains part of the workspace's stored data and exports where supported.

## 4. Connect and organize ideas

**Connections:** Select two or more notes and press **C**, or drag a connection port between notes. Select a manually drawn connection to **edit its label, arrow direction, or line style**. Press **S** to toggle connection arrows/spotlight; press **2** to switch between one and two connection levels. Arrowheads show the destination.

**Links inside notes:** Insert a note link using **Ctrl/⌘ + L**, or type **[[** and choose an available heading or named image. Hover over a note link for a preview. Find incoming links through **Links and backlinks** in the command palette.

**Groups:** Select related notes and press **Ctrl/⌘ + G**. Rename or collapse groups from their header; **Ctrl/⌘ + Shift + G** ungroups. For one note, use **Shift + C** to collapse/expand its contents. The **Actions** menu also offers borders/styles, alignment, equal spacing, grids, and **Auto-organize** (**Shift + L**) for selected items.

**Tags:** Select notes → **Actions → Tags** (or search **Edit tags** in Commands). Enter comma-separated labels such as `research, next`. Open **Tags and filters** to show matching notes, require **all/any** tags, search this canvas or the entire workspace, or rename/remove tags. Filters change what's displayed, **not** your saved content.

**Moving between canvases:** Select notes → **Move / copy to canvas**. Internal connections travel with copied/moved notes; links to unselected notes may require attention. Use **Menu → Tools → Create a portal** to add a clickable link to another canvas or a specific note there. A portal needs its destination to exist in the workspace.

## 5. Tasks, tables, and split view

Open **Menu ▾** or **Ctrl/⌘ + P** to find these actions:

| Feature | How to use it |
| --- | --- |
| **New task** | Enter a title/details, choose a status and optional due date. Update status from the task card. |
| **Task board** | See tasks by status; filter or open a task back on its canvas. |
| **New table** | Add columns and rows; edit cells, sort/filter the displayed table, or import/export **CSV** from the table editor. |
| **Add PDF** | Import a PDF as a canvas element, browse its pages, or link to a specific page. |
| **Split view** | Open a second view to reference other canvas content while working. |

For general note checkboxes, use the **Checklist** formatting tool. A checklist inside a note is different from a structured **task** card.

## 6. Useful workspace tools

Access these via **Menu → Tools** or search their names with **Ctrl/⌘ + P**.

- **Canvas cleanup:** Review overlaps, duplicate notes, empty notes, and disconnected notes. Apply fixes individually; use **Undo** if a change isn't right. The tool protects referenced empties and certain special content.
- **Canvas bookmarks:** Save a named view location and zoom level; jump back to it later. Bookmarks are included in canvas backups.
- **Portals:** Jump to another canvas or note from a linked note. Edit or remove the portal using its controls.
- **Focus mode:** **Shift + F** hides distractions; **Esc** exits. Useful for reading or presenting a canvas.
- **Recovery history:** Use Commands → **Recovery history** to inspect available recovery checkpoints, or **Save recovery checkpoint** before major changes.
- **Theme:** Use the light/dark toggle at the top.

## 7. Save, export, import, and back up

**Autosave:** The app saves locally in your **current browser**. This is not the same as online sync. Avoid clearing browser data if you haven't exported a backup.

**Export:** Choose **Export canvas** in the menu/commands; select the **entire canvas** or **selected elements**, then a format:

| Format | Best for |
| --- | --- |
| **`.cnvx`** | **Backups and transfer** — preserves canvas structure, layout, connections, images, and supported metadata. |
| **`.md`** | Readable notes — exports text, group labels, and connection descriptions; not a fully editable visual canvas. |
| **`.png`** | Sharing a picture of the canvas. |

**Import:** Click **↥ Import** or search **Import canvas file (.cnvx)** in Commands to bring a saved canvas back. You can also drop Markdown files onto the canvas to make content.

**Important:** Export `.cnvx` backups regularly, particularly before changing browsers or devices. A portal pointing to another canvas needs that destination canvas to be present too. Back up all related canvases if you rely on cross-canvas links.

## 8. Keyboard shortcuts — essentials

| Action | Shortcut |
| --- | --- |
| New note / edit selected / finish edit | **N** / **Enter** / **Ctrl/⌘ + Enter** |
| Search / all commands / help | **Ctrl/⌘ + K** / **Ctrl/⌘ + P** / **?** |
| Undo / redo | **Ctrl/⌘ + Z** / **Ctrl/⌘ + Shift + Z** |
| Connect notes / fit canvas | **C** / **F** |
| Group / ungroup | **Ctrl/⌘ + G** / **Ctrl/⌘ + Shift + G** |
| Link to note / backlinks | **Ctrl/⌘ + L** / **Ctrl/⌘ + Shift + L** |
| Focus mode / collapse selection | **Shift + F** / **Shift + C** |
| Auto-organize / connection arrows | **Shift + L** / **S** |
| Delete selection | **Delete** or **Backspace** |
| Copy / paste selected elements | **Ctrl/⌘ + C** / **Ctrl/⌘ + V** |

For the complete list, click **?** in the app.

## 9. Troubleshooting

- **Can't see your notes?** Press **F**, clear active **Tags and filters**, and check you're on the right canvas.
- **Can't edit?** Double-click the note or select it and press **Enter**. For tables and PDFs, use their specialized edit/open controls.
- **Can't find a feature?** Press **Ctrl/⌘ + P** and type the action name.
- **Can't pan?** Hold **Space** while dragging rather than dragging a note.
- **Portal doesn't open?** Verify the destination canvas/note still exists.
- **Storage error or moving devices?** Export `.cnvx` while you still have access. Browser-local saves don't automatically follow you to another device.

**A good first project:** Create a canvas, add three notes, connect them, give two notes a tag, group them, save a bookmark, then export a `.cnvx` backup. That covers the core workflow.

---
*This guide describes the features visible in the supplied `workspace.html` app. Menu labels may vary slightly with screen size or app state.*
