# NeuroCaption: Image Captioning with Deep Learning

NeuroCaption provides a comprehensive toolkit for training and deploying deep learning models tailored for the image captioning task on the Flickr8k dataset.

![Project Idea]([path_to_idea_image.png](https://github.com/anirudhsinghdahiya/NeuroCaption/blob/main/NeuroCaption_idea.png))

## Overview

The project offers a streamlined pipeline from loading and preprocessing data from the Flickr8k dataset to training a model and then utilizing that model to caption new unseen images.

## Features

- Customizable data loader tailored for the Flickr8k dataset.
- Encoder-Decoder architecture combining CNNs and RNNs for the captioning task.
- Utility scripts for easy saving and loading of model checkpoints.
- Integration with TensorBoard for training insights.

## Getting Started

### Prerequisites

- Python 3.x
- PyTorch and torchvision
- Pandas
- Spacy (with `en_core_web_sm` model)
- TensorBoard

### Installation

1. Clone the repository:
git clone https://github.com/your_username/NeuroCaption.git
cd NeuroCaption

2. Install required packages:
pip install -r requirements.txt

3. Download the Flickr8k dataset and arrange it in the directory as mentioned in the `get_loader.py` script.

## Usage

1. To train the model, simply run:
python train.py

vbnet
Copy code

2. If you want to infer using a pre-trained model, ensure you've loaded the model and then use appropriate methods for inference.

## Results

After training for several epochs on the Flickr8k dataset, our model was able to produce remarkable captions for various images. Here's an example result:

![Result Image](path_to_result_image.png)

## Contributing

If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.
