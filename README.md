# Asset Links & Packages

A curated index of Unity packages, Asset Store dependencies, and modular project setup workflows.

> **Note:** 💰 denotes a paid Asset Store package.

---

## 🏗️ Menu System & Modularization

- **Package Modularization:** Convert core systems (splash screen, localization, input rebinding, etc.) into separate Git packages.
- **Menu System:** Turn the menu system into a private Git package, bundled with sample scenes containing the demo game.

---

## 📦 Git Packages

### Manual Installation
Follow this installation order:
1. `EditorTools`
2. `Utilities` (Install after installing DOTween; DOTween may be auto-installable via `EditorTools` if cached locally)
3. Install NuGet `https://github.com/GlitchEnzo/NuGetForUnity.git?path=/src/NuGetForUnity`, then install the NuGet packages:
   - `R3`
   - `UniTask`
   - `ZLinq`
4. `SuperUnityBuild` & `SuperUnityBuild Build Actions`

### Auto-Install
*(Pre-configured in `EditorTools`; external links not required)*

- **Improved Timers** (personal fork)
- **Unity Utilities Library**
- **EditorWindowMaximizer**
- **GG Camera Shake**
- **NuGetForUnity**
- **yFullscreen** (personal fork)
- **Simple Folder Icon**
- **Eflatun.SceneRef**
- **KyleBanks/scene-ref-attribute**
- **Modular-MVP**
- **Cysharp Suite:**
  - `R3`
  - `UniTask`
  - `ZLinq`
- **Graphy**
- **LUT Library** (used to be on asset store but not anymore)
- **Audio System** (*TODO*)

---

## 🏪 Asset Store & Project Assets

### 🐞 Debug
- [Quantum Console (QSFW)](https://assetstore.unity.com/packages/tools/utilities/quantum-console-211046) 💰

### 🛠️ Editor
- [vInspector 2](https://assetstore.unity.com/packages/tools/utilities/vinspector-2-252297) 💰
- [Editor Auto Save (IntelliNation)](https://assetstore.unity.com/packages/tools/utilities/editor-auto-save-234445)
- [Unity Editor Dark Mode (Windows)](https://assetstore.unity.com/packages/tools/gui/darkmode-for-unity-editor-on-windows-281842)
- [Audio Preview Tool](https://assetstore.unity.com/packages/tools/audio/audio-preview-tool-244446)

### ⚡ Optimizations
- [Update Manager](https://assetstore.unity.com/packages/tools/utilities/update-manager-53581)

### 🎬 Animation & Tweening
- [DOTween (HOTween v2)](https://assetstore.unity.com/packages/tools/animation/dotween-hotween-v2-27676)

### 🎨 Rendering, Post-Processing & Textures
- [Scalable Prototype Textures](https://assetstore.unity.com/packages/2d/textures-materials/grid-prototype-materials-214264): Scalable so easily the best ones.
- Skybox
  - [AllSky Free - 10 Sky / Skybox Set](https://assetstore.unity.com/packages/2d/textures-materials/sky/allsky-free-10-sky-skybox-set-146014)
  - [Fantasy Skybox FREE](https://assetstore.unity.com/packages/2d/textures-materials/sky/fantasy-skybox-free-18353)
  - [Stylized Skyboxes | FREE](https://assetstore.unity.com/packages/2d/textures-materials/sky/stylized-skyboxes-free-302248)

### 🖥️ UI
- [Evo UI - Modern UI Framework](https://assetstore.unity.com/packages/tools/gui/evo-ui-modern-ui-framework-310303) 💰
- [Flat pack - GUI by CorePro](https://assetstore.unity.com/packages/2d/gui/flat-pack-gui-307236): 💰 Paid, but was free on publisher sale.
- [Skymon Icon Pack Free](https://assetstore.unity.com/packages/2d/gui/icons/skymon-icon-pack-free-282424)
- [FPS Icons Pack by Infima](https://assetstore.unity.com/packages/p/fps-icons-pack-45240): Deprecated. Exists in the template project if ever required.

### 🗑️ Deprecated / Removed
- `EditorThemes` — Removed (unnecessary bloat; default theme preferred)
- `TimeScale Toolbar` — Removed (unnecessary bloat; use QSFW instead)
- `BetterHierarchy` — Removed (no longer needed in Unity 7+)

---

## 📋 TODO

######  **EditorTools:** 
- [ ] Update the cached Asset Store auto-install list in `EditorTools` only after migrating to Unity 7 (requires a new template project and fresh installations).
###### **Git Packages:**
- [ ] Watch git-amend tutorials for the three Cysharp packages (`R3`, `UniTask`, `ZLinq`) to configure installation via NuGet.
- [ ] Convert Audio into a Git package (refactor `AudioManager` into a ScriptableObject and transition pooled audio to an SO-based pattern).
###### **Unity Packages:**
- [ ] Convert personal assets into modular Unity packages and delete them from the sample project.
