# Analog Clock Time Recognition (PyTorch CNN)

## Project Overview
This project aims to recognize time on analog clock faces using deep learning. The model classifies clock images into **144 distinct classes**, representing time intervals of 5 minutes across a 12-hours.

The dataset consists of high-quality clock renders generated in **Blender** by a team member. This synthetic data provides perfect alignment and precise labeling, which is crucial for fine-grained time estimation.

## Architecture
The implementation uses a custom Convolutional Neural Network (CNN) built with **PyTorch**.

## Dataset
- **Source:** Synthetic renders from Blender.
- **Input Size:** 128x128 pixels (RGB).

## Authors
- Jan Pazdan - clock's renders, model implementation
- Jakub Jucha - model implementation
