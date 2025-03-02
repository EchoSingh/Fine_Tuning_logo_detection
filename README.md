# Fake Brand Logo Detector

## Overview

The **Fake Brand Logo Detector** is a deep learning-based tool that helps identify whether a brand logo is real or fake. The model classifies brand logos using a ResNet-18 architecture that has been fine-tuned for detecting logo authenticity. The project includes:

- A dataset of real and fake brand logos downloaded from Bing.
- A pre-trained ResNet-18 model for image classification.
- A Gradio interface for easy image upload and classification.

## Features

- **Image Downloading**: Automatically fetches brand logos using Bing Image Downloader for both real and fake logos.
- **Model**: Uses a fine-tuned ResNet-18 model to classify logos as either "Real" or "Fake".
- **Interface**: Provides a simple, user-friendly interface with Gradio to upload images and receive predictions.
  
## Requirements

To run this project locally, you will need the following Python packages:

- `torch`
- `torchvision`
- `gradio`
- `bing-image-downloader`
- `Pillow`

You can install the required libraries using `pip`:

```bash
pip install torch torchvision gradio bing-image-downloader Pillow
```

## Usage
Download Logos: Run the script to download real and fake brand logos. This will populate the dataset_main folder with the logos.

Train the Model: Train the ResNet-18 model on the dataset of real and fake logos.

Run the Gradio Interface: After training, use the following script to launch the Gradio interface where you can upload an image of a brand logo for prediction.


## License
This project is licensed under the MIT License - see the LICENSE file for details.
