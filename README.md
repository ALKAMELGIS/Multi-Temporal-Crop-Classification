Training dataset

IBM/NASA Geospatial – Multi-Temporal Crop Classification

Hugging Face Dataset — multi-temporal-crop-classification

It was created using:

HLS (Harmonized Landsat and Sentinel-2) imagery
USDA Crop Data Layer (CDL) for the labels
3 temporal observations
6 bands per observation → 18 bands total
224 × 224 pixel chips
13 land-cover/crop classes

The original dataset-generation pipeline is also available here:

Training-data generation GitHub repository

And the fine-tuning code/configuration is here:

NASA-IMPACT HLS Foundation Model GitHub

Important distinction

The Hugging Face Space/demo you shared is not the training dataset. It is the demo for running the already fine-tuned model.

So for your project, you can cite:

Dataset: IBM/NASA Geospatial, Multi-Temporal Crop Classification Dataset
Imagery: NASA HLS
Labels: USDA CDL
Model: Prithvi-100M Multi-Temporal Crop Classification. Discrpations
