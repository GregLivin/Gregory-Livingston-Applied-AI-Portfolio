# 🎯 VisionTalk – Image Captioning System

VisionTalk is an AI system that generates natural-language captions from images using a pretrained **BLIP Vision–Language Model**. It demonstrates how computer vision and language models work together to interpret and describe visual content.

---

## 1. Problem Statement

The goal of this project is to build a system that:

- Takes an input image  
- Understands key visual features  
- Produces a descriptive caption  

This project applies core concepts from ITAI 1378, including image processing, neural networks, and multimodal AI.

---

## 2. Approach

The notebook uses a pretrained **BLIP** model from Hugging Face.

The pipeline:

1. Load the BLIP processor and model  
2. Upload or load an image  
3. Preprocess the image  
4. Generate a caption  
5. Display the image and caption  

---

## 3. Folder Contents

```text
VisionTalk-Image-Captioning/
├── VisionTalk_Image_Captioning.ipynb
├── README.md
└── results/
Notebook – All code and explanations

results/ – Example images and captions

4. How to Run
A. Google Colab (recommended)
Open the notebook in Google Colab

Install dependencies:

python
Copy code
!pip install transformers timm pillow accelerate
Upload an image

Run all cells

B. Local Python Environment
bash
Copy code
pip install transformers timm pillow accelerate
jupyter notebook
Open the notebook and run it.

5. Dataset / Images
No large dataset is required.
The system uses individual test images included in the notebook or saved in the results/ folder.

6. Results
Example outputs (images with captions) are stored inside the results folder.

7. What I Learned
Through VisionTalk, I practiced:

Using pretrained Vision–Language Models

Applying Hugging Face tools

Connecting images to natural-language generation

Documenting and organizing an AI mini-project

This project demonstrates my ability to build practical computer vision systems for my Applied AI portfolio.
