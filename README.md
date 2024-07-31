# Computer-Vision

Kornia:

https://github.com/kornia/kornia

Segmentation Models:

https://segmentation-models-pytorch.readthedocs.io/en/latest/models.html

https://github.com/jlcsilva/segmentation_models.pytorch/blob/master/examples/cars%20segmentation%20(camvid).ipynb

ResUnet++ is a fully convolution neural network for image semantic segmentation. Consist of encoder and decoder parts connected with skip connections. The encoder extracts features of different spatial resolution (skip connections) which are used by decoder to define accurate segmentation mask.

Applies attention to the skip connection feature maps, based on themselves and the decoder feature maps. The skip connection feature maps are then fused with the decoder feature maps through concatenation. Uses an Atrous Spatial Pyramid Pooling (ASPP) bridge module and residual connections inside each decoder blocks.
