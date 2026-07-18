# 📻 Bajaune (बजाउने)

Bajaune is a premium, desktop-grade, zero-dependency theater soundboard application optimized for live high-stakes theater productions. Engineered to run completely within a single browser viewport as a self-contained `index.html` file, it combines minimalist Apple/Figma-inspired dark aesthetics with the robust scheduling accuracy of the native Web Audio API. 

Perfect for production environments where software crashes are not an option, Bajaune is fully portable and completely ready to host instantly on GitHub Pages.

---

## 🚀 Key Architectural Strengths

*   **Zero Dependencies:** Crafted purely out of semantic HTML5, localized CSS structural design models, and high-performance vanilla ECMAScript. No bundlers, no external asset libraries, and no hidden package installations.
*   **Sample-Accurate Playback Graphs:** Built directly upon a Web Audio API routing infrastructure ensuring near-zero latency execution, simultaneous multi-track cue firing, and artifact-free precision crossfades.
*   **Performance Lock Mode:** Dedicated performance state lock layer hiding administrative config modules and key-assignment controls to eliminate accidental alterations during critical live cues.
*   **Resilient Failure Fallbacks:** Gracefully degrades from modern File System Access API interfaces down to individual asynchronous multi-file upload managers when operating under restricted security scopes.

---

## 🛠️ Feature Breakdown

### 🎯 High-Visibility Hotkey Matrix
*   **Prominent Key Indicators:** Extra-large, high-contrast, bold key labels built directly into card headers for error-free tracking at a distance under low light.
*   **Strict Collision Prevention Engine:** Hardwired structural rules prevent multiple channels from sharing a single trigger block or a single cue map occupying multiple keys.
*   **Exclusive Master Interrupt:** The **Spacebar** is isolated at the engine root level and reserved exclusively for the global **STOP ALL** macro.

### 🎛️ Configurable Cue-Deceleration Modes
*   **Abrupt Termination:** Instant digital audio muting without click artifacts.
*   **Linear Web Audio Fades:** Precision amplitude sloping driven by sample-synchronized Web Audio parameters (`linearRampToValueAtTime`) adjustable on an individual card boundary basis from 1s to 5s.
*   **Smart Toggles:** Pressing an active hotkey a second time will execute the specific card's stop behavior, while pressing it a third time during a fade cancels the fade and immediately restarts the cue clean.

### 📊 Fluid Performance UI
*   **Auto-Adapting Densities:** Automatically adjusts padding, layout sizing, and visualization scaling if massive cue structures (tested up to 500 tracks) are parsed.
*   **Instant Predictive Search:** Linear key and filename filtering updating the display layout live with standard character entries.
*   **State Serialization:** Import and export your entire workspace layout setup array instantly into clean JSON objects.

---

## 📖 Quick Start Blueprint

### Prerequisites
*   A modern evergreen browser supporting the Web Audio API (Chrome, Edge, Safari, Firefox).

### Setup and Ingestion
1. **Download the Core Matrix:** Clone or copy the single standalone `index.html` file into your computer.
2. **Launch Application:** Double-click `index.html` to execute locally or upload the script directly to your GitHub Pages repository branch.
3. **Populate Canvas:** Click **Load Sounds**, then select either a whole asset directory workspace folder or multi-select individual stems (`.mp3`, `.wav`, `.ogg`, `.m4a`, `.flac`).
4. **Link Cues:** Click any prominent card header shortcut block and tap a keyboard key to lock down the hotkey mapping.
5. **Protect Setup:** Toggle **Performance Lock** to safe-mode once configurations are aligned, ensuring your setup is locked down for live show operations.

---

## 🤝 Contribution Guidelines

Bajaune is a single-file orchestration framework. When proposing changes:
1. Ensure all CSS properties are localized cleanly within the global root variables palette.
2. Avoid attaching code fragments to external CDNs or linking structural modules out of the single-file perimeter.
3. Maintain non-blocking, asynchronous execution throughout the main event loop thread using native `requestAnimationFrame` configurations.
