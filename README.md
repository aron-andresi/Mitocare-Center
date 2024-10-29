# Mitocare-Center
## Overview

To support the microscopic imaging work of our lab, the custom solution 
for mitochondrial imaging will be hosted here. The work mainly impacts 
FIB-SEM related code that helps with mitochondria recognition and masking in 3D 
volumetric data.

<div align="center">
  <img src="https://research.jefferson.edu/content/research/mitochrondrial-imaging-diagnostics-center/jcr%3acontent/root/article/responsivegrid/text_and_image/image.img.jpg/1714670218945.jpg" alt="Mitochondrial Imaging">
</div>

## About us
At the Center (referred to as MitoCare Center), our team pairs advanced, 
high-resolution 3D imaging modalities in vitro and invivo with other 
cutting-edge technologies to study mitochondrial health and disease 
pathogenesis, diagnostics, and potential therapeutic targets.

Our Mission is to innovate, create, and use advanced technologies in a
programmatic context to study mitochondria in health and disease.

Website: [Mitochondrial Imaging Diagnostics Center](https://research.jefferson.edu/mitochrondrial-imaging-diagnostics-center.html)

## Devlopment

1. Clone the repository:
    ```bash
    git clone https://github.com/aron-andresi/Mitocare-Center.git
    ```
2. Install Conda and CUDA 12.3.
3. Create the Conda environments:
    ```bash
    conda env create --file cupy123.yml
    conda env create --file monai.yml
    ```
4. Launch Visual Studio Code with the repository as the working directory. Use the `monai` environment for deep learning and prediction-related work, and for everything else, use `cupy123`.
