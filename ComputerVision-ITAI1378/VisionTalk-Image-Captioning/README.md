🖼️ VisionTalk – Image Captioning System

VisionTalk is an AI system that generates natural-language captions from input images using a pretrained BLIP Vision–Language Model. It demonstrates how AI can interpret visual content and produce meaningful descriptions.

1. Problem Statement

The goal of this project is to build a system that:

Accepts an input image

Extracts and understands key visual features

Generates a descriptive caption

This project applies core concepts from ITAI 1378 – Computer Vision, including neural networks, transfer learning, and vision–language modeling.

2. Approach

The project uses a pretrained BLIP model from Hugging Face.
The processing pipeline includes:

Load the BLIP processor and model

Upload an image

Preprocess the image

Generate a caption

Display the image + caption

Notebook Location

📌 The main notebook for this project is stored in:

../notebooks/VisionTalk_Image_Captioning.ipynb


This keeps the portfolio clean and organized.

3. Folder Contents
VisionTalk-Image-Captioning/
├── README.md               ← This file  
└── results/                ← Output examples

Contents:

results/ — Saved sample captions & any generated images

Notebook is stored separately in /notebooks for better organization

4. How to Run the Project
A. Run in Google Colab (recommended)

Open the notebook in Colab

Install dependencies:

!pip install transformers timm pillow accelerate


Upload an image

Run all cells

The system will display the image + generated caption

B. Run Locally (Python environment)

Install dependencies:

pip install transformers timm pillow accelerate


Launch Jupyter Notebook:

jupyter notebook


Open:
VisionTalk_Image_Captioning.ipynb

5. Dataset / Images

No dataset is required.

The user uploads a single test image, which the model processes.
Example images and output captions are stored inside the results/ folder.

6. Results

Sample outputs include:

Generated captions

Displayed images

Notes & observations

These are available in the results/ directory.

7. What I Learned

From building VisionTalk, I learned to:

Use pretrained Vision–Language Models

Apply Hugging Face tools

Understand how images are encoded for language generation

Build a mini end-to-end computer vision application

Document and organize AI projects professionally

This project demonstrates my ability to create real-world AI applications for my Applied AI portfolio.
