# Matryoshka Multimodal Authentication Dataset

This repository contains the standalone dataset released in support of the research paper: 
**"Authenticating Matryoshka Nesting Dolls via an Auditable 2D–3D–Text Evidence Framework"**.

## Dataset Specifications
- **Format:** High-Definition (1920x1080) Turntable Videos and extracted frames.
- **Physical Metadata:** 168 unique physical sets with an average of 4.2 shells per set.
- **Sampling Density:** 20 frames per shell (sampled at 360-degree turntable intervals).
- **Total Frames:** 27,387 labeled RGB frames.
- **Evidence Streams:** 2D Frames (.png), BMA Skeletons (.png), 3D Meshes (.obj), and Semantic Reports (.json).

## Directory Structure
- `/frames`: RGB images organized by Video ID.
- `/3d_models`: Reconstructed meshes and point clouds.
- `/metadata`: `index.csv` containing labels for 8-way style and 3-way authenticity.
- `/captions`: Semantic reports generated via Qwen3-VL.

## DOI & Citation
Digital Object Identifier: **[INSERT DOI HERE AFTER ZENODO RELEASE]**

Please cite as:
Kumar, Y., & Sengupta, S. (2026). Matryoshka Multimodal Dataset for Cultural Heritage Authentication. Zenodo.
