# README Art Recognition Raphael Training Dataset 

## Overview

This repository contains the link to the Raphael dataset. The dataset consists of two sets of data used for the authentication analysis of artworks attributed to Raphael. It includes folders of authentic and not authentic images, along with their corresponding documentation.
The dataset can be downloaded at the following link:
[Raphael Dataset](https://drive.google.com/drive/folders/1uyQqBPAsY0jRj_rm0IH4c74taihR-Ywh?usp=share_link)

## Contents

- Authentic Images (Folder: Raphael authentic_images). This folder contains verified authentic images by Raphael. These images have been carefully selected to ensure they represent genuine works by the artist, excluding murals and controversial pieces. Accompanying the images is the Excel file 'Raphael authentic.xlsx' detailing the information available for each artwork, including catalogue raisonné numbers from Dussler and Meyer.

- Contrast Images (Folder: Raphael authentic_images). This folder includes images of non-authentic examples, categorized into three groups: followers, imitations and synthetic, whereby the synthetic images have been created with Stable Diffusion. Accompanying the images is the Excel file 'Raphael contrast.xlsx' with the corresponding details.
  
The contrast set is intentionally larger to envelope the authentic images during training, thus creating a clear boundary in the latent space between authentic and non-authentic images. By applying lower sample weights to the contrast images, we maintain an equal representation between authentic and contrast sets. 

## Usage 

We kindly request that users credit Art Recognition when utilizing this dataset in research, publications, or other projects. For any inquiries or further information, please contact us at contact@art-recognition.com.

Thank you for respecting the integrity and purpose of this dataset.




