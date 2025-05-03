```markdown
# Volumetric Morphing Particle Sphere

A dynamic, rotating volumetric sphere made of morphing particles using [Three.js](https://threejs.org/) and [Simplex Noise](https://github.com/jwagner/simplex-noise.js).



---

## Features

- **Volumetric Surface:** Distribute particles on the surface of a sphere.
- **Noise Morphing:** Use Simplex Noise to modulate radius for an organic pulsating effect.
- **Rotation:** Continuous slow rotation for a mesmerising vibe.
- **Easy Customization:** Adjust particle count, base radius, noise intensity, rotation speed, etc.

---


## 🚀 Getting Started

**Prerequisites**

- A modern web browser (Chrome, Firefox, Safari, Edge)
- (Optional) A local HTTP server to avoid CORS issues

**Clone the repository**

```bash
git clone https://github.com/<your-username>/volumetric-sphere.git
cd volumetric-sphere
````

**Option 1: Open Directly**

* Double-click `index.html` to open in your browser.

**Option 2: Serve with a Local Server**

Using [http-server](https://www.npmjs.com/package/http-server):

```bash
npm install -g http-server
http-server .
# Visit http://localhost:8080
```

---

## 🛠️ Customization

Inside `index.html`, look for these core parameters:

```js
const particleCount = 30000;      // Number of particles
const baseRadius = 200;           // Base sphere radius
const noiseScale = 1.5;           // Noise frequency multiplier
const noiseAmplitude = 50;        // How far noise can push particles
const rotationSpeed = 0.002;      // Rotation increment per frame
```

Modify these values to change density, size, morph intensity, and spin speed.

---

## 📈 Performance Tips

* Lower `particleCount` for better performance on older devices.
* Reduce `noiseAmplitude` or `noiseScale` to simplify calculations.
* Consider using `THREE.BufferGeometry` optimizations or GPU-based noise.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Please follow these steps:

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/new-thing`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-thing`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the [MIT License](./LICENSE).

---

## 🙏 Acknowledgements

* [Three.js](https://threejs.org/) for the 3D library
* [simplex-noise.js](https://github.com/jwagner/simplex-noise.js) by Jonas Wagner
* Community examples and tutorials that inspired this demo

```
```
