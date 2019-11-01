# Self Using Note
**Some Useful Niubi** tricks, repositories and paper. Just use Ctrl+F and input key words to search what you what. ~~Strikethrough~~ means I have not gone through it.

## General Structure
[High Resolution Net(HRNet)](https://arxiv.org/abs/1904.04514): UNet with convolution in skip connection.

[DANet](https://arxiv.org/abs/1809.02983): Dual self attention module, great example of [pytorch sync-batch-norm and attention module](https://github.com/junfu1115/DANet).

~~[Independent Components Layer](https://arxiv.org/abs/1905.05928v1): Combination of batch normalization and dropout layer.~~

## Detection
[Uncertainty bounding box](https://arxiv.org/abs/1809.08545)

## Face Recognition
~~[Deep Comparator Network](https://arxiv.org/abs/1807.11440)~~

## Image Synthesis
[Few shot unsupervised image2image](https://arxiv.org/abs/1905.01723): Content module and style module.

[Pix2PixHD: Segmentation to image](https://arxiv.org/abs/1711.11585): Enhancer structure.

[Semantic Image Synthesis with Spatially-Adaptive Normalization(SPADE)](https://arxiv.org/abs/1903.07291): Used in GauGAN, segmentation to image.

[SinGAN](https://arxiv.org/abs/1905.01164): Using multiscale patch generator to learn the distribution of target nature image.(ICCV19 Best Paper)

[AdaIN](https://arxiv.org/abs/1703.06868): Adaptive instance normalization using in style transfer.

~~[Domain Intersection and Domain Difference](https://arxiv.org/abs/1908.11628)~~

### Face swapping: from beginner to give-up
[Face Swapping GAN(FSGAN)](https://arxiv.org/abs/1908.05932): Subject agnostic face swapping and reenactiment model.
[Face swapping GAN](https://github.com/shaoanlu/faceswap-GAN): Introducing self attention, Kalman Filter.
[Few-shot face swapping GAN](https://github.com/shaoanlu/fewshot-face-translation-GAN): Introducing AdaIN, SPADE.
[Deep face lab](https://github.com/iperov/DeepFaceLab): ~~deep cyka blyat learning!~~ Deep fake tools.

### 3D morphable model: from beginner to rookie
[Deep 3D face reconstruction](https://arxiv.org/abs/1903.08527): Code available [here](https://github.com/microsoft/Deep3DFaceReconstruction)
[3D face alignment](http://www.cbsr.ia.ac.cn/users/xiangyuzhu/projects/3DDFA/main.htm): 3dmm data and code.
[Python 3dmm tools](https://github.com/YadiraF/face3d)
[Another deep 3D face reconstruction](https://arxiv.org/abs/1903.10873): Code available [here](https://github.com/apchenstu/Facial_Details_Synthesis)

## 3D
[Active Appearance Model](https://www.cs.cmu.edu/~efros/courses/LBMV07/Papers/cootes-eccv-98.pdf)

[Thin Plate Spline Interpolation](https://en.wikipedia.org/wiki/Thin_plate_spline)

[DF2Net](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zeng_DF2Net_A_Dense-Fine-Finer_Network_for_Detailed_3D_Face_Reconstruction_ICCV_2019_paper.pdf): Deep learning approach single image 3DMM generator.

## Low Level Vision
~~[Deep Image Prior](https://arxiv.org/abs/1711.10925): VGG will have better result using in perceptual loss compared with ResNet.~~

## Loss Function
~~[Triple consistency loss for pairing distributions in GAN-based face synthesis](https://arxiv.org/abs/1811.03492): Combination of long path loss and short cut loss.~~

Give wrong labeled pixel penalty:
lossfunction(out,gt,reduction=None)*|Sig(out)-gt|

Hinge loss:
loss=max(0,1-gt*out)

## Explainability and Interpretability
~~[Explaining Explanations: An Overview of Interpretability of Machine Learning](https://arxiv.org/abs/1806.00069)~~
