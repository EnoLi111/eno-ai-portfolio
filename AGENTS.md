# Eno AI / Creative Technology Portfolio

## Product goal
A portfolio for AI Product / Creative Technology roles.
The site should show the path from Visual Arts and market insight to product thinking and AI building.

## Flagship project
The flagship project is the Publicis AI Workbench.
Radar is an important feature/module inside the workbench, not the name of the whole project.

## Homepage intro
- Intro is a visual opening sequence only.
- Eno appears in student-uniform-inspired styling.
- She holds an oversized identity/credential card.
- On scroll, the card moves strongly toward the camera.
- The card does NOT open into navigation.
- The intro ends by revealing the main portfolio content.
- Red / dusty-rose ribbon is the recurring moving motif.

## Visual direction
- Warm white / fog white / pearl gray base.
- Muted wine / dusty rose accent.
- Dark gray / near-black typography.
- Large negative space.
- Restrained, editorial, slightly surreal.
- Inspired by Gentle Monster's restraint and object-focused campaign language.
- Avoid neon blue, cyberpunk, generic AI gradients, terminal aesthetics, and excessive UI chrome.

## Motion language
- Scroll-driven.
- Strong perspective and depth.
- Smooth but clearly visible.
- Use parallax between background, person, card, and ribbon.
- Keep motion minimal and purposeful.
- Prefer 2D / 2.5D first.

## Engineering rules
- Build the homepage intro first.
- Use Next.js + TypeScript.
- Use GSAP / ScrollTrigger for the first prototype.
- Do not add Three.js or Blender output in v1.
- Do not build other project sections yet.
- Keep components isolated so the intro can later be replaced or upgraded.
- Add graceful fallback for reduced motion.
- Do not use the reference image as a production background; it is a visual target only.

## First prototype acceptance criteria
1. Desktop 16:9 composition remains stable.
2. Scroll visibly pushes the card toward the camera.
3. Card perspective feels spatial, not like a simple scale-up.
4. Ribbon layers create foreground/background parallax.
5. Intro exits cleanly into a simple blank content section.
