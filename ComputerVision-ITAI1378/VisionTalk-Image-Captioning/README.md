🎯 VisionTalk – Image Captioning System

VisionTalk is a small AI system that generates natural-language captions from images using a pretrained BLIP Vision–Language Model. It demonstrates how computer vision and language models can work together to interpret and describe visual content.

1. Problem Statement

The goal of this project is to create a system that:

Takes an input image

Understands key visual features

Produces a descriptive caption

This project applies the main concepts learned in ITAI 1378, including image processing, neural networks, transformers, and multimodal AI.

2. Approach

The notebook uses a pretrained BLIP model from Hugging Face.
The pipeline:

Load the BLIP processor and model

Upload or load an image

Preprocess the image

Run inference to generate a caption

Display the image and its caption

3. Folder Contents
VisionTalk-Image-Captioning/
├── VisionTalk_Image_Captioning.ipynb
├── README.md
└── results/


Notebook – Full code, explanations, and outputs

results/ – Example images and generated captions

4. How to Run
A. Google Colab (easiest)

Open the notebook in Colab

Install dependencies:

!pip install transformers timm pillow accelerate


Upload an image

Run all cells

B. Local Python Environment
pip install transformers timm pillow accelerate
jupyter notebook


Open the notebook and run it.

5. Dataset / Images

No large dataset is required.
This project uses individual test images placed in the notebook or results/ folder.

6. Results

Output examples (image + caption) are stored in the results folder.

7. What I Learned

Through VisionTalk, I practiced:

Running pretrained VLMs

Using Hugging Face models

Connecting visual input to text output

Structuring and documenting an AI mini-project

This project is a key part of my Applied AI portfolio and demonstrates my ability to build practical computer vision systems.
