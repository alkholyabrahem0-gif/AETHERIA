AETHERIA: THE LOST WORLD - PWA

This is an early browser-playable prototype. It is single-player; online multiplayer is not implemented.

NEW: Adaptive rendering for a 30 FPS target
- Rendering is paced toward 30 frames per second.
- The game monitors delivered frame intervals and dynamically lowers render resolution when performance drops below the target.
- After a sustained stable period, it gradually raises render resolution again.
- The visual world and UI layout are retained; the internal render resolution changes to reduce GPU load.
- Browser-based prototype limitation: it cannot reliably read the phone's exact GPU temperature or GPU workload. Actual sustained 30 FPS must be tested on the target Galaxy A13. The adaptive controller is a best-effort mechanism, not a guarantee.

To publish with GitHub Pages:
1. Extract this ZIP.
2. Upload the CONTENTS of the aetheria_package folder to the root of a GitHub repository.
3. Enable GitHub Pages from Settings > Pages, using the main branch and root folder.
4. Open the published HTTPS URL in Chrome on Android. Use the browser menu > Install app / Add to Home screen.

Three.js is loaded from jsDelivr, so an internet connection is required to load the game.
