# Advanced Video Compressor

![Python Version](https://img.shields.io/badge/python-3.7%2B-blue)
![PySide6](https://img.shields.io/badge/PySide6-6.4%2B-green)
![FFmpeg](https://img.shields.io/badge/FFmpeg-required-orange)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

A **cross‑platform GUI application** built with PySide6 that leverages FFmpeg to compress video files with fine‑grained control over codec, quality, bitrate, resolution, and encoding preset. Perfect for reducing file sizes while maintaining quality.

---

## Features

- 📁 **Select multiple video files** (MP4, AVI, MKV, etc.)
- 📂 **Choose custom output directory**
- 🎚️ **Advanced encoding options**:
  - Codec: H.264 (`libx264`) or H.265 (`libx265`)
  - CRF (Constant Rate Factor) from 0–51
  - Video bitrate (in kbps)
  - Audio bitrate (in kbps)
  - Encoding preset (ultrafast to veryslow)
  - Resolution scaling (or keep original)
- ✅ **Batch processing checkbox** (placeholder for future extension)
- 📊 **Live progress bar** – shows compression progress based on FFmpeg output
- 🧵 **Multi‑threaded** – compression runs in a separate thread, UI stays responsive

---

## Requirements

- **Python 3.7+**
- **PySide6** – for the GUI
- **FFmpeg** – must be installed and accessible in your system PATH

---

## Installation

1. **Clone the repository** (or download the script):
   ```bash
   git clone https://github.com/yourusername/advanced-video-compressor.git
   cd advanced-video-compressor
