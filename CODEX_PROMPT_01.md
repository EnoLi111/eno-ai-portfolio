Work only on the homepage intro prototype.

First inspect the repository and AGENTS.md.

If the repository is empty, initialize a minimal latest-stable Next.js App Router project with TypeScript and ESLint. Do not add Tailwind unless it already exists. Install only what is necessary, including GSAP.

Build only this interaction:

1. Full-screen pale warm-white intro.
2. A placeholder character layer in the mid/background.
3. A CSS-built oversized Eno identity card in front of the character.
4. Two or three translucent muted-wine ribbon layers crossing foreground/background.
5. On vertical scroll:
   - 0–15%: mostly still.
   - 15–40%: card begins moving toward camera.
   - 40–70%: card becomes the dominant foreground object with perspective/depth, not just scale.
   - 70–100%: card and character leave/clear the viewport and reveal a simple blank content section.
6. Use GSAP ScrollTrigger.
7. Add reduced-motion fallback.
8. Keep all intro code isolated under `components/intro/`.
9. Use `public/references/hero-reference.png` only as a visual target. Do not use it as the webpage background.
10. Do not build any other sections, project pages, menus, 3D, Blender, or Radar UI.

Use temporary CSS shapes / placeholder imagery where final production assets are missing. The purpose of this pass is motion and depth validation, not final art direction.

After implementation:
- run typecheck/lint/build as available;
- report exactly which files were added or changed;
- report any assumptions;
- stop. Do not continue into the rest of the site.
