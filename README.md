# unet_from_scratch
Implementaion of U-Net architecture for Semantic Segmentation

Semantic Segmentaion : Consider an image and make a bounding box around each object, this will be Object Detection.
                       If we paint the pixel around every obejct, it is semantic segmentation where every pixel represents either an object or non-object/background, UNET is designed to do this.
                       One step further is Instance Segmentaion.

![GitHub Logo](images/1.png)

Link to Original Paper : https://arxiv.org/abs/1505.04597 : Authors came up with this for Biomedical Image Segmentaion.

![GitHub Logo](images/2.png)

Part on Left is Encoder(Downsampling) and Right Part is Decoder(Upsampling) and Concatenation of feature maps or right and left is responsible for localization information (Bottom Part)