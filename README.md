## 1. Basic Navigation

### Panning
![SPACE - Pan](https://img.shields.io/badge/SPACE-Pan-007ACC?style=for-the-badge)

Hold **Space** and drag your mouse anywhere on the canvas. Perfect for exploring massive diagrams.

### Zooming
![Ctrl + + - Zoom In](https://img.shields.io/badge/Ctrl%20%2B%20%2B-Zoom%20In-28A745?style=for-the-badge) ![Ctrl + - - Zoom Out](https://img.shields.io/badge/Ctrl%20%2B%20%E2%88%92-Zoom%20Out-DC3545?style=for-the-badge)

- **Mouse wheel** — zoom in/out with mouse position as center
- **Keyboard** — `Ctrl + +` / `Ctrl + =` (in) or `Ctrl + -` (out)

The background grid scales dynamically for perfect alignment at any zoom level.



## 2. Managing Components

### Adding Nodes & Groups
Use the **toolbar** (top center):
- **Add Node** → creates a new service node at your current view center
- **Group** → creates a resizable dashed boundary (great for VPCs, Availability Zones, Kubernetes clusters, etc.)

**Resizing Groups**: Drag the dotted handle at the bottom-right corner.

**Renaming**: Right-click any node or group → **Rename**.



## 3. Advanced Node Features

### Custom Icons
Right-click any node → **Upload Icon** → choose PNG/SVG (AWS, Azure, GCP, Kubernetes, databases, etc.).

### Connections (the coolest part)
![SHIFT + Q - Connect](https://img.shields.io/badge/SHIFT%20%2B%20Q-Connect-FF5722?style=for-the-badge)

**How to draw a connection:**
1. Hold **`Shift + Q`**
2. Click and hold on the **source** node (it turns green)
3. Drag the glowing dashed "ghost line" to the **target** node
4. Release → connection appears!

**Two-Way Links**: Right-click any existing line → **Toggle Two-Way** (bidirectional data flow).



## 4. Simulation Mode

Click **SIMULATE** in the top toolbar.

- Editing is locked (safe mode)
- Real-time **blue data packets** automatically flow along every connection
- Watch your entire architecture come alive!

Switch back to **EDIT** anytime.



## 5. Persistence

**Export** — Click **Export** → downloads `architecture_*.json.gz` (includes everything: positions, icons, groups, connections).

**Import** — Click **Import** or just drag & drop your `.json.gz` file onto the canvas.

**Clear** — Red button (with confirmation) to start fresh.

Document are written by AI 70%
