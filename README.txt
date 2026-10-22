SYNTAX TREE — REFERENCE REPLICA

This is a mobile-first Capacitor web app styled to closely reproduce the supplied eight-screen Syntax Tree mockup.

Included screens: Home, New Tree, Build Your Tree, Syntax Tree, Tree Style, Settings, Export & Share, Bracket Notation, About.

Features: manual constituent-span labeling, S/TP/CP/NP/VP/PP and other labels, curved/straight/angled/bracket branches, light/dark mode, accent colors, bracket notation, TXT export, PNG export, Web Share support where available, and offline operation.

Build APK: push these files to GitHub main/master, then open Actions and run “Build Syntax Tree Builder APK”. Download the syntax-tree-builder-debug-apk artifact after a successful run.

Note: radial is shown as a style choice in the reference-inspired interface but currently maps to the curved layout. The tree is manually built; the app does not automatically parse arbitrary English syntax.

Update: fixed the broken settings (Show Node Numbers, Word Positions, Show All Labels, Auto Save, Animations, Dark Mode switch), Auto Save now restores your sentence and labels, the Build screen tree preview now scales to fit the screen, PNG/TXT export and sharing use the native Android share sheet, the Android back button navigates between screens, crossing (non-nested) labels are rejected, and the new app icon is included.
