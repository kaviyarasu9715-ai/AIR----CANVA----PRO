# Air Canvas Pro — 3D Blender Modeling Engine

A standalone native Windows desktop application with dual-hand AI tracking and a built-in 3D Blender procedural engine. Draw lines and circles in the air to generate, extrude, zoom, and rotate real 3D objects in real time.

## 5+ Blender 3D Tools
1. **3D Tube (Line Extrusion)**: Draw any line or curve in the air. Upon releasing your finger, it automatically meshes and extrudes into a smooth 3D pipe/cylinder in 3D space.
2. **3D Sphere (Circle Converter)**: Draw a circle in the air. It automatically detects the diameter and spawns a rotating 3D UV Sphere with latitude/longitude mesh rings.
3. **3D Cube**: Spawns a 6-sided quadrilateral shaded cube.
4. **3D Cylinder**: Spawns a vertical column with top/bottom polygon caps and connecting quad walls.
5. **3D Pyramid**: Spawns a 4-sided pyramid with an apex point and base quad.
6. **3D Torus (Blender Donut)**: Spawns the classic Blender donut with dual-radius toroidal geometry.

## 3D Zoom & Manipulation Gestures
- **Two-Hand Zoom (Scale)**:
  - Spread your left and right hands apart in the air $\rightarrow$ **Zoom In** ($Scale \uparrow$).
  - Bring your hands closer together $\rightarrow$ **Zoom Out** ($Scale \downarrow$).
  - Real-time on-screen HUD displays active zoom percentage (e.g. `3D ZOOM: 150%`).
- **3D Orbit & Rotation**:
  - Raise **Index + Middle fingers** together and move your hand to rotate the 3D object along Pitch and Yaw axes.
- **3D Translation (Drag)**:
  - Pinch (Index + Thumb) and move your hand to drag the 3D object anywhere on the screen.

## Shading & Rendering
- **Painter's Algorithm**: Depth-sorted polygon faces with back-to-front ordering.
- **Directional Diffuse Lighting**: Realistic shading calculated from surface normal cross-products against a virtual light source.
- **Turntable Auto-Spin**: Press `Space` to toggle continuous 3D turntable rotation.
- **Wireframe Mode**: Press `W` to toggle between solid shaded polygons and wireframe mesh.

## How to Run
Double-click `run_air_canvas.bat` inside `d:\jarvis tools\hand canva tool\`.
