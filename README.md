# Paint95 🖌️

A Windows 95-inspired drawing studio built entirely with vanilla HTML, CSS, and JavaScript — no frameworks, no build step, no dependencies.


🎨   [Live Demo](https://paint95.netlify.app)



## Features

**Drawing Tools**
- Brush — freehand strokes with smooth line interpolation
- Eraser — paints background color with adjustable size
- Fill — flood fill with edge tolerance (works on anti-aliased edges)
- Eyedropper — sample any pixel color from the canvas
- Line, Rectangle, Ellipse — shape tools with live preview
- Selection — drag to select, Delete to clear region
- Text — click to place, Enter to stamp onto canvas

**Canvas & Colors**
- Adjustable brush size (1–100px) and opacity
- 32-color retro palette with shift/right-click to set background color
- Hex color input with live preview
- Custom foreground, background, and canvas fill colors
- Neon mode — dark canvas with glow effect on all strokes

**Layers**
- Named layer labels for organization
- Toggle visibility, merge layers, add/delete

**File Operations**
- Save to browser `localStorage` (persists across sessions)
- My Drawings gallery — browse, open, and delete saved work
- Download as PNG

**UI**
- Authentic Windows 95 chrome — beveled buttons, title bars, taskbar, Start menu
- Pixel-art desktop icons with proper Win95 bevel shading
- Draggable, minimizable, resizable windows
- Working clock in taskbar
- 2× zoom mode for pixel-level detail
- Full keyboard shortcuts

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `B` | Brush |
| `E` | Eraser |
| `F` | Fill |
| `I` | Eyedropper |
| `L` | Line |
| `R` | Rectangle |
| `O` | Ellipse |
| `S` | Select |
| `T` | Text |
| `[` / `]` | Decrease / Increase brush size |
| `Ctrl+Z` | Undo |
| `Ctrl+Y` | Redo |
| `Ctrl+S` | Save to My Drawings |
| `Ctrl+D` | Download PNG |
| `Delete` | Clear selection |


## Tech

Pure HTML · CSS · JavaScript - single file, zero dependencies, zero build step.
