sjm.dev | Stephen James Morris Portfolio
A high-end, premium digital portfolio designed to bridge the gap between corporate architecture and immersive digital art. This project utilizes a single-file architecture to ensure rapid deployment and high performance while maintaining sophisticated visual effects.
🌟 Technical Core Principles
This project follows Spec-Driven Development (SDD) and focuses on:
 * Single-File Mandate: All logic, styling, and content are contained in a single index.html.
 * Performance First: Heavy utilization of CSS hardware acceleration and optimized Canvas rendering.
 * Responsive Architecture: Mobile-first approach with dedicated wide-screen optimizations.
🛠 Feature Specifications
1. The Constellation Engine (Canvas)
A custom-built particle system that generates geometric nodes and dynamic connecting lines.
 * Optimization: Style lookups are cached outside the animation loop to prevent layout thrashing.
 * Adaptability: Alpha values adjust dynamically between Light and Dark modes to maintain legibility.
2. Synchronization & Loading
 * Custom Loader: A monochromatic monospace loader using animated brackets { } and the SJM logo.
 * Skeleton Loading: CSS-driven shimmer effects that placeholder content during initial image fetching.
 * Intersection Observer: Reveal animations triggered as the user scrolls into new sections.
3. Navigation & UX
 * Pill-Style Navbar: A floating, glassmorphic navigation bar that adapts to device width.
 * Internationalization: Multi-language engine (English/German) with instant UI updates via data-attributes.
 * 3D Interactive Gallery: CSS perspective-based cards with Z-axis translation on hover/touch.
4. The Arsenal & Tech Marquee
 * Skill Arsenal: High-tech tags featuring LED-style status indicators and kinetic lift effects.
 * Tech Scroller: An infinite horizontal marquee powered by CSS keyframe animations utilizing high-quality image-based tech logos.
📊 Development Roadmap & Tasks
| Task | Category | Status |
|---|---|---|
| [x] | Implementation of core single-file architecture | Done |
| [x] | Develop "The Essence" with social media integration | Done |
| [x] | Create "The Chronicle" with all 7 professional milestones | Done |
| [x] | Build "The Academy" Bento Grid with 6 certifications | Done |
| [x] | Integration of bracketed loader { logo } | Done |
| [x] | Implementation of Constellation Engine (Particles) | Done |
| [x] | Infinite horizontal marquee for Tech Logos | Done |
| [x] | Advanced 3D Gallery Card effects | Done |
| [x] | Skeleton loading system for all visual assets | Done |
| [x] | Dual-language support (EN/DE) | Done |
| [x] | Revert and stabilize Pill-style Navigation | Done |
| [/] | Fine-tune Canvas performance for older mobile devices | In Progress |
| [ ] | Implement automated Lighthouse performance auditing | Not Started |
| [ ] | Final content proofread (German/English nuances) | Planned |
📋 Acceptance Checklist
 * [x] Architecture: Is the project contained in a single runnable file?
 * [x] Aesthetics: Does the design meet "Premium Quality" standards (spacing, rounded corners, depth)?
 * [x] Responsive: Is the navigation bar fixed for both desktop and mobile views?
 * [x] Data Integrity: Are all professional milestones and certificates present?
 * [x] Interactive: Do the 3D cards and scrolling logos function without jitter?
 * [x] Technical: Is the custom CSS pulse animation for the loader correctly implemented?
🚀 Usage
Simply open index.html in any modern web browser. The application initializes automatically, calculating canvas dimensions and triggering the loading sequence based on resource availability.
Forged in the Void — 2026 Stephen James Morris
