Project Title: The Infinite Descent – Premium Parallax Experience

🌌 Project Overview
This project is a high-end, interactive landing page utilizing advanced parallax scrolling techniques to construct a deep, immersive 3D digital landscape. Driven by a cosmic/fantasy theme ("Aethelgard"), the page rewards user interaction by creating an organic illusion of spatial depth as they scroll through multiple atmospheric layers.

🛠️ Technical Features & Architecture
Advanced Layer Occlusion: Text and design elements are physically sandwiched between background assets (stars, celestial bodies) and foreground assets (layered mountain ranges). As the user scrolls, typography smoothly hides behind structural shapes, mimicking real-world depth perception.

GSAP & ScrollTrigger Integration: Instead of using rigid, linear scroll triggers or heavy window.scroll listeners that cause browser lag, this page uses the GreenSock Animation Platform (GSAP). Animations are tied directly to the browser's scroll bar using physics-based scrubbing for buttery-smooth performance.

Hardware-Accelerated Performance: The parallax layers translate across the Y-axis utilizing independent velocity values (data-rate), offloading calculations to the device's GPU to maintain a consistent 60+ FPS experience.

Responsive Fluid Design: Built with modern CSS (Flexbox, CSS Grid, and clamp-based fluid typography), ensuring the layout scales gracefully from widescreen desktop monitors down to mobile devices.

Micro-Interactions: Includes interactive, floating geometric elements running on infinite CSS/GSAP keyframe loops to keep the page visually active even when the user stops scrolling.

🚀 Technologies Used
HTML5 (Semantic structure & custom data attributes)

CSS3 (Custom properties, linear gradients, layout grids, and keyframes)

JavaScript (ES6+)

GSAP 3 & ScrollTrigger (Animation Engines via CDN)
