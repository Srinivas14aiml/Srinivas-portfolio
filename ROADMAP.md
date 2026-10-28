# THE 3D WEB DEVELOPMENT ROADMAP

> **From Beginner to Immersive, Award-Worthy Websites**  
> A practical roadmap for learning modern 3D web development, WebGL, Three.js, React Three Fiber, animation, and creative development.

🔗 **[Live Interactive Roadmap with WebGL 3D Preview](https://srinivas14aiml.github.io/roadmap.html)**

---

## How to Use This Guide
If you have seen websites such as Pasqua, Pear or Zoo and wondered how developers create immersive 3D scenes, smooth camera movement and interactive experiences, this roadmap gives you a path to start building them yourself.

> 💡 **Golden Rule:** Do not try to master every technology at once. Learn a concept, build something with it, break it, debug it, and then move to the next level.

---

## Table of Contents
1. [01 — What You Actually Need to Learn](#01--what-you-actually-need-to-learn)
2. [02 — Stage 1: Master Normal Websites First](#02--stage-1-master-normal-websites-first)
3. [03 — Stage 2: JavaScript](#03--stage-2-javascript)
4. [04 — Stage 3: React](#04--stage-3-react)
5. [05 — Stage 4: Motion](#05--stage-4-motion)
6. [06 — GSAP + ScrollTrigger](#06--gsap--scrolltrigger)
7. [07 — Smooth Scrolling](#07--smooth-scrolling)
8. [08 — Stage 5: Understand 3D](#08--stage-5-understand-3d)
9. [09 — Three.js](#09--threejs)
10. [10 — Your First Three.js Projects](#10--your-first-threejs-projects)
11. [11 — React Three Fiber](#11--react-three-fiber)
12. [12 — Drei](#12--drei)
13. [13 — Learn Blender](#13--learn-blender)
14. [14 — 3D File Formats](#14--3d-file-formats)
15. [15 — Spline](#15--spline)
16. [16 — Shaders + GLSL](#16--shaders--glsl)
17. [17 — WebGL Fundamentals](#17--webgl-fundamentals)
18. [18 — What Makes a 3D Website Feel Premium?](#18--what-makes-a-3d-website-feel-premium)
19. [19 — How to Study Great Websites](#19--how-to-study-great-websites)
20. [20 — Recommended Tech Stack](#20--recommended-tech-stack)
21. [21 — Performance](#21--performance)
22. [22 — Common Beginner Mistakes](#22--common-beginner-mistakes)
23. [23 — Learning Roadmap (8 Levels)](#23--learning-roadmap)
24. [24 — Project Roadmap (12 Projects)](#24--project-roadmap)
25. [25 — 30-Day Challenge](#25--30-day-challenge)
26. [26 — Inspiration Websites & Galleries](#26--inspiration-websites--galleries)
27. [27 — Useful Search Terms](#27--useful-search-terms)
28. [28 — The Practice Loop](#28--the-practice-loop)
29. [29 — Final Advice](#29--final-advice)
30. [30 — Quick Cheat Sheet](#30--quick-cheat-sheet)

---

## 01 — What You Actually Need to Learn
- **Web foundation:** HTML, CSS, JavaScript, Git and responsive design
- **Frontend:** React, Next.js and Tailwind CSS
- **Motion:** GSAP, ScrollTrigger, smooth scrolling and micro-interactions
- **3D:** Three.js, WebGL concepts, GLTF/GLB, cameras, lights, materials and textures
- **React 3D:** React Three Fiber and Drei
- **3D creation:** Blender and Spline
- **Advanced graphics:** shaders, GLSL, particles, physics and post-processing
- **Creative development:** art direction, storytelling, interaction design and performance

---

## 02 — Stage 1: Master Normal Websites First
Before jumping into 3D, become comfortable building polished 2D websites:
- Semantic HTML
- Flexbox and Grid
- Responsive layouts
- CSS transitions and transforms
- CSS variables and gradients
- JavaScript DOM and events
- Forms, APIs and async/await

**Practice projects:** Landing page, portfolio, interactive navbar, image gallery, modal, custom cursor, and theme switcher.

---

## 03 — Stage 2: JavaScript
Learn variables, functions, arrays, objects, DOM manipulation, events, modules, promises, async/await, classes and ES6+.

Build small interactions instead of only watching tutorials. Your JavaScript foundation will make animation and 3D much easier.

---

## 04 — Stage 3: React
Learn components, props, state, hooks, events, conditional rendering, lists, context and component composition.

Build an animated portfolio before moving deeply into 3D.

---

## 05 — Stage 4: Motion
Premium websites often feel impressive because of motion, not simply because they contain 3D:
- Easing
- Timelines
- Stagger
- Parallax
- Scroll-triggered animation
- Page transitions
- Micro-interactions

---

## 06 — GSAP + ScrollTrigger
Learn `gsap.to()`, `gsap.from()`, `gsap.fromTo()`, timelines, stagger, and ScrollTrigger.

Practice text reveals, image reveals, pinned sections, horizontal scrolling, parallax, and scroll-controlled scenes.

---

## 07 — Smooth Scrolling
Explore smooth scrolling and connect scroll progress to animation progress.

> **Mental Model:**  
> `Scroll position (0 → 1) ➔ animation progress ➔ camera / object / text changes`

---

## 08 — Stage 5: Understand 3D
Three.js gives you a way to create 3D graphics in the browser. Understand these concepts first:
- **Scene:** The 3D world container
- **Camera:** What the user sees (PerspectiveCamera)
- **Mesh:** An object made from geometry + material
- **Geometry:** The mathematical shape
- **Material:** The surface properties (color, roughness, metalness)
- **Light:** Illumination (Ambient, Directional, Spot)
- **Renderer:** Converts the 3D scene into 2D pixels

---

## 09 — Three.js
- Scene and PerspectiveCamera
- WebGLRenderer
- Meshes and geometry
- Materials and textures
- Lights and shadows
- Groups, position, rotation, and scale
- OrbitControls
- Raycasting (hover & click picking)
- GLTFLoader
- AnimationMixer
- Environment maps

---

## 10 — Your First Three.js Projects
1. Rotating cube
2. Interactive sphere
3. 3D product viewer
4. Solar system
5. 3D gallery
6. 3D portfolio hero
7. Scroll-controlled 3D scene
8. Interactive product website
9. Particles scene
10. Immersive portfolio

---

## 11 — React Three Fiber
React Three Fiber is a React renderer for Three.js. It lets you build 3D scenes declaratively with reusable components. The official documentation recommends having a basic grasp of both React and Three.js before diving deeply into R3F.
- `<Canvas>`
- Mesh components
- `useFrame`
- `useThree`
- `<Suspense>`
- Lights & Camera
- Controls & State interactions

---

## 12 — Drei
Drei provides essential production-ready helpers for React Three Fiber:
- `<OrbitControls />`
- `<Environment />`
- `<Float />`
- `<Text />`
- `<Html />`
- `<ContactShadows />`
- `<Stage />`
- `<PresentationControls />`
- `<ScrollControls />`
- `useGLTF()`

---

## 13 — Learn Blender
You do not need to become a professional 3D artist. Learn enough Blender to create, edit, and optimize web-ready assets:
- Navigation & Transformations (G, R, S)
- Basic modeling
- Materials and lighting
- Camera setup
- Modifiers (Decimate for polycount reduction)
- UVs and textures
- Texture baking
- Exporting GLB/GLTF
- Reducing polygon count

---

## 14 — 3D File Formats
- **GLB / GLTF:** Especially useful for modern web workflows (embedded binary geometry, materials, textures, animations).
- **OBJ / FBX:** Legacy formats when working with downloaded assets; convert to GLB using `gltf-pipeline` for web delivery.

---

## 15 — Spline
Spline is useful for quickly creating interactive 3D scenes, prototypes, product visualizations, and landing-page experiences. Use it as a tool in your workflow, while learning Three.js/R3F for deeper control.

---

## 16 — Shaders + GLSL
Shaders let you control how surfaces and pixels are rendered. Learn these after you understand Three.js:
- **Vertex shaders:** Calculate vertex position in space (waves, displacement, noise)
- **Fragment shaders:** Calculate pixel color (gradients, liquid refractions, glow)
- **Uniforms:** Variables passed from JavaScript (time, mouse, resolution)
- **Attributes:** Per-vertex data (position, normal, uv)
- **Varyings:** Data passed from vertex to fragment shader
- **UV coordinates:** 2D mapping coordinates
- **Noise:** Simplex & Perlin noise for organic effects
- **Distortion & Liquid effects:** Mouse ripple interactions

---

## 17 — WebGL Fundamentals
You do not need to become a graphics engineer, but understanding GPU rendering, vertices, triangles, buffers, textures, and shaders will make 3D easier to reason about.

> **Mental Model:**  
> `JavaScript ➔ Three.js / R3F ➔ WebGL ➔ GPU ➔ Pixels`

---

## 18 — What Makes a 3D Website Feel Premium?
The answer is not simply "more 3D". Great experiences combine design, 3D, animation, typography, interaction, sound, and storytelling.

Before adding 3D, ask:
*Why is the 3D there? Does it explain the product, create atmosphere, guide attention, tell a story, or make an interaction memorable?*

---

## 19 — How to Study Great Websites
- What is moving?
- Is the camera moving?
- What triggers the animation?
- How does scroll affect the scene?
- How are typography and 3D combined?
- What could be implemented with Three.js, R3F, GSAP, or shaders?
- How is loading handled?
- How does the experience work on mobile?

---

## 20 — Recommended Tech Stack
| Area | Tools | Why |
| :--- | :--- | :--- |
| **Frontend** | React / Next.js | Modern component architecture, SSR & fast routing |
| **Styling** | Tailwind CSS | Utility-first, zero runtime overhead, responsive |
| **3D Engine** | Three.js + R3F + Drei | Industry standard declarative 3D ecosystem |
| **Animation** | GSAP + ScrollTrigger | High performance, timeline sequencing, scrub |
| **3D Creation** | Blender + Spline | Asset optimization, mesh cleanup & interactive scenes |
| **Assets** | GLB / GLTF + Draco | Compressed web-ready 3D binary format |
| **Version Control** | Git + GitHub | Tracking iterations & collaborative workflow |
| **Deployment** | Vercel / Netlify / GitHub Pages | Fast CDN deployment & instant previews |

---

## 21 — Performance & Optimization
A beautiful 3D website that takes too long to load is not a good experience:
- Reduce polygon count (target < 50,000 polygons for mobile)
- Compress textures (WebP, KTX2/Basis)
- Optimize GLB files using Draco compression
- Lazy-load heavy 3D canvases
- Avoid unnecessary render loops when canvas is offscreen
- Limit expensive shadows and post-processing bloom
- Clamp device pixel ratio (`Math.min(window.devicePixelRatio, 2)`)
- Monitor GPU/CPU usage in Chrome DevTools

---

## 22 — Common Beginner Mistakes
| Mistake | Better Approach |
| :--- | :--- |
| **Trying to learn everything first** | Learn enough to build, then learn what the project demands. |
| **Copying tutorials blindly** | Rebuild the project from memory and change the idea. |
| **Starting directly with shaders** | Learn Three.js fundamentals first. |
| **Making everything 3D** | Use 3D where it improves the experience; keep text & navigation in HTML. |
| **Ignoring performance** | Optimize from the beginning (polycount, textures, draw calls). |
| **Only watching tutorials** | Spend 80% of your time building and debugging code. |

---

## 23 — Learning Roadmap
- **Level 1:** HTML, CSS, JavaScript, Git, responsive design
- **Level 2:** React, Next.js, Tailwind CSS
- **Level 3:** GSAP, ScrollTrigger, smooth scrolling
- **Level 4:** Three.js, WebGL concepts, GLTF/GLB
- **Level 5:** React Three Fiber, Drei
- **Level 6:** Blender, Spline, textures, materials
- **Level 7:** Shaders, GLSL, particles, physics, post-processing
- **Level 8:** Art direction, storytelling, interaction and performance

---

## 24 — Project Roadmap
1. Animated landing page
2. Animated portfolio
3. Custom cursor website
4. Scroll animation website
5. 3D product viewer
6. 3D portfolio
7. Interactive 3D hero
8. Scroll-controlled 3D scene
9. Interactive product experience
10. 3D storytelling website
11. Creative agency website
12. Award-style portfolio

---

## 25 — 30-Day Challenge
- **Week 1:** HTML + CSS + JavaScript + responsive design. Build one polished landing page.
- **Week 2:** React + GSAP + ScrollTrigger + smooth scrolling. Build an animated portfolio.
- **Week 3:** Three.js fundamentals: scene, camera, mesh, geometry, materials, and lights. Build an interactive 3D site.
- **Week 4:** React Three Fiber + Drei + GLB models + Blender basics + optimization. Build your first serious 3D website.

---

## 26 — Inspiration Websites & Galleries
- **[Three.js Official Examples](https://threejs.org/examples/):** Official Three.js examples covering WebGL, WebGPU, post-processing, and 3D textures.
- **[React Three Fiber Examples](https://github.com/pmndrs/react-three-fiber/blob/master/docs/getting-started/examples.mdx):** Official R3F examples including scroll, reflections, glass, physics, and particles.
- **[React Three Fiber Docs](https://r3f.docs.pmnd.rs/):** Core documentation for building Three.js scenes with React.
- **[Three.js Docs](https://threejs.org/docs/):** Reference and fundamentals for Three.js.
- **[Awwwards](https://www.awwwards.com/):** Explore award-winning creative websites and study interaction patterns.
- **[Godly](https://godly.website/):** Curated modern web design inspiration.
- **[Lapa Ninja](https://www.lapa.ninja/):** Landing page inspiration and UI references.
- **[Three.js Journey](https://threejs-journey.com/):** Structured Three.js learning resource by Bruno Simon.
- **[Blender](https://www.blender.org/):** Free 3D creation software for modeling, materials, and exporting web assets.
- **[Spline](https://spline.design/):** Browser-based 3D design and interactive scene creation.

---

## 27 — Useful Search Terms
- `Three.js product viewer`
- `React Three Fiber scroll animation`
- `GSAP ScrollTrigger 3D`
- `Three.js GLTF model`
- `React Three Fiber particles`
- `Three.js shader distortion`
- `GLSL liquid shader`
- `WebGL image distortion`
- `R3F camera animation`
- `Blender GLB optimization`
- `Three.js post processing`
- `React Three Fiber physics`

---

## 28 — The Practice Loop
```
LEARN ➔ BUILD ➔ BREAK ➔ DEBUG ➔ RESEARCH ➔ IMPROVE ➔ PUBLISH ➔ REPEAT
```

---

## 29 — Final Advice
Your first website will not look like Pasqua, Pear or Zoo. That's completely fine. The goal is not to copy those websites. Study their interactions, understand the techniques, and create your own experience.

> *The real milestone is when you can look at a design and think: "I know how I would build this." That is the skill you are working toward.*

---

## 30 — Quick Cheat Sheet
- **WEB:** HTML ➔ CSS ➔ JavaScript
- **FRONTEND:** React ➔ Next.js ➔ Tailwind CSS
- **MOTION:** GSAP ➔ ScrollTrigger ➔ Smooth scrolling
- **3D:** Three.js ➔ WebGL ➔ GLTF
- **REACT 3D:** React Three Fiber ➔ Drei
- **3D ASSETS:** Blender ➔ Spline
- **ADVANCED:** Shaders ➔ GLSL ➔ Particles ➔ Physics ➔ Post-processing
- **CREATIVE DEVELOPMENT:** Design ➔ Storytelling ➔ Interaction ➔ Performance

---

### Resources Note
Technology and library versions change over time. Use the official documentation linked above for current installation instructions and API details. The React Three Fiber documentation specifically recommends learning the basics of both React and Three.js first.

*Maintained by [Srinivas Devalla](https://github.com/Srinivas14aiml) · [Repository](https://github.com/Srinivas14aiml/Srinivas-portfolio.git)*
