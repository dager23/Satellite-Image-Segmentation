# Satellite-Image-Segmentation
Satellite Image Segmentation to Identify Roads using U-Net Model

We test the accuracy and efficiency of Unet model
on the dataset from Deep-Globe-Road-Extraction
Challenge 2018. In disaster zones, especially in 
developing countries, maps and accessibility 
information are crucial for crisis response. DeepGlobe-Road-Extraction Challenge poses the challenge 
of automatically extracting roads and street networks 
from satellite images. Contains RGB colour code 
mappings for different classes in labels. The labels in 
this dataset have 2 classes: 'road' & 'background'
• The training data for Road Challenge contains 
6226 satellite imagery in RGB, size 
1024x1024.
• The imagery has 50cm pixel resolution, 
collected by DigitalGlobe's satellite.
• The dataset contains 1243 validation and 1101 
test images (but no masks).
The proposed model was implemented using Keras
framework and optimized by the Adam optimizer and 
a binary cross-entropy is used as the loss function.

In conclusion, this project successfully 
employed the UNet architecture for road segmentation 
from satellite imagery using the satellite-road-imageextraction dataset. With the proposed methodology, an 
impressive accuracy of 96% was achieved on the test 
set, while the validation accuracy of 95% further 
validated the robustness of the proposed method. The 
results obtained demonstrate the efficacy of the 
proposed UNet architecture for road segmentation from 
satellite imagery, which can be applied in various 
domains, including urban planning, transportation, and 
disaster management. Overall, this research provides 
valuable insights into the development of accurate and 
efficient road segmentation models for satellite 
imagery, which can contribute to the advancement of 
various fields of research and applications
