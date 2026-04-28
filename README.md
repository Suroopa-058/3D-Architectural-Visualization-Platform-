# ArchViz 3D — Architectural Visualization Platform

A web-based 3D architectural visualization platform that allows clients to preview and customize house designs before construction — similar to SolidWorks/FreeCAD but browser-based.

## 🏗️ Features

- **Interactive 3D View** — Real-time 3D house rendering using Three.js (drag to rotate, scroll to zoom)
- **Floor Plan View** — Top-down 2D floor plan with all rooms labeled
- **Front & Side Elevation Views** — Professional architectural elevation drawings
- **Wall Color Customization** — 12 color options with live 3D update
- **Floor Material Selection** — Hardwood, Marble Tile, Concrete, Parquet
- **Room Details Panel** — Area, height, windows, doors per room
- **Touch Support** — Works on mobile and tablet

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **3D Rendering:** Three.js (r128)
- **2D Drawing:** HTML5 Canvas API
- **Fonts:** Google Fonts (DM Sans + Playfair Display)

## 🚀 How to Run

Just open `index.html` in any modern browser — no build tools or installations needed!

```bash
# Option 1: Direct open
open index.html

# Option 2: Local server
npx serve .
# or
python -m http.server 8000
```

## 📁 Project Structure

```
ArchViz3D/
├── index.html      # Complete app (single file)
└── README.md       # This file
```

## 🎮 Controls

| Action | How |
|--------|-----|
| Rotate 3D | Click and drag |
| Zoom | Mouse scroll |
| Change view | Toolbar buttons |
| Change wall color | Click color swatches |
| Change floor | Click floor buttons |
| Select room | Click room in sidebar |

## 🔮 Future Plans (Backend)

- [ ] User authentication (JWT)
- [ ] Save/load custom designs (Node.js + MySQL)
- [ ] Export design as PDF
- [ ] Share design with client via link
- [ ] Multiple house templates

## 👩‍💻 Developer

**Suroopa B** — Full Stack Developer  
Sri Krishna College of Engineering and Technology, Coimbatore
