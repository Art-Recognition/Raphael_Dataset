# README Art Recognition Raphael Training Dataset 

## Overview

This repository contains the link to the Raphael dataset, which consists of two sets of data (‘authentic’ and ‘not authentic’) used for the authentication analysis of artworks attributed to Raphael. Each dataset comprises the image folders, along with their corresponding documentation.
The dataset can be downloaded by accessing the following link:
[Raphael Dataset](https://forms.gle/5nsxXm5LhLV1ndBX8)

## Contents

- Authentic Images (Folder: Raphael authentic_images). This folder contains verified authentic images by Raphael. These images have been carefully selected to ensure they represent genuine works by the artist, excluding murals and controversial pieces.
- Accompanying the authentic images is the Excel file ‘Raphael authentic.xlsx’ detailing the information available for each artwork, including catalogue raisonné numbers from Dussler and Meyer.
- Contrast Images (Folder: Raphael contrast_images). This folder includes images of non-authentic examples, categorized into three groups: followers, imitations and synthetic, whereby the synthetic images have been created with Stable Diffusion. The contrast set is intentionally larger to envelop the authentic images during training, thus creating a clear boundary in the latent space between authentic and non-authentic images. By applying lower sample weights to the contrast images, we maintain an equal representation between authentic and contrast sets.
- Accompanying the contrast images is the Excel file ‘Raphael contrast.xlsx’, which contains the available information on the included artworks.
- The document ‘Genre split Raphael.xlsx’ provides a breakdown of the percentages of different genres found in Raphael’s works (Portraits, Madonnas, Religious scenes/Allegories) within both the authentic and contrast sets.

## Updates

28-01-2026

Two images have been removed from the authentic dataset following a reassessment based on the information reported in the catalogue by Jürg Meyer zur Capellen (Raphael: A Critical Catalogue of His Paintings, Landshut: Arcos, 2001). The removal was motivated by issues related to preservation, restoration history, and/or the current status of the artworks, which could introduce ambiguities for training and analysis purposes.

- **Raphael_authentic_image_88.jpg**  
  *Title: Portrait of a Lady with a Unicorn*  
  From the catalogue Jürg Meyer zur Capellen, *Raphael : a critical catalogue of his paintings*, Landshut : Arcos, 2001. Vol. 1, p. 290.  
  > “The painting is in a very critical state of preservation. In the late seventeenth century, the composition was overpainted, hiding the unicorn and supplying the lady with a robe and the attribute of St Catherine of Alexandria, a wheel. In 1936, it was decided to under-take extensive restoration work, which involved removing later additions and transferring the body of the work from wood to canvas. The procedure had a deleterious effect on the picture's condition. A second attempt in 1959-60 was designed to repair the damage and stabilize the body of the painting. Infra-red photographs made at the time revealed the earlier figure of a dog beneath the unicorn. It also appears that the woman's face was altered during the final execution.”

- **Raphael_authentic_image_78.jpg**  
  *Title: Portrait of a Young Man*  
  From the catalogue Jürg Meyer zur Capellen, *Raphael : a critical catalogue of his paintings*, Landshut : Arcos, 2001. Vol. 3, pp. 94–99.  
  > “A photograph of the picture taken by the museum [in black and white] shows the complete right hand, which is cropped in the old colour photograph. (Note 17: It is not possible, however, to be completely sure about the condition in the photograph.) […] In World War II, Germans seized the picture and Gauleiter Hans Frank exhibited it in the rooms he had confiscated in the Wawel in Crakow. As the war was ending, the traces of the Portrait of a Young Man got lost, so that it remains unclear whether it was destroyed or removed illegally and is possibly still in the possession of some unknown person.”

## Usage 

We kindly request that users credit Art Recognition when utilizing this dataset in research, publications, or other projects. For any inquiries or further information, please contact us at contact@art-recognition.com.

Thank you for respecting the integrity and purpose of this dataset.




