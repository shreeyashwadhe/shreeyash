This frontend project is a modern, interactive webpage featuring smooth scrolling, animated cursors, and dynamic navigation. It's designed to be visually engaging using GSAP (GreenSock Animation Platform) for animations and Locomotive Scroll for enhanced scroll effects. It focuses on a rich user experience with responsive design, hover effects, and scroll-triggered animations.

🔧 KEY COMPONENTS
1. HTML Structure
Divided into main sections: #page1, #page2, #page3
A fixed navigation bar (#nav) with two parts: logo (#nav-part1) and links/icons (#nav-part2)
2. CSS Styling
Uses * reset and custom fonts (Gilroy, Futura)
Responsive design via media queries for screens ≤600px
Custom cursor styling
3. JavaScript Functionality
a. Locomotive Scroll Setup
Smooth scrolling enabled using LocomotiveScroll

Integrated with GSAP ScrollTrigger using scrollerProxy

b. GSAP Animations
Scroll-triggered nav animation (hides on scroll)
Entrance animation for headings and video section
Cursor follows the mouse with scaling on hover.
