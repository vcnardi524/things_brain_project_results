# Things Brain Project Results
## UCSB Dynamo Undergrads

Contributors: 
- @vcnardi524
- Eirini Schoinas
- Emily Hu
- Julia Novick


Our project was to generate images from a subject’s fMRI that corresponded with the image the subject was viewing when the fMRI was taken. We used the THINGS dataset for this project.

The architectures we used were LDMs, MLPs, and convulational auto-encoders.

This repo contains two sets of images. One image contains reconstructions made from fMRI scans; call this image RI. The other contains the ground truth image; call this image GTI. Note that index RI_ij corresponds with index GTI_ij. That is, the reconstructed image found in image RI at index ij corresponds to the reconstruction of the image in GTI at index ij. 

| RI | GTI |
|----|-----|
| ![](images/RI1.png) | ![](images/GTI1.png) |
| ![](images/RI2.png) | ![](images/GTI2.png) |
| ![](images/RI3.png) | ![](images/GTI3.png) |
| ![](images/RI4.png) | ![](images/GTI4.png) |


Hebart, Martin; Contier, Oliver; Teichmann, Lina; Rockter, Adam; Zheng, Charles; Kidder, Alexis; et al. (2023). THINGS-data: A multimodal collection of large-scale datasets for investigating object representations in brain and behavior. Figshare+. Collection. https://doi.org/10.25452/figshare.plus.c.6161151
