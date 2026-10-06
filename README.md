<div align="center">
  <img src="https://raw.githubusercontent.com/GRIMREAPER35487/Synthos-VRC-Packages/main/.github/banner.png" alt="Synthos VRC Packages" width="100%" />

  <br/><br/>

  <a href="https://grimreaper35487.github.io/Synthos-VRC-Packages/">
    <img src="https://raw.githubusercontent.com/GRIMREAPER35487/Synthos-VRC-Packages/main/.github/browse_vpm_repository.png" alt="Browse VPM Repository" height="46" />
  </a>
</div>

<br/>

# Synthos VRC Packages

Official VPM (VRChat Package Manager) listing for Synthos tools, optimization suites, and editor extensions.

Add this repository to your VRChat Creator Companion (VCC) or ALCOM to install and receive automatic updates for all Synthos packages.

---

### Quick Install

- **One-Click Add (VCC / ALCOM):**  
  [Add to VCC](vcc://vpm/addRepo?url=https%3A%2F%2Fgrimreaper35487.github.io%2FSynthos-VRC-Packages%2Findex.json)

- **Listing URL (Manual Add):**  
  ```text
  https://grimreaper35487.github.io/Synthos-VRC-Packages/index.json
  ```

---

### Included Packages

| Package | Identifier | Description |
| :--- | :--- | :--- |
| [**Synthos Batch Uploader**](https://github.com/GRIMREAPER35487/VRC-Batch-Uploader) | `com.synthos.batch-uploader` | Unattended multi-avatar batch uploader with multi-platform synchronization (PC / Android / iOS), blendshapes, and material overrides. |
| [**Synthos Scene Optimizer**](https://github.com/GRIMREAPER35487/SynSceneOptimiser) | `com.synthos.scene-optimizer` | Non-destructive world and scene performance suite featuring texture VRAM downscaling, mesh simplification, GPU instancing, audio, and particle audits. |
| [**Synthos Frame Debugger Exporter**](https://github.com/GRIMREAPER35487/SynFrameDebugger) | `com.synthos.frame-debugger` | Inspects and exports Unity Frame Debugger event streams, draw calls, shader properties, and batch break causes to structured JSON. |
| [**Meshia Mesh Simplification**](https://github.com/GRIMREAPER35487/Meshia.MeshSimplification-Synthos) | `com.synthos.meshia` | Burst-accelerated mesh decimation library decoupled from NDMF with independent UV barycentric preservation and native VRCFury support. |
| [**Avatar Compressor**](https://github.com/GRIMREAPER35487/avatar-compressor-Synthos) | `com.synthos.avatar-compressor` | High-performance avatar texture optimization utility decoupled from NDMF with native VRCFury hooks and non-destructive runtime baking. |

---

### Automated Deployment

Package releases from the individual repositories automatically trigger the `Build Repo Listing` GitHub Actions workflow in this repository. The action compiles the latest releases, generates `index.json`, and publishes the live catalog to GitHub Pages.
