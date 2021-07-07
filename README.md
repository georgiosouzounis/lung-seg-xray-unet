# Lung segmentation from thoracic X-Ray images using UNET


<img src="https://raw.githubusercontent.com/georgiosouzounis/lung-seg-xray-unet/main/images/title.jpg" width = "600"/>


## Overview

This Google Colab [notebook](https://github.com/georgiosouzounis/lung-seg-xray-unet/blob/main/lung_seg_xray_unet.ipynb) demonstrates the use of the UNET architecture in training a custom model to detect and segment lungs from thoracic X-Ray images. Model training is stretched to 5 epochs only, at the end of which the model reports: ***loss:*** 5.29% and **accuracy:** 98.05%

## Acknowledgements

The author would like to thank and acknowledge the following:

- [Divan Gupta](https://github.com/divamgupta) and all other contributors to the [Image Segmentation Keras : Implementation of Segnet, FCN, UNet, PSPNet and other models in Keras](https://github.com/divamgupta/image-segmentation-keras) repo for their amazing work in putting all the functionality together to make semantic segmentation accessible through Keras.
- [Nikhil Pandey](https://www.kaggle.com/nikhilpandey360) for posting an excellent quality [X-Ray dataset of thoracic scans](https://www.kaggle.com/nikhilpandey360/chest-xray-masks-and-labels) in Kaggle.


## Disclaimer

In the following, "author" refers to Georgios Ouzounis.

- The work presented in this notebook is independent from past works of the author at varius companies and institutions. It differs with regards to the technology and code being used and does not relate to any prior products, research work or IP developed by the author.
- This notebook (code) is developed explicitly for educational purposes, demonstrating how one can train the UNET model. It is not meant for any other usage and the author has no responsibility of its outcome and deliverables, if used for a purpose different from the one stated.

## License

Plrease refer to [LICENSE](https://github.com/georgiosouzounis/lung-seg-xray-unet/blob/main/LICENSE)
