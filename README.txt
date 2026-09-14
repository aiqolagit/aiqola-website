AIQOLA Website v2.0 EXPERIMENTAL — Motion Experience

IMPORTANT
This package is a FORK of the locked AIQOLA Website v1.9 baseline.
Do NOT overwrite the current production v1.9 repository while evaluating v2.0.

WHAT IS PRESERVED
- v1.9 content structure
- AIQOLA brand / dark navy + cyan + violet identity
- Products & Roadmap
- About AIQOLA
- Hari Adrianto professional attribution
- Indonesian / English support
- /products clean route
- /aiqola-intelligence clean route
- Existing responsive structure and reduced-motion support

V2.0 EXPERIMENTAL MOTION LAYER
1. Cinematic first-load hero reveal
2. Lightweight page veil / transition-in
3. Top scroll progress beam
4. Navbar changes into stronger glass state while scrolling
5. Cursor-reactive hero ambience on desktop
6. Subtle 3D/parallax response on the hero core and floating data panels
7. Sequential scroll reveals with blur-to-sharp entrance
8. Cursor-tracking spotlight and restrained 3D tilt on cards
9. Animated light sweep across cards
10. Animated AIQOLA product ecosystem roadmap line
11. Section-level cursor glow / scroll progress accent
12. Magnetic button micro-interaction on pointer devices
13. AIQOLA Intelligence Core cursor response
14. Core → Advanced → Max signature entrance enhancement
15. Recommended cyan pulse + Max violet premium pulse
16. Animated AIQOLA Intelligence roadmap connection
17. Mobile/touch fallbacks: tilt and cursor effects disabled
18. prefers-reduced-motion fallback retained
19. No Three.js, WebGL, GSAP, or heavy external animation dependencies

PERFORMANCE PHILOSOPHY
The experiment intentionally uses native CSS/JavaScript only.
Visual movement is mostly opacity, transform, gradient, and IntersectionObserver.
Desktop gets the richer interaction; mobile receives a lighter motion profile.

SAFE TESTING
Recommended:
A. Create a separate GitHub repository, e.g. aiqola-v2-experimental
B. Upload these files to that repository root
C. Import that repository as a NEW Vercel project
D. Test it on a temporary *.vercel.app URL
E. Keep current aiqola.vercel.app on locked v1.9

DO NOT replace the existing production repository yet.

FILES TO UPLOAD TO THE EXPERIMENTAL REPO ROOT
- index.html
- aiqola-intelligence.html
- intelligence.html
- products.html
- vercel.json
- EXPERIMENTAL.json
- README.txt

TEST CHECKLIST
Desktop:
- hero entrance
- cursor/parallax response
- cards spotlight + subtle tilt
- navbar glass state
- product roadmap flow
- /products
- /aiqola-intelligence
- Core / Advanced / Max
- Intelligence roadmap

Mobile:
- hero animation remains smooth
- no pointer tilt
- navigation works
- products page works
- Intelligence page works
- scrolling is smooth

If v2.0 is preferred, promote it only after mobile + laptop approval.
