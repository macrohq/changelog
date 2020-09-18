# v1.13.2

### 🔥 Firestore Update
 - Macro uses Firestore to keep meeting data synced. Node has an issue with Firestore sending requests too quickly so we made a quick queue to prevent app crashes.

### 🐛 Bug Fixes
 - CSS got all wonky with a recent release but this is fixed now so your divs are all in order once again.
 - Electron windows were having a hard time closing at the end of some meetings, keeping Macro open and requiring a force quit. This is now fixed.
