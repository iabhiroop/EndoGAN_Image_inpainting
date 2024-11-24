
# EndoGAN Deep Image Inpainting for Endoscopic Image Restoration  

This repository contains the implementation of a deep learning-based image inpainting system for restoring endoscopic images affected by various artifacts. The **CSA Inpainting Model** model is trained on the Paris StreetView Dataset and then finetuned with the **EndoCV2020 Dataset** to medical imaging tasks.  

## Overview  
Endoscopic images can be degraded by artifacts which can compromise the accuracy of medical procedures. **Image inpainting** can effectively restore these frames, improving visualization and enabling better decision-making during medical procedures.  

![Example Result](test_images_after_fine_tuning_with_endoscopy_images/Epoch_(1)_(1of99).jpg)  


## Requirements  
To replicate this work, the following libraries and tools are required:  
- Python 3.x  
- TensorFlow / PyTorch  
- OpenCV  
- NumPy  
- Matplotlib  

For detailed package versions, refer to `requirements.txt`.  
