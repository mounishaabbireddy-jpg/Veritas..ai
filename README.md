# VERITAS AI — See Beyond the Synthetic

> Advanced synthetic media detection and forensic signal analysis platform for images and videos.

![VERITAS AI](https://images.unsplash.com/photo-1544005313-94ddf0286df2?auto=format&fit=crop&w=1200&q=80)

---

## 🌟 Overview

**VERITAS AI** is an intelligent, multi-vector synthetic media analysis platform designed to help journalists, researchers, and digital investigators evaluate whether images and videos are AI-generated or manipulated.

Rather than relying on opaque binary classifications, VERITAS decomposes media across orthogonal forensic axes:
- **Spatial & Frequency Domain**: Error Level Analysis (ELA) and Discrete Cosine Transform (DCT) high-frequency deconvolution.
- **Physical Optical Consistency**: Bi-ocular corneal catchlight vector raytracing and specular reflection coherence.
- **Temporal Video Scrutiny**: Inter-frame optical flow stability, latent keyframe drift, and blink cadence.
- **Container & Hardware Telemetry**: JPEG APP1 EXIF headers, silicon sensor Photo-Response Non-Uniformity (PRNU), and C2PA Content Credentials.

---

## 🚀 Key Features

- **Multi-Format Ingestion**: Supports JPG, JPEG, PNG, WEBP images and MP4, MOV, WEBM videos.
- **Interactive Forensic Lens**: Real-time client-side canvas shaders for:
  - Error Level Analysis (ELA) compression heatmaps
  - High-Pass Edge Continuity filtering
  - Inverted Luminance false-color maps
  - Interactive split wipe comparison slider
- **Explainable Verdicts**: Strictly categorized into `Likely AI-generated`, `Likely authentic`, or `Inconclusive` with uncertainty intervals (e.g. 89% ± 6%).
- **Benchmark Library**: 4 pre-indexed test cases for instant 1-click evaluation.
- **Zero Retention**: All client-side inspections run in-memory; no files are logged or used for model training.
- **Full-Stack Architecture**: Express server with Vite dev middleware and modular server-side forensic inspection proxy (`/api/analyze`).

---

## 🛠️ Tech Stack

- **Frontend**: React 19, TypeScript, Tailwind CSS v4, Lucide Icons, Canvas 2D API
- **Backend**: Express, Node.js, `@google/genai`
- **Build Tool**: Vite 8, `tsx`

---

## 📦 Getting Started

### Prerequisites

- Node.js 18+ or 20+
- npm or yarn

### Installation

```bash
# Clone repository
git clone https://github.com/<your-username>/veritas-ai.git
cd veritas-ai

# Install dependencies
npm install
