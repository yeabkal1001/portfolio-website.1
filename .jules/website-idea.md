Role & Goal:
Act as a world-class Frontend Engineer and Awwwards-winning UI/UX Designer. Build a personal portfolio website for a [Insert Your Role, e.g., Creative Developer / Product Designer] that aims to win "Site of the Day." The goal is a perfect balance of brutalist modern aesthetics, high-performance interactivity, and deep storytelling.

Design Language & Vibe:

Layout: Use a responsive Bento Grid layout (modular, uneven grid cells) that feels organic but structured.

Aesthetics: "Clean Brutalism." Use a monochrome base (deep charcoal #0a0a0a and off-white #f4f4f5) with a single, electric accent color (e.g., Neon Lime or Hyper Blue). High contrast.

Typography: Mix oversized, kinetic typography (sans-serif, wide tracking) for headers with a clean monospace font for metadata/labels.

Motion: Implement smooth scrolling (Lenis) and scroll-triggered animations. Elements should fade in, scale, or reveal with a staggered delay as the user scrolls.

Core Features & Tech Stack:

Stack: React, Tailwind CSS, Framer Motion (for complex animations), and Lucide React (for icons).

Hero Section: A full-screen interactive playground. Do not use a static image. Create a WebGL-style mouse-follower effect or a kinetic text loop that reacts to cursor velocity.

Projects Section: Display work in large, tilt-effect cards. On hover, the card should expand slightly, play a video preview, and dim the surrounding background (focus mode).

Navigation: A floating, glass-morphism dock at the bottom center of the screen (macOS style) rather than a top navbar.

Micro-interactions:

Magnetic Buttons: Buttons should slightly gravitate toward the mouse cursor before clicking.

Custom Cursor: A small circular cursor that blends (mix-blend-mode: difference) with the background and expands when hovering over clickable elements.

Content Structure:

Hero: Name, Role, One-line value prop.

About: A "scrollytelling" section where text highlights as it enters the viewport.

Selected Work: 4-5 key projects with "Case Study" buttons.

The "Stack": A marquee (infinite scroll) of tech logos.

Footer: Massive typography for "LET'S TALK" with a magnetic email copy button.

Technical Constraints:

Mobile-first responsiveness.

Ensure 100/100 Lighthouse performance score (optimize images, lazy load components).

Code must be modular and clean.