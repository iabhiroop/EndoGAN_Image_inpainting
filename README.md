
# EndoGAN Deep Image Inpainting for Endoscopic Image Restoration  

This repository contains the implementation of a deep learning-based image inpainting system for restoring endoscopic images affected by various artifacts. The project leverages transfer learning with the **CSA Inpainting Model** (originally designed for Paris StreetView Dataset) and adapts it to medical imaging tasks using the **EndoCV2020 Dataset**.  

## Overview  
Endoscopic images can be degraded by artifacts such as glare, occlusions, and blurring, which can compromise the accuracy of medical procedures. This project demonstrates how **deep image inpainting** can effectively restore these frames, improving visualization and enabling better decision-making during medical procedures.  

![Example Result]()  


## Requirements  
To replicate this work, the following libraries and tools are required:  
- Python 3.x  
- TensorFlow / PyTorch  
- OpenCV  
- NumPy  
- Matplotlib  

For detailed package versions, refer to `requirements.txt`.  
