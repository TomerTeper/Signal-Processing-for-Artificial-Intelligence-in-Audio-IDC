# Homework 4: Music Style Transfer with GAN and Pix2Pix

## Overview
This assignment explores the use of a **Generative Adversarial Network (GAN)** in a **pix2pix** architecture to perform **style transfer** on musical pieces. The task focuses on preserving the harmonic structure of a song (via chroma features) while generating a complementary musical texture (distribution of notes).

By extracting chroma representations from **MIDI files**, the notebook guides you through training a generator model that reconstructs textures from harmonic outlines—similar to how pix2pix reconstructs images from sketches.

## Key Topics Covered
- Music style transfer  
- Chroma features and MIDI data  
- Generative Adversarial Networks (GANs)  
- Pix2Pix architecture  
- Data preprocessing and visualization  
- TensorFlow/Keras implementation of GANs  

## Structure
The notebook includes the following major sections:
1. **Introduction**: Overview of the task and pix2pix analogy.  
2. **Data Processing**: Extraction of chroma and note matrices from MIDI files.  
3. **Model Definition**: Building the generator and discriminator networks.  
4. **Training Loop**: Training the GAN using chroma-texture pairs.  
5. **Evaluation**: Visualizing and interpreting generated musical textures.  

## Requirements
- Python 3.x  
- TensorFlow (>=2.x)  
- Pretty_MIDI  
- Numpy  
- Matplotlib  
