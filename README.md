<div align="center">
  <br />
  <div>
    <img src="https://img.shields.io/badge/-HTML5-black?style=for-the-badge&logoColor=white&logo=html5&color=E34F26" alt="html5" />
    <img src="https://img.shields.io/badge/-CSS3-black?style=for-the-badge&logoColor=white&logo=css3&color=1572B6" alt="css3" />
    <img src="https://img.shields.io/badge/-JavaScript-black?style=for-the-badge&logoColor=white&logo=javascript&color=F7DF1E" alt="javascript" />
    <img src="https://img.shields.io/badge/-GSAP-black?style=for-the-badge&logoColor=white&logo=greensock&color=88CE02" alt="gsap" />
    <img src="https://img.shields.io/badge/-Locomotive_Scroll-black?style=for-the-badge&logoColor=white&logo=locomotive&color=2C3E50" alt="locomotive" />
  </div>
  <h3 align="center">Apple Vision Pro Clone</h3>
  <div align="center">
    An educational frontend clone of the Apple Vision Pro website, showcasing advanced animations and smooth scrolling effects
  </div>
</div>

## 📋 Table of Contents
1. 🎯 [Overview](#overview)
2. 🚀 [Features](#features)
3. 💻 [Technologies Used](#technologies)
4. 🎨 [Animations & Effects](#animations)
5. 🔧 [Setup & Installation](#setup)
6. ⚠️ [Disclaimer](#disclaimer)

## <a name="overview">🎯 Overview</a>
This project is an educational clone of Apple's Vision Pro website, created to demonstrate and practice advanced web animation techniques and smooth scrolling implementations. The clone replicates the key visual elements and sophisticated animations of the original site while implementing custom ScrollTrigger animations and Locomotive Scroll for smooth scrolling experiences.

## <a name="features">🚀 Features</a>
👉 **Smooth Scrolling**
- Locomotive Scroll integration
- Custom scroll-based animations
- Seamless section transitions

👉 **Advanced Animations**
- GSAP-powered animations
- ScrollTrigger implementations
- Parallax effects
- Text reveal animations
- Image sequence animations

👉 **Responsive Design**
- Mobile-first approach
- Adaptive layouts
- Responsive images and videos
- Cross-browser compatibility

👉 **Performance Optimizations**
- Efficient animation rendering
- Optimized asset loading
- Smooth performance across devices

## <a name="technologies">💻 Technologies Used</a>
### Core Technologies
- **HTML5**
- **CSS3**
  - Flexbox & Grid
  - Custom Properties
  - CSS Animations
- **JavaScript (ES6+)**

### Libraries & Frameworks
- **GSAP (GreenSock Animation Platform)**
  - ScrollTrigger plugin
  - Timeline animations
  - Custom eases
- **Locomotive Scroll**
  - Smooth scrolling
  - Scroll-based events
  - Custom scroll behaviors

## <a name="animations">🎨 Animations & Effects</a>
1. **Scroll-Based Animations**
   - Parallax scrolling effects
   - Content reveal animations
   - Image sequence playback
   - Text fade effects

2. **Interactive Elements**
   - Hover states
   - Click animations
   - Transition effects
   - Loading animations

3. **GSAP Implementations**
   - Timeline sequences
   - ScrollTrigger pins
   - Custom animation paths
   - Stagger effects

4. **Locomotive Scroll Features**
   - Smooth scroll behavior
   - Section-based scrolling
   - Scroll-linked animations
   - Custom scroll speeds

## <a name="setup">🔧 Setup & Installation</a>
1. **Clone the Repository**
```bash
git clone https://github.com/Abhias2405/apple_vision_pro_clone.git  
cd apple_vision_clone
```

2. **Dependencies**
```html
<!-- Add to your HTML -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/ScrollTrigger.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/locomotive-scroll@4.1.4/dist/locomotive-scroll.min.js"></script>
```

3. **Initialize Smooth Scroll**
```javascript
const scroll = new LocomotiveScroll({
    el: document.querySelector('#main'),
    smooth: true
});
```

4. **GSAP ScrollTrigger Setup**
```javascript
gsap.registerPlugin(ScrollTrigger);

// Example animation
gsap.to(".target-element", {
    scrollTrigger: {
        trigger: ".trigger-element",
        start: "top center",
        end: "bottom center",
        scrub: true
    },
    y: 100,
    opacity: 0
});
```

## <a name="disclaimer">⚠️ Disclaimer</a>
This project is created for educational purposes only. All design credits go to Apple Inc. and their Vision Pro website. This clone is built to demonstrate and practice advanced frontend development techniques and is not intended for commercial use.

### Educational Objectives
- Learning advanced GSAP animations
- Implementing smooth scroll behaviors
- Practicing responsive design
- Understanding ScrollTrigger functionality
- Mastering modern CSS and JavaScript techniques

The project serves as a learning resource for developers interested in:
- Advanced animation techniques
- Scroll-based interactions
- Performance optimization
- Modern web development practices
