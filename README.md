# Computer Vision Lab

Computer vision projects developed in the context of WorldQuant University's
Applied AI Lab: Deep Learning for Computer Vision. Each project has its own
repository containing code, dependencies, data references, and usage instructions.

## Projects

### 1. Wildlife Conservation in Côte d'Ivoire

Classifies camera-trap images into seven animal groups and an empty-frame class.
Uses a PyTorch CNN, a binary dense baseline, validation loss, and confusion matrices.

[Repository and code](https://github.com/shivanshu-1609/wildlife-preservation)

### 2. Crop Disease Classification in Uganda

Classifies cassava leaf images into four disease categories and a healthy class.
Includes a compact CNN, ResNet50 transfer learning, augmentation, early stopping,
and single-image prediction.

[Repository and code](https://github.com/shivanshu-1609/crop-detection-uganda)

### 3. Traffic Flow Analysis

Detects vehicles in traffic images and video using YOLOv8. Includes annotation
conversion, custom-class training, validation, optional ByteTrack IDs, and CSV exports.

[Repository and code](https://github.com/shivanshu-1609/traffic-flow-analysis)

### 4. Celebrity Sightings in India

Detects faces with MTCNN and compares InceptionResnetV1 embeddings against an
enrolled reference gallery. Includes annotated image output and a Flask upload API.

[Repository and code](https://github.com/shivanshu-1609/celebrity-sightings-india)

### 5. Medical Image Generation in Spain

Generates synthetic grayscale images using a vanilla GAN or published MediGAN
models. Includes training, image sampling, and a Streamlit interface. Outputs are
educational and are not clinically validated.

[Repository and code](https://github.com/shivanshu-1609/medical-image-generation)

### 6. Social Media Marketing in the United States

Creates images from text prompts using Stable Diffusion and adds captions with
Pillow. Includes a Streamlit app, styles, seed controls, optional compatible LoRA
loading, and downloadable images.

[Repository and code](https://github.com/shivanshu-1609/social-media-image-generation)

## Setup and attribution

Use each project's README and requirements in a separate Python 3.11 environment.
Datasets, downloaded weights, and generated outputs are excluded from the code
repositories. Evaluation details and recorded course results are documented
within each project.

[WorldQuant University](https://www.wqu.edu/) provided the original course material.
Original course files, datasets, and pretrained models retain their own licenses;
the standalone scripts have the licenses stated in their project repositories.
