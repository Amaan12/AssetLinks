# Asset Links & Packages

> A curated index of Unity packages, Asset Store dependencies, and modular project setup workflows.
> 
> 💰 = paid

---

# 📦 Git Packages

- [EditorTools](https://github.com/Amaan12/EditorTools.git)
- [Utilities](https://github.com/Amaan12/Utilities.git)
- [Unity Utilities Library](https://github.com/adammyhre/Unity-Utils.git)
- [EditorWindowMaximizer](https://github.com/longbombus/FullScreenUnityEditor.git)
- [GG Camera Shake](https://github.com/gasgiant/Camera-Shake.git#upm)
- [NuGetForUnity](https://github.com/GlitchEnzo/NuGetForUnity.git?path=/src/NuGetForUnity)
- [Simple Folder Icon](https://github.com/SeaeeesSan/SimpleFolderIcon.git?path=Packages/com.seaeees.simple-folder-icon)
- [Eflatun.SceneRef](https://github.com/starikcetin/Eflatun.SceneReference.git#upm)
- [KyleBanks/scene-ref-attribute](https://github.com/KyleBanks/scene-ref-attribute.git)
- **Cysharp Suite:**
  - [R3](https://github.com/Cysharp/R3.git?path=src/R3.Unity/Assets/R3.Unity) (_install this after the NuGet package R3 is installed and compiled._)
  - [UniTask](https://github.com/Cysharp/UniTask.git?path=src/UniTask/Assets/Plugins/UniTask)
- [Graphy](https://github.com/Tayx94/graphy.git)
- [LitMotion](https://github.com/annulusgames/LitMotion.git?path=src/LitMotion/Assets/LitMotion)
- [Improved Timers](https://github.com/Amaan12/Unity-Improved-Timers.git) (_personal fork_)
- [Logging System](https://github.com/Amaan12/LoggingSystem.git)
- [yFullscreen](https://github.com/Amaan12/yFullScreen.git) (_personal fork_)
- [Modular-MVP](https://github.com/Amaan12/Modular-MVP.git)
- [LUT Library](https://github.com/Amaan12/Cinematic-Look-LUT-Library.git) (_used to be on asset store but not anymore_)
- [Audio System](https://github.com/Amaan12/AudioSystem.git)
- [SuperUnityBuild](https://github.com/superunitybuild/buildtool) & [SuperUnityBuild Build Actions](https://github.com/superunitybuild/buildactions)

---

# 🏪 Asset Store

#### 🐞 Debug
- [Quantum Console](https://assetstore.unity.com/packages/tools/utilities/quantum-console-211046) 💰

#### 🛠️ Editor
- [vInspector 2](https://assetstore.unity.com/packages/tools/utilities/vinspector-2-252297) 💰
- [Editor Auto Save](https://assetstore.unity.com/packages/tools/utilities/editor-auto-save-234445)
- [DarkMode for Unity Editor on Windows](https://assetstore.unity.com/packages/tools/gui/darkmode-for-unity-editor-on-windows-281842)
- [Audio Preview Tool](https://assetstore.unity.com/packages/tools/audio/audio-preview-tool-244446)

#### ⚡ Optimizations
- [Update manager](https://assetstore.unity.com/packages/tools/utilities/update-manager-53581)

#### 🎨 Rendering, Post-Processing & Textures
- Textures
  - [Grid Prototype Materials](https://assetstore.unity.com/packages/2d/textures-materials/grid-prototype-materials-214264) (_Scalable shader so easily the best ones._)
- Skybox
  - [AllSky Free - 10 Sky / Skybox Set](https://assetstore.unity.com/packages/2d/textures-materials/sky/allsky-free-10-sky-skybox-set-146014)
  - [Fantasy Skybox FREE](https://assetstore.unity.com/packages/2d/textures-materials/sky/fantasy-skybox-free-18353)
  - [Stylized Skyboxes | FREE](https://assetstore.unity.com/packages/2d/textures-materials/sky/stylized-skyboxes-free-302248)

#### 🖥️ UI
- [Evo UI - Modern UI Framework](https://assetstore.unity.com/packages/tools/gui/evo-ui-modern-ui-framework-310303) 💰
- [Flat pack - GUI](https://assetstore.unity.com/packages/2d/gui/flat-pack-gui-307236): 💰
- [Skymon Icon Pack Free](https://assetstore.unity.com/packages/2d/gui/icons/skymon-icon-pack-free-282424)
- [FPS Icons Pack by Infima](https://assetstore.unity.com/packages/p/fps-icons-pack-45240) (_Deprecated, still owned if required.)_

---

> # *TODO*
  - **Package Modularization:** Convert core systems (splash screen, localization, input rebinding, UI feel, GoogleSheets/Docs API fetcher, loader, etc.) into separate Git packages.
  - **Menu System:** Turn the menu system into a private (or maybe public) Git package, bundled with sample scenes containing the demo game. Then with AI makes loads and loads of samples, no functionality just samples.
  - **Shader Library (CLI)**: Pull individual .unitypackage shaders from GitHub.
  - **Input Actions (CLI)**: Pull genre .inputactions presets from GitHub.
  - **Sibling Imports Folder (Git Package)**: Virtual folder with SO toggle. Already made, waiting for Unity 7 to update in one go.
  - **CI/CD Tool (Git Package)**: GitHub Actions
