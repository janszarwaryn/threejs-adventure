# Three.js adventure


---

Lesson recap and exercises.

## Chapter 01 - Basics

### simple

- An 3D object is also called a Mesh.
- A Mesh needs a Geometry and a Material.
- Use Camera to adjust the POV of the scene.
- Perspective is the default camera.
- A Camera needs an aspect ratio and an FOV (degree).
- A Renderer need width/height, where to render into, a camera to see and a scene with every mesh's in it.

### The mess

- Milestone: lesson #10
- Things in this mess: `gsap`, `OrbitControls`, `object.geometry.setDrawRange()`, `THREE.BufferGeometry()`

### Infinite Minecraft Blocks

- Milestone: lesson #13
- Keywords: `gsap/ScrollTrigger`, `THREE.FontLoader()`, `THREE.TextGeometry()`, `THREE.MeshBasicMaterial()`
  , `THREE.TextureLoader()`

---

## Deployment

```shell
# Install package
npm i

# Start dev server
npm run dev

# Generate static site
nuxt generate
```
