# Christmas Tree Visualization with Three.js

This project is a 3D visualization of a Christmas tree created using [Three.js](https://threejs.org/). The tree features realistic branches, ornaments, clouds, and a star on top, all rendered in a dynamic 3D environment. The project also includes lighting, a sky background, and interactive controls for exploring the scene.

![christmas_tree](https://github.com/user-attachments/assets/7058b7cf-692e-4d5f-9642-56194cf6abdf)

## Blog
[Blog (written in Japanese)](https://qiita.com/hiranuma/items/ee6aa11b4153b8b44e0f)

## Features

- **3D Christmas Tree**: A procedurally generated tree with branches and a trunk.
- **Ornaments**: Colorful ornaments placed dynamically around the tree.
- **Star**: A glowing star at the top of the tree.
- **Clouds**: Spiraling clouds around the tree for a magical effect.
- **Interactive Controls**: Use the mouse to rotate, zoom, and pan around the tree.
- **Dynamic Lighting**: Ambient and directional lighting for a realistic look.
- **Sky Background**: A blue sky surrounding the scene.

## Demo

To see the Christmas tree in action, open the tree.html file in a browser that supports ES modules and WebGL.

## Installation

1. Clone this repository or download the source code.
2. Open the tree.html file in a modern browser (e.g., Chrome, Firefox, Edge).

## Usage

- **Rotate**: Click and drag the mouse to rotate the view.
- **Zoom**: Use the scroll wheel to zoom in and out.
- **Pan**: Right-click and drag to pan the view.

## File Structure

- **`tree.html`**: The main file containing the 3D Christmas tree visualization.
- **`snow.html`**: A 2D canvas-based Christmas tree with falling snow animation.
- **`.vscode/settings.json`**: VS Code settings for the project.

## Dependencies

This project uses the following libraries:

- [Three.js](https://threejs.org/) for 3D rendering.
- [OrbitControls](https://threejs.org/docs/#examples/en/controls/OrbitControls) for interactive camera controls.

The libraries are loaded via a CDN using an import map:

```html
<script type="importmap">
{
  "imports": {
    "three": "https://cdn.jsdelivr.net/npm/three@0.167.0/build/three.module.js",
    "OrbitControls": "https://cdn.jsdelivr.net/npm/three@0.167.0/examples/jsm/controls/OrbitControls.js"
  }
}
</script>
```

## Customization

You can customize the tree's appearance and behavior by modifying the following parameters in the tree.html file:

- **Tree Height**: Adjust the `treeHeight` variable in the `ChristmasTree` class.
- **Ornaments**: Change the number, size, and colors of ornaments in the `createOrnaments` method.
- **Clouds**: Modify the number and arrangement of clouds in the `createClouds` method.
- **Lighting**: Adjust the intensity and color of lights in the `setupCameraAndRenderer` method.

---

Enjoy creating your own magical Christmas tree! 🎄✨
