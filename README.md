sjm.dev | Stephen James Morris Portfolio
A premium digital portfolio designed to bridge the gap between corporate architecture and immersive digital art. This project leverages a sophisticated single-file architecture to provide a high-performance, maintenance-free, and visually stunning user experience.
🌟 Technical Core Principles
This project is built following the Spec-Driven Development (SDD) philosophy, emphasizing intent over raw implementation:
 * Single-File Architecture: All HTML structure, Tailwind styling, and JavaScript logic are consolidated into one high-performance file.
 * Spec-Driven Quality: Design choices (spacing, typography, motion) follow strict premium architectural guidelines.
 * Performance Optimization: Optimized Canvas rendering and hardware-accelerated CSS transitions ensure a smooth experience even on mobile devices.
🛠 Feature Specifications
1. The Constellation Engine (Canvas API)
A custom-built particle system that serves as the dynamic backdrop for the portfolio.
 * Logic: Generates autonomous geometric nodes that connect via proximity lines.
 * Optimization: Caches theme-specific CSS variables outside the animation loop to minimize layout thrashing and CPU load.
 * Adaptability: Dynamically adjusts line and node opacity (Alpha) based on the active theme (Dark/Light mode) to maintain text legibility.
2. Branding & Synchronization
 * Bracketed Loader: A custom monospaced loader featuring the { logo } bracket animation, signaling a technical and developer-focused identity.
 * Skeleton System: Shimmer-effect placeholders that provide immediate visual feedback while heavy assets (like profile photos and gallery images) are loading.
3. Interactive UI Components
 * Pill-Style Navigation: A glassmorphic, floating navbar that automatically handles responsive layouts and theme switching.
 * 3D Interactive Gallery: Perspective-based CSS transformations that respond to hover and touch events, giving digital artwork physical depth.
 * Infinite Tech Scroller: A CSS-driven marquee displaying the current tech stack (Node.js, React, Next.js, etc.) with image-based logos and monochromatic filters.
📊 Development Roadmap & Tasks
| Status | Task | Category |
|---|---|---|
| [x] | Core single-file architecture implementation | Infrastructure |
| [x] | "The Essence" with social media and contact logic | Feature |
| [x] | "The Chronicle" history (7 milestones) | Data |
| [x] | "The Academy" bento grid (6 certifications) | Data |
| [x] | Bracketed { logo } loading screen implementation | UX |
| [x] | Image-based Tech Scroller (Node, React, PHP, etc.) | Feature |
| [x] | Constellation Engine performance optimization | Technical |
| [/] | Fine-tune 3D card tilt sensitivity for tablet devices | UX |
| [/] | Calibrate light-mode geometric contrast | UI |
| [ ] | Automated Lighthouse performance auditing | DevOps |
| [ ] | Implement server-side contact form handler | Planned |
| [ ] | Final cross-browser compatibility check (Safari/Edge) | Planned |
📋 Acceptance Checklist
 * [x] Architecture: Entire application is contained within a single runnable file.
 * [x] Aesthetics: Design meets "Premium Quality" standards (rounded corners, consistent depth, ample whitespace).
 * [x] Responsive: Navigation and Hero sections adapt correctly to mobile, tablet, and wide screens.
 * [x] Data Integrity: All 7 career milestones and 6 certifications are accurately represented.
 * [x] Interaction: Scrolling logos and 3D gallery cards function without visual jitter.
 * [x] Technical: Custom CSS pulse animations and Canvas engine are correctly synchronized.
🚀 Usage
Open index.html in any modern web browser. The system will automatically detect system theme preferences and initialize the loading sequence.
Forged in the Void — 2026 Stephen James Morris