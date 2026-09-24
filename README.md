# Coordination of Spiral Waves in the Motor Cortex
**Honours Research Project & Final Defense**  
*School of Physics | Faculty of Science | The University of Sydney*

- **Author:** Adam Karvon
- **Supervisor:** Dr. Pulin Gong
- **Degree:** Bachelor of Science and Bachelor of Advanced Studies (Honours)
- **Submission Date:** May 17, 2024

---

## Abstract

Advances in brain-imaging techniques have revealed highly organized patterns of spatiotemporal activity as core features of the processes that are central to our understanding of cognition. Although the presence of spiral-shaped brain waves in functional magnetic resonance imaging (fMRI) recordings is well-documented, their role in cognitive processing and the organizational principles underlying their dynamics are still uncertain.

Here, based on human fMRI recordings, we investigate the mechanistic role of spiral waves in coordinating turbulent-like cortical dynamics and their functional correlates with human motor behaviours. Consistent with previous studies, we find the properties of these spiral waves, such as their rotational directions and locations, to be task-relevant and valuable in the neural decoding of motor tasks. By observing the flow of brain activity, we elucidate hubs of activity surrounded by pairs of spiral waves with the description of elementary rules that mechanistically describe the functional role of these spirals. 

Additionally, using a mathematical model, we demonstrate that unique interactions among an array of spiral waves distributed across the cortex can successfully capture the structure of the underlying brain function. Specifically, we can reliably predict the complex dynamics of the human cortex solely based on the spatial configurations of the spiral wave array, which consists of only a few dozen spiral wave patterns. These findings provide novel evidence supporting the mechanistic and functional importance of cortical spiral waves underlying motor function in the human brain.

---

## Repository Contents

| Deliverable | File | Description | Size |
| :--- | :--- | :--- | :--- |
| **Honours Thesis** | [`Honours_Thesis__Final.pdf`](./Honours_Thesis__Final.pdf) | Complete 45-page final thesis detailing the theoretical physics foundations, vector calculus on cortical surfaces (CIFTI/GIFTI meshes), phase singularity detection, and predictive spatiotemporal modeling. | ~26.3 MB |
| **Honours Talk** | [`Honours_Talk-Final.pdf`](./Honours_Talk-Final.pdf) | Final 17-slide honours defense presentation containing high-resolution animated figures and dynamic cortical flow field visualizations. Tracked via **Git LFS**. | ~338 MB |

---

> [!IMPORTANT]
> ### 🎬 Viewing Note for the Honours Talk Slides (`Honours_Talk-Final.pdf`)
> The presentation PDF contains high-resolution embedded frame-by-frame animations demonstrating cortical vortex propagation, vector velocity fields, and dynamic phase singularity interactions across time.
>
> **Standard browser-based PDF viewers (e.g., Google Chrome, Microsoft Edge, Safari) do not support embedded PDF animations and may display only static frames.**
> 
> **It is strongly advised to download the file directly and view it using [Adobe Acrobat Reader](https://get.adobe.com/reader/) (or Adobe PDF Reader)** for full animation and multimedia playback.

---

## Cloning the Repository (Git LFS)

Because [`Honours_Talk-Final.pdf`](./Honours_Talk-Final.pdf) is tracked using **Git Large File Storage (Git LFS)**, make sure you have Git LFS installed prior to cloning:

```bash
# 1. Install / initialize Git LFS on your machine (one-time setup)
git lfs install

# 2. Clone the repository
git clone https://github.com/AdamKarvon/Graduate-Research.git
```

If you already cloned without Git LFS, pull the LFS objects with:
```bash
git lfs pull
```

---

## Related Repositories & Resources

- [**BrainVortexToolbox**](https://github.com/AdamKarvon/BrainVortexToolbox): Custom MATLAB pipeline and functions developed for analyzing CIFTI/GIFTI fMRI data to identify and quantify cortical vortices and spiral wave interactions.
- [**Adam Karvon GitHub Profile**](https://github.com/AdamKarvon): Portfolio and research overview.
