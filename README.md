# 🌄 Parallax Scroll Animation

A breathtaking, multi-scene parallax scrolling web experience built using scalable **SVG**, **CSS3**, and **GSAP (ScrollTrigger)**[cite: 4, 5, 6]. As you scroll down the page, seamlessly transition through distinct scenic environments complete with dynamic sun motions, floating clouds, flying bats, shifting colour gradients, and twinkling starfields.

## ✨ Features

* **Advanced GSAP ScrollTrigger Integration:** Smooth, scrubbed-based scroll animations that control complex multi-layered vector graphics[cite: 5].
* **Multi-Scene Parallax Architecture:** 
  * **Scene 1:** Dynamic morning/daybreak atmosphere with layered hills, moving clouds, and a drifting bird[cite: 5].
  * **Scene 2:** Transition phase featuring rising hills and animated flying bats[cite: 5].
  * **Scene 3:** A starry night scene equipped with twinkling stars, shifting gradients, and a falling shooting star[cite: 5].
* **Responsive SVG Scaling:** Utilises scalable vector graphics with a fixed aspect ratio container (`preserveAspectRatio="xMidYMax slice"`) to maintain sharp visuals across different screen resolutions.
* **Zero Dependencies (Except GSAP):** Lightweight and optimized performance driven purely by modern web animation tools[cite: 5, 6].

## 📁 Project Structure

```text
├── index.html     # Main markup containing the full SVG scene graphics and structure
├── style.css      # Core styles, responsive layout rules, and fixed viewport configurations[cite: 6]
└── script.js      # GSAP timeline configuration, ScrollTrigger hooks, and motion logic[cite: 5]
