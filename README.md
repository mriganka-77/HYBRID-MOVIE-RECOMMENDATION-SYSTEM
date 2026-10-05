# 🎬 Sylva Cinema — Hybrid Movie Recommendation System

An intelligent, state-of-the-art cinematic discovery and movie recommendation engine harmonizing **Collaborative Filtering** and **Content-Based Filtering** with the award-winning **Sylva** editorial aesthetic.

🔗 **Live Production Site**: [https://sylva-jet.vercel.app/](https://sylva-jet.vercel.app/)

---

## 🌟 Key Features

### 1. 🍃 Sylva Luxury Visual & Shader Architecture
- **Interactive Floating Dock**: Featuring physics-based proximity magnification, active section indicators, and dynamic specular rim lighting (`[data-spec]`) tracking cursor angle.
- **Liquid-Metal Dispersion Shader Controls**: Multi-pass WebGL2 fluid metal shaders with chromatic aberration, ripple dynamics on press, and pointer warp fields.
- **Three.js 3D Celestial Atmosphere**: Procedural floating film ribbons, celestial stardust pollen particles, and velocity-sensitive cursor lighting.
- **Stepped Transmission Portals**: Custom canvas pixel-reveal animations simulating transmission scans on curated film photography cards.
- **Custom Lexend & Obsidian Design System**: Tailored typography with glassmorphism, responsive unit scaling (`--u: calc(100vw / 1600)`), and smooth parallax planes.

### 2. 🧠 Intelligent Hybrid Recommendation Engine
- **Collaborative Filtering (SVD)**: Decomposes the User-Movie rating matrix into low-rank 512D latent orthogonal matrices ($U \Sigma V^T$) to uncover latent taste archetypes.
- **Content-Based Semantic Embeddings**: Employs deep tag vectors and cosine similarity across genres, directorial signatures, thematic tropes, and sonic landscapes (e.g. Hans Zimmer motifs).
- **Adaptive Weight Tuning**: Live interactive slider controlling $\alpha \in [0, 1]$:
  $$\hat{S}(u, i) = \alpha \cdot \hat{R}_{\text{CF}}(u, i) + (1-\alpha) \cdot \text{Sim}_{\text{CB}}(i, A_u)$$
- **Dynamic User Personas**: Switch between *Sci-Fi Visionary*, *Auteur & Arthouse*, *Psychological Stakes*, and *Dreamscape Animation*.
- **Live User Profile Calibration**: Star ratings on any film dynamically recalibrate personal preference vectors in real time.
- **Curated Film Universes (Habitats)**: Explore thematic micro-clusters such as *Echoes of the Cosmos*, *Neon & Rainy Shadows*, and *Hand-Drawn Reverie*.
- **Curated Watchlist Drawer & HD Trailer Modal**: Save films to persistent local storage and launch cinematic trailers in an immersive dark theater modal.

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v16+) or Python 3

### Running Locally

```bash
# Clone and enter the workspace
cd HYBRID-MOVIE-RECOMMENDATION-SYSTEM-main

# Start the application server
npm start
# or
node server.js
```

Open your browser at:
```
http://localhost:3000
```
