# Hire-me
Dip's web store
# 🌌 PROJECT: ALPHA | Architecture Portfolio

![Project Alpha Header](https://i.imgur.com/WjwmZnT.png)

### **High-End Cybernetic Interface & Web Deployment**
A curated collection of next-generation system interfaces, neural network visualization grids, and cybernetic architectures engineered by **Dip-Tarafder**.

---

## 💎 Design Philosophy
This project explores the intersection of **Glassmorphism** and **Cyberpunk aesthetics**. It utilizes a dark-mode-first approach with high-contrast neon accents and fluid motion.

* **Glassmorphic UI:** Deep background blurs (`16px`) and semi-transparent surfaces.
* **Neon Feedback:** Interactive glow effects using CSS custom properties.
* **Neural Motion:** Staggered entrance animations to simulate a system "boot-up."
* **Responsive Grid:** A fluid `320px` min-max grid system that adapts to any viewport.

---

## 🛠️ Technical Specifications

| Component | Technology | Implementation |
| :--- | :--- | :--- |
| **Styling** | CSS3 / SCSS | Custom properties, `backdrop-filter`, and CSS Grids. |
| **Typography** | Google Fonts | 'Outfit' variable font (Weights 300-800). |
| **Icons** | FontAwesome 6 | Vector-based iconography for UI controls. |
| **Interactivity** | Vanilla JS | Mouse-tracking spotlight effect on asset cards. |

### Neural Glow Logic
The "High-End" feel is achieved through a dynamic spotlight script that tracks the user's cursor:
```javascript
// Calculates relative mouse position to update CSS Variables
const x = e.clientX - rect.left;
const y = e.clientY - rect.top;
card.style.setProperty('--mouse-x', `${x}px`);
