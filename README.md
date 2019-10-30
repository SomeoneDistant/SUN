# Self Using Note
**Some Useful Niubi** tricks, repositories and paper. Just use Ctrl+F and input key words to search what you what. ~~Strikethrough~~ means I have not gone through it.

## General Structure
[High Resolution Net(HRNet)](https://arxiv.org/abs/1904.04514): UNet with convolution in skip connection.

[DANet](https://arxiv.org/abs/1809.02983): Dual self attention module, great example of [pytorch sync-batch-norm and attention module](https://github.com/junfu1115/DANet).

## Detection
[Uncertainty bounding box](https://arxiv.org/abs/1809.08545)

## Face Recognition
~~[Deep Comparator Network](https://arxiv.org/abs/1807.11440)~~

## Image Synthesis
[Few shot unsupervised image2image](https://arxiv.org/abs/1905.01723): Content module,

[Pix2PixHD: Segmentation to image](https://arxiv.org/abs/1711.11585): Enhancer structure.

[Semantic Image Synthesis with Spatially-Adaptive Normalization(SPADE)](https://arxiv.org/abs/1903.07291): Used in GauGAN, segmentation to image.

[Face Swapping GAN(FSGAN)](https://arxiv.org/abs/1908.05932): Subject agnostic face swapping and reenactiment model.

[SinGAN](https://arxiv.org/abs/1905.01164): Using multiscale patch generator to learn the distribution of target nature image.(ICCV19 Best Paper)

[AdaIN](https://arxiv.org/abs/1703.06868): Adaptive instance normalization using in style transfer.

~~[Domain Intersection and Domain Difference](https://arxiv.org/abs/1908.11628)~~

[Face swapping GAN](https://github.com/shaoanlu/faceswap-GAN): Introducing self attention, Kalman Filter.

[Few-shot face swapping GAN](https://github.com/shaoanlu/fewshot-face-translation-GAN): Introducing AdaIN, SPADE.

## 3D
[Active Appearance Model](https://www.cs.cmu.edu/~efros/courses/LBMV07/Papers/cootes-eccv-98.pdf)

[Thin Plate Spline Interpolation](https://en.wikipedia.org/wiki/Thin_plate_spline)

[DF2Net](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zeng_DF2Net_A_Dense-Fine-Finer_Network_for_Detailed_3D_Face_Reconstruction_ICCV_2019_paper.pdf): deep learning approach single image 3DMM generator.

## Loss Function
Give wrong labeled pixel penalty:
lossfunction(out,gt,reduction=None)*|Sig(out)-gt|

Hinge loss:
loss=max(0,1-gt*out)

## Explainability and Interpretability
~~[Explaining Explanations: An Overview of Interpretability of Machine Learning](https://arxiv.org/pdf/1806.00069.pdf)~~
