# 💻 whmv-C3D Viewer

> **A browser-based 3D motion capture viewer to inspect, label, and analyze `.c3d` files directly in your web browser—no installation required.**

<p align="center">
  <img src="https://raw.githubusercontent.com/whymv/whmv-C3D-Viewer/main/img/example_gait.gif" width="720" alt="C3D Viewer Gait Demo" />
</p>

<p align="center">
  <a href="https://whymv.github.io/whmv-C3D-Viewer/">
    <img src="https://img.shields.io/badge/👉_Click_to_Open_Viewer-blue?style=for-the-badge" alt="Click to Open Viewer" />
  </a>
  <a href="./LICENSE">
    <img src="https://img.shields.io/badge/License-AGPL--3.0-green?style=for-the-badge" alt="License: AGPL-3.0" />
  </a>
</p>

---

## ⚡ Overview

A web tool to quickly open `.c3d` motion capture files right in your browser. All processing runs entirely on your local machine—no server uploads, no software setup.

- **3D Viewport**: Orbit, pan, zoom, frame-by-frame control (`,` / `.`), and speed adjustment (0.25×–1×).
- **Signals**: View synchronized analog channels (EMG, Force Plate) alongside the 3D playback.

---

## 🛠 Quick Workflow

### 1. View Raw Markers
Click the **'Open C3D'** button or drop any `.c3d` file directly into the browser. Inspect raw marker coordinates, frame count, duration, and sampling rates immediately.

<p align="center">
  <img src="https://raw.githubusercontent.com/whymv/whmv-C3D-Viewer/main/img/01_initial.png" width="700" alt="Initial Raw Markers" />
</p>

---

### 2. Label & Group
Organize markers by body segment (**Trunk**, **Right/Left Limbs**, **Etc**). Supports auto-assignment based on standard marker naming conventions.

<p align="center">
  <img src="https://raw.githubusercontent.com/whymv/whmv-C3D-Viewer/main/img/02_labeling.png" width="700" alt="Marker Labeling" />
</p>

---

### 3. Links & Analysis
Connect markers into skeletons and calculate key biomechanical metrics.

<p align="center">
  <img src="https://raw.githubusercontent.com/whymv/whmv-C3D-Viewer/main/img/03_link.png" width="700" alt="Segment Linking and Skeleton" />
</p>

- **Auto-link**: Apply skeleton templates (Plug-in Gait, Cortex, OpenSim).
- **Joint Centers & COM**: Automatic detection of joint centers (Knee, Ankle, Hip) and whole-body Center of Mass (COM).
- **GRF & EMG**: Ground Reaction Force (GRF) vectors and raw / RMS EMG signal visualization.

---

## 📄 License

> **GNU Affero General Public License v3.0 (AGPL-3.0)**  
> This project is open-source. For details, see the [LICENSE](./LICENSE) file.
