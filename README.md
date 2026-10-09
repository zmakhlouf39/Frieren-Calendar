# Frieren's Grimoire

Single-file weekly time-blocking calendar. Open `index.html` in a browser. No build, no dependencies.

- Drag on a column to create a block; drag a block to move it; drag its bottom edge to resize; click to edit.
- Data lives in your browser (localStorage). Use Export/Import for backups.
- Night/dawn theme toggle, arrow keys change week.

## Android APK

The `Build APK` GitHub Action wraps `index.html` with Capacitor and builds a debug APK.
Actions tab → latest "Build APK" run → download the `frieren-grimoire-apk` artifact → unzip → install `app-debug.apk` on your phone (allow "install unknown apps").
