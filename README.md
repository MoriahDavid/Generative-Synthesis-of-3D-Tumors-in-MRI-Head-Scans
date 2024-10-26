# Generative Creation of Synthetic 3D Tumors in MRI Head Scans 🧠🧬✨
Our Final Project.<br />

### In this repository:
1. **Project Book**
2. **Link to Colab Notebooks**<br />
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MoriahDavid/Synthetic-3D-Tumors/blob/main/BrainSegmentation.ipynb) Brain Segmentation.<br />
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MoriahDavid/Synthetic-3D-Tumors/blob/main/Synthetic3DTumors.ipynb) Generate Synthetic Tumors- Full Process.<br />
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MoriahDavid/Synthetic-3D-Tumors/blob/main/BrainTumorDetection.ipynb) Dataset Validation with DenseNet model.<br />


### Project Explanation:

This project aims to improve brain tumor detection models by expanding MRI datasets with synthetic 3D tumors. By embedding synthetic tumors in healthy MRI scans, this approach creates diverse data for training AI models, especially for identifying small and subtle tumors that are often missed during manual diagnosis.

Key Steps:
1. **Brain Segmentation and Tumor Positioning**: Using brain segmentation tools, we isolated the brain from each MRI scan and identified specific areas within it for tumor insertion, ensuring precise placement within the 3D brain structure.
2. **Creating Synthetic Tumors**: Using a geometric approach, we generated realistic 3D tumors with adjustable shapes and sizes.
3. **Embedding Tumors**: These synthetic tumors were blended into the MRI scans for natural appearance.
4. **Generating Slices**: We created 2D slices from various angles to ensure diverse training data.

Using the DenseNet model, we evaluated the effect of adding synthetic tumors on model accuracy, which showed an improvement in detecting tumors across different scans.

This project enhances the ability of AI-driven diagnostics to support early and accurate tumor detection, aiming to benefit patient outcomes and assist medical professionals in healthcare. 


<img src="https://github.com/user-attachments/assets/a975812d-6612-4837-80b8-ced72329551f" width="500">

