# Alexei | Systems Integration & AI/ML Engineer

> **Specialization:** Applied Optical & Embedded Hardware · High-Throughput MLOps Inference · Local-First Knowledge & Agent Architectures  
> **Location:** Helsinki, Finland  
> **Links:** [LinkedIn](https://linkedin.com) · [GitHub](https://github.com) · [Email](mailto:your-email@example.com)

---

## Executive Summary

**Systems Integration and AI/ML Engineer** with 3+ years of experience building end-to-end technical systems across custom hardware, computer vision pipelines, and on-premise compute infrastructure. I specialize in bridging physical and digital domains: designing custom optical and experimental apparatuses from scratch, developing high-throughput automated ML pipelines, and architecting local AI systems. My focus is translating complex physical and computational constraints into reliable, production-ready workflows.

---

## Flagship Engineering Projects

### 1. [Full-Field Spherical Stimulator & Ocular Reflex Rig](https://github.com/AlexeiKramm/full-field-spherical-stimulator)
**Tech Stack:** `Python` · `OpenGL (GLSL)` · `Raspberry Pi` · `MQTT` · `Fusion 360` · `OpenCV`

A custom electro-optical platform engineered from scratch when no commercial system existed that could deliver **full-field optical stimulation** (~300°) while tracking **gaze** in unrestrained subjects. I designed a 3D-printed projection chamber with an internal spherical convex mirror, developed automated closed-loop calibration routines, and wrote real-time GLSL fragment shaders to correct geometric distortions caused by projecting flat images onto a curved inner sphere. Orchestrated over MQTT, the integrated system operated **24/7 unattended for 1–2 week experiment runs** on Raspberry Pi edge hardware.

---

### 2. [High-Throughput Keypoint Inference Pipeline & MLOps Suite](https://github.com/AlexeiKramm/High-Throughput-Keypoint-Inference-Pipeline)
**Tech Stack:** `Python` · `TensorFlow` · `OpenCV` · `Albumentations` · `NumPy` · `Tkinter`

An asynchronous deep learning pipeline built to track pupil keypoints across multi-thousand video datasets where standard tools (DeepLabCut) were bottlenecked at 40–60 FPS. I built a custom end-to-end TensorFlow pipeline featuring a lightweight 2-stage CNN (Finder → Placer) with sub-pixel coordinate extraction and a desktop inspection GUI for rapid validation. The system accelerated inference throughput from **40–60 FPS to ~300 FPS (~5x speedup)**, reducing dataset turnaround from **approximately 1 week to 1 day**.

---

### 3. [Local-First Hierarchical Knowledge Engine & FastMCP Server](https://github.com/AlexeiKramm/Local-First-Hierarchical-Knowledge-Engine)
**Tech Stack:** `Python` · `FastMCP` · `SQLite (FTS5)` · `llama.cpp / vLLM`

A privacy-first knowledge retrieval engine and Model Context Protocol (FastMCP) server engineered to eliminate context saturation when querying multi-year temporal text archives with local LLMs. I architected an ingestion pipeline using local SLM parsing (Qwen 3.5 4B) and a pre-computed 4-tier hierarchical summarization pyramid (Day → Year) that enables agents to navigate timelines top-down without brute-force context dumps. The system allows local models to resolve complex longitudinal queries (such as comparing project milestones, recurring habits, or life events across 6+ years) 100% offline on consumer GPUs with zero external data leakage.

---

## Core Competencies & Technical Skills

* **Languages & Core Tooling:** Python (NumPy, SciPy, OpenCV, Flask, TensorFlow), Bash, MATLAB, C/C++ (Embedded), Git.
* **Hardware & Systems Integration:** Single-Board Computers (Raspberry Pi), Microcontrollers (ESP32), Precision Electro-Optical Calibration (Photometry, Geometric Distortion, Spatial Scaling), Serial / MQTT Communication, 3D CAD & Rapid Prototyping (Fusion 360, 3D Printing).
* **Computer Vision & Machine Learning:** Custom CNN Models (Sub-Pixel Keypoint Tracking, Multi-Class Classification), High-Throughput Inference (TensorFlow), Custom Data Annotation & Inspection GUIs (Tkinter).
* **Local AI & Agent Systems:** Model Context Protocol (FastMCP), Local LLM Serving (`llama.cpp`, `vLLM`), Local Audio & Image Pipelines (`Whisper`, `ComfyUI`).
* **Infrastructure & Storage:** Linux Server Administration & Virtualization, TrueNAS (ZFS), 3-2-1 Backup Architecture, Docker.
* **Applied Domain & Experimental Systems:** Visual Psychophysics, Pupillometry & Gaze Tracking, Custom Experimental Rigs, Automated Data Collection & Analysis Pipelines.
