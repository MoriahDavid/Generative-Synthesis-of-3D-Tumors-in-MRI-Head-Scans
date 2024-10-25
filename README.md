# Generative Creation of Synthetic 3D Tumors in MRI Head Scans
Our Final Project.

In this repository:
1. Project Book
2. Link to Colab Notebooks

Project Explanation:

This project aims to improve brain tumor detection models by expanding MRI datasets with synthetic 3D tumors. By embedding synthetic tumors in healthy MRI scans, this approach creates diverse data for training AI models, especially for identifying small and subtle tumors that are often missed during manual diagnosis.

Key Steps:
1. **Locating Tumor Position**: We selected specific areas within the brain MRI scans for inserting synthetic tumors.
2. **Creating Synthetic Tumors**: Using a geometric approach, we generated realistic 3D tumors with adjustable shapes and sizes.
3. **Embedding Tumors**: These synthetic tumors were blended into the MRI scans for natural appearance.
4. **Generating Slices**: We created 2D slices from various angles to ensure diverse training data.

Using the DenseNet model, we evaluated the effect of adding synthetic tumors on model accuracy, which showed an improvement in detecting tumors across different scans.

This project enhances the ability of AI-driven diagnostics to support early and accurate tumor detection, aiming to benefit patient outcomes and assist medical professionals in healthcare. 


<img src="https://github.com/user-attachments/assets/a975812d-6612-4837-80b8-ced72329551f" width="500">

