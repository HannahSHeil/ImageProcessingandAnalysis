# Image Processing and Analysis

**Teaching Material and Resources for an Image Processing and Analysis Lecture**
---
Hannah S. Heil, Lund University, November 2025


## 📚 Overview

This repository contains teaching materials, exercises, and resources for an **Image Processing and Analysis** lecture. It is intended for students, instructors, and researchers who want to learn or teach practical image analysis techniques, including segmentation, tracking, and quantification.

The repository includes:

- **Jupyter/Colab notebooks** with hands-on tutorials  
- **Supplementary resources** (datasets, references, and reading material)

---

## 🚀 Getting Started with the excercise

### 1. Open a Notebook in Google Colab

Click the **“Open in Colab”** badge or open directly via Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HannahSHeil/ImageProcessingandAnalysis/blob/main/notebooks/CellSegmentation_Exercise.ipynb)

> Students should **make a copy** of the notebook in their own Google Drive to run and modify it independently.


## 💡 Tips for Students

Always work on your own copy of a notebook.

Explore the example images before modifying the analysis.

Read comments and markdown cells carefully—they contain explanations and hints.

Ask questions or report issues via the GitHub Issues tab.


---

## Image Analysis Resources

### 1. Learning & Community Platforms

| Tool | Description | Link |
|------|-------------|------|
| **NEUBIAS** | European network for bioimage analysis, offering courses, workshops, and tutorials. | [NEUBIAS](https://www.neubias.org/), [NEUBIAS Training](https://neubias.github.io/training-resources/) |
| **Euro-BioImaging** | European infrastructure providing access to imaging technologies and training. | [Euro-BioImaging](https://www.eurobioimaging.eu/) |
| **Image.sc** | Forum for image analysis discussion, plugin support, and community help. | [Image.sc](https://forum.image.sc/) |
| **Bio-image Analysis Notebooks** |Collection of python notebooks for image processing and analysis. | [Link](https://haesleinhuepf.github.io/BioImageAnalysisNotebooks/intro.html) |

### 2. Software & Tools

| Tool | Description | Link |
|------|-------------|------|
| **Fiji** | Open-source image processing package with extensive plugins for microscopy and bioimage analysis. | [Fiji](https://fiji.sc/) |
| **BioVoxxel Toolbox** | Collection of ImageJ/Fiji plugins for advanced image processing tasks. | [BioVoxxel Toolbox](https://imagej.net/plugins/biovoxxel-toolbox) |
| **Napari** | Python-based interactive multi-dimensional image viewer with plugin support. | [Napari](https://napari.org/) |
| **Google Colab** | Cloud-based Jupyter notebook environment for running Python code and image analysis workflows. | [Colab](https://colab.research.google.com/) |


### 3. AI / Deep Learning Resources

| Tool | Description | Link |
|------|-------------|------|
| **ZeroCostDL4Mic** | Framework for running deep learning models for microscopy on cloud platforms with minimal setup. | [ZeroCostDL4Mic](https://github.com/HenriquesLab/ZeroCostDL4Mic) |
| **BioImage Model Zoo** | Repository of pre-trained deep learning models for microscopy image analysis. | [bioimage.io](https://bioimage.io/) |
| **DeepImageJ** | Integrates deep learning models into Fiji/ImageJ for microscopy analysis. | [DeepImageJ](https://deepimagej.github.io/) |


### 4. Utility Tools

| Tool | Description | Link |
|------|-------------|------|
| **Nyquist Calculator** | Tool for calculating Nyquist sampling rates to ensure proper image resolution. | [Nyquist Calculator](https://imagej.net/plugins/nyquist-calculator) |


# References for Bioimage Analysis
*A curated and annotated list of key literature, tools, and resources.*

---

## 📚 Alphabetized References with Clickable DOI Links

**Abbe, E.** (1873). *Beiträge zur Theorie des Mikroskops und der mikroskopischen Wahrnehmung.* Archiv für Mikroskopische Anatomie, 9, 413–418.  
**➜** Classical optics; diffraction limit; foundations of microscopy

**Appeltshauser, L., Linke, J., Heil, H. S., Karus, C., Schenk, J., Hemmen, K., Sommer, C., Doppler, K., & Heinze, K. G.** (2023). *Super-resolution imaging pinpoints the periodic ultrastructure at the human node of Ranvier and its disruption in patients with polyneuropathy.* Neurobiology of Disease, 182, 106139. [https://doi.org/10.1016/j.nbd.2023.106139](https://doi.org/10.1016/j.nbd.2023.106139)  
**➜** Super-resolution microscopy; neurobiology application

**Archit, A., Freckmann, L., Nair, S. et al.** (2025). *Segment Anything for Microscopy.* Nature Methods, 22, 579–591. [https://doi.org/10.1038/s41592-024-02580-4](https://doi.org/10.1038/s41592-024-02580-4)  
**➜** Foundation models; segmentation; SAM adaptation for microscopy

**Brocher, J.** (2025). *BioVoxxel 3D Box (bv3dbox).* Zenodo. [https://doi.org/10.5281/ZENODO.17702242](https://doi.org/10.5281/ZENODO.17702242)  
**➜** 3D image analysis; Fiji plugin

**Hinderling, L., Heil, H. S., Rates, A., et al.** (2025). *Smart Microscopy: Current Implementations and a Roadmap for Interoperability.* [https://doi.org/10.1101/2025.08.18.670881](https://doi.org/10.1101/2025.08.18.670881)  
**➜** Smart microscopy; automation; hardware–software integration

**Laine, R. F., Arganda-Carreras, I., Henriques, R., & Jacquemet, G.** (2021). *Avoiding a replication crisis in deep-learning-based bioimage analysis.* Nature Methods, 18(10), 1136–1144. [https://doi.org/10.1038/s41592-021-01284-3](https://doi.org/10.1038/s41592-021-01284-3)  
**➜** Reproducibility; deep learning best practices

**Laine, R. F., Heil, H. S., Coelho, S., Nixon-Abell, J., Jimenez, A., Wiesner, T., … Henriques, R.** (2023). *High-fidelity 3D live-cell nanoscopy through data-driven enhanced super-resolution radial fluctuation.* Nature Methods, 20(12), 1949–1956. [https://doi.org/10.1038/s41592-023-02057-w](https://doi.org/10.1038/s41592-023-02057-w)  
**➜** Live-cell nanoscopy; data-driven SRRF; computational super-resolution

**napari contributors.** (2019). *napari: a multi-dimensional image viewer for Python.* [https://doi.org/10.5281/zenodo.3555620](https://doi.org/10.5281/zenodo.3555620)  
**➜** Visualization; Python viewer; plugin ecosystem

**Ouyang, W., Beuttenmueller, F., Gómez-de-Mariscal, E., et al.** (2022). *BioImage Model Zoo: A Community-Driven Resource for Accessible Deep Learning in BioImage Analysis.* bioRxiv. [https://doi.org/10.1101/2022.06.07.495102](https://doi.org/10.1101/2022.06.07.495102)  
**➜** Deep learning model repository; model standardization

**Royer, L. A.** (2024). *Omega — harnessing the power of large language models for bioimage analysis.* Nature Methods, 21, 1371–1373. [https://doi.org/10.1038/s41592-024-02310-w](https://doi.org/10.1038/s41592-024-02310-w)  
**➜** LLMs for bioimage analysis; multimodal workflows

**Uchida, S.** (2013). *Image processing and recognition for biological images.* Development, Growth & Differentiation, 55, 523–549. [https://doi.org/10.1111/dgd.12054](https://doi.org/10.1111/dgd.12054)  
**➜** Classical image processing; feature extraction; pattern recognition

**von Chamier, L., Laine, R. F., & Henriques, R.** (2019). *Artificial intelligence for microscopy: what you should know.* Biochemical Society Transactions, 47(4), 1029–1040. [https://doi.org/10.1042/BST20180391](https://doi.org/10.1042/BST20180391)  
**➜** Introductory review of AI for microscopy

**von Chamier, L., Laine, R. F., Jukkala, J., Spahn, C., Krentzel, D., … Henriques, R.** (2021). *Democratising deep learning for microscopy with ZeroCostDL4Mic.* Nature Communications, 12(1), 2276. [https://doi.org/10.1038/s41467-021-22518-0](https://doi.org/10.1038/s41467-021-22518-0)  
**➜** Accessible DL training; Google Colab workflows



⚖️ License

This repository is shared for educational purposes. See LICENSE for details.
