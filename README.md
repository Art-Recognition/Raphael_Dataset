# README Art Recognition Raphael Training Dataset 

## Overview

This repository contains the link to the Raphael dataset, which consists of two sets of data (‘authentic’ and ‘not authentic’) used for the authentication analysis of artworks attributed to Raphael. Each dataset comprises the image folders, along with their corresponding documentation.
The dataset can be downloaded by accessing the following link:
[Raphael Dataset](https://drive.google.com/drive/folders/1uyQqBPAsY0jRj_rm0IH4c74taihR-Ywh?usp=share_link)

## Contents

- Authentic Images (Folder: Raphael authentic_images). This folder contains verified authentic images by Raphael. These images have been carefully selected to ensure they represent genuine works by the artist, excluding murals and controversial pieces.
- Accompanying the authentic images is the Excel file ‘Raphael authentic.xlsx’ detailing the information available for each artwork, including catalogue raisonné numbers from Dussler and Meyer.
- Contrast Images (Folder: Raphael contrast_images). This folder includes images of non-authentic examples, categorized into three groups: followers, imitations and synthetic, whereby the synthetic images have been created with Stable Diffusion. The contrast set is intentionally larger to envelope the authentic images during training, thus creating a clear boundary in the latent space between authentic and non-authentic images. By applying lower sample weights to the contrast images, we maintain an equal representation between authentic and contrast sets.
- Accompanying the contrast images is the Excel file ‘Raphael contrast.xlsx’, which contains the available information on the included artworks.
- The document ‘Genre split Raphael.xlsx’ provides a breakdown of the percentages of different genres found in Raphael’s works (Portraits, Madonnas, Religious scenes/Allegories) within both the authentic and contrast sets.

## Usage 

We kindly request that users credit Art Recognition when utilizing this dataset in research, publications, or other projects. For any inquiries or further information, please contact us at contact@art-recognition.com.

Thank you for respecting the integrity and purpose of this dataset.




