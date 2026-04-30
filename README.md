# 360 Video Viewer App

A Windows PCVR application for viewing 360° videos on the HTC VIVE headset, built with Unity. Supports both stereoscopic 3D and 2D footage captured by devices such as the **Insta360 X4**, **X5**, **Pro2**, and the **Antigravity A1** drone, with full ambisonic audio support.

---

## Contents of This Repository

| File | Description |
|------|-------------|
| `360-Video-Viewer-App.zip` | Complete Unity project (attached in Releases) |
| `StepbyStep-Guide.pdf` | Step-by-step build and usage guide |

> The Unity project zip file is available under [**Releases**](../../releases). See the setup guide PDF for build instructions.

---

## Features

- 360° video playback in VR (HTC VIVE / Windows PCVR)
- Stereoscopic 3D and standard 2D video support
- Ambisonic spatial audio up to 4 channels (AmbiX format)
- Optimized for large, high-resolution video files

---

## Video Compatibility

| Format | Maximum Resolution |
|--------|--------------------|
| 2D | 6144 × 3072 |
| 3D (Stereoscopic) | 6144 × 6144 |

- **Preferred format:** MP4
- **Preferred codec:** H.265 (HEVC)
- Stereoscopic 3D videos must be formatted **left eye on top** (top-bottom layout)

---

## Audio Compatibility

- Mono and stereo audio
- Ambisonic audio up to **4 channels**, encoded in **AmbiX format**
- **Preferred format:** WAV

---

## Getting Started

Refer to the **StepbyStep-Guide.pdf** included in this repository for step-by-step instructions on how to build and run the application from the Unity project.

### Requirements

- Unity (see setup guide for recommended version)
- Windows PC with SteamVR installed
- HTC VIVE headset
