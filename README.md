# Automated AI Video Generation with ComfyUI

## Overview
ComfyUI is now installed and configured in this directory with **ComfyUI-Manager** ready to use.

---

## Quick Start: Launch ComfyUI

You can start ComfyUI at any time using:
- **Shortcut:** Double-click [Start_ComfyUI.bat](file:///c:/Users/DEELL/Documents/Automated%20Ai%20video/Start_ComfyUI.bat) in the root folder, or
- **Inside ComfyUI folder:** Double-click [run_cpu.bat](file:///c:/Users/DEELL/Documents/Automated%20Ai%20video/ComfyUI/run_cpu.bat).

Once started:
1. A terminal window will open and load ComfyUI.
2. Your default web browser will automatically open to [http://127.0.0.1:8188](http://127.0.0.1:8188).

---

## Hardware Configuration & Generating Videos

Your machine has:
- **GPU:** Intel HD Graphics 520 (integrated graphics)
- **RAM:** 8 GB

> [!IMPORTANT]
> Modern local AI video models (such as Wan 2.1, HunyuanVideo, LTX-Video, or CogVideoX) require a dedicated NVIDIA GPU with **12 GB+ to 24 GB+ VRAM** and 16+ GB system RAM. Running those multi-gigabyte models entirely on integrated Intel graphics will quickly exhaust RAM and fail or take hours per frame.

### Recommended Ways to Make Videos:
1. **Cloud & API Nodes inside ComfyUI (Best & Easiest):**
   - Click the **Manager** button on the bottom right in ComfyUI.
   - Search for API/cloud provider nodes (such as **Fal.ai**, **Replicate**, **Runware**, or **Kling**).
   - These nodes let you build visual node workflows locally in ComfyUI while sending the heavy video rendering to fast cloud GPUs via inexpensive API keys.
2. **Cloud ComfyUI Instances:**
   - If you want full custom open-source model control without paying for local hardware, you can run ComfyUI workflows on **Google Colab (T4/A100 GPU)**, **RunComfy**, or **Vast.ai / RunPod**.
