# Awesome Neural Art [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

Creating art and manipulating images using deep neural networks.

## Contents

- [Colorization](#colorization)
- [Style Transfer](#style-transfer)
- [Super Resolution](#super-resolution)
- [Patching](#patching)
- [Image matting](#image-matting)
- [Deep Dream](#deep-dream)
- [Doodle to Image](#doodle-to-image)
- [Multiple categories](#multi-category)
- [Lectures](#lectures)

## Colorization

See also: [this subreddit](https://www.reddit.com/r/Colorization) where people do this manually.

- [Interactive Deep Colorization](https://github.com/junyanz/interactive-deep-colorization)

<img src='https://github.com/junyanz/interactive-deep-colorization/blob/master/imgs/demo.gif' width=600>  

<img src='https://richzhang.github.io/ideepcolor/index_files/imagenet_showcase_small.jpg' width=800>

- [colornet](https://github.com/pavelgonchar/colornet)

<img src='https://raw.githubusercontent.com/pavelgonchar/colornet/master/summary/209000_0.png' width=600>  

- [Colorful Image Colorization](https://github.com/richzhang/colorization)

<img src='https://camo.githubusercontent.com/0f54d76e1561911ef2c423251c386a9368551365/687474703a2f2f726963687a68616e672e6769746875622e696f2f636f6c6f72697a6174696f6e2f7265736f75726365732f696d616765732f746561736572342e6a7067' width=600>  


- [style2paints](https://github.com/lllyasviel/style2paints/) - sketch + style = paints art 

## Style Transfer

- [neural-style](https://github.com/jcjohnson/neural-style) - Torch implementation of neural style algorithm

<img src='https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/outputs/starry_stanford_bigger.png' width=600>  

- [adaptive-style-transfer](https://github.com/tensorlayer/adaptive-style-transfer) - Arbitrary Style Transfer in Real-time with Adaptive Instance Normalization.
- [deep-photo-styletransfer](https://github.com/luanfujun/deep-photo-styletransfer) - Code and data for ["Deep Photo Style Transfer"](https://arxiv.org/abs/1703.07511).
- [fast-style-transfer](https://github.com/lengstrom/fast-style-transfer#image-stylization) - TensorFlow CNN for fast style transfer with larger scale style features in transformations.
- [texture_nets](https://github.com/DmitryUlyanov/texture_nets) - Code for "Texture Networks: Feed-forward Synthesis of Textures and Stylized Images". 
- [AdaIN-style](https://github.com/xunhuang1995/AdaIN-style) - Code for [Arbitrary Style Transfer in Real-time with Adaptive Instance Normalization](https://arxiv.org/abs/1703.06868)

Neat features:

- [Transfer style but not color](https://github.com/xunhuang1995/AdaIN-style#transfer-style-but-not-color)
- Style interpolation

<img src='https://raw.githubusercontent.com/xunhuang1995/AdaIN-style/master/examples/style_interp.jpg' width=600>  
 - spatial control
 
<img src='https://raw.githubusercontent.com/xunhuang1995/AdaIN-style/master/examples/spatial_control.jpg' width=600>  


- [Bicycle GAN](https://github.com/junyanz/BicycleGANg) - NIPS 2017 Toward Multimodal Image-to-Image Translation, PyTorch implementation. Given the same night image, model is able to synthesize possible day images with different types of lighting, sky and clouds.

<img src='https://github.com/junyanz/BicycleGAN/blob/master/imgs/results_matrix.jpg' width=820>  


## Neural Style Transfer & Neural Doodles

- [Neural Style Transfer](https://github.com/titu1994/Neural-Style-Transfer) - Keras Implementation of Neural Style Transfer from the paper ["A Neural Algorithm of Artistic Style"](http://arxiv.org/abs/1508.06576) in Keras 2.0+

- [Deep Painterly Harmonization](https://github.com/luanfujun/deep-painterly-harmonization) - Photoshopping an object into a painting, and then neural network changes the style (pallete, strokes, luminosity, etc) of the object to match the painting style. [See paper](https://arxiv.org/abs/1804.03189).

## Super Resolution

- [waifu2x](https://github.com/nagadomi/waifu2x) - Image Super-Resolution for Anime-Style Art 

<img src='https://raw.githubusercontent.com/nagadomi/waifu2x/master/images/slide.png' width=820>  

- [srgan](https://github.com/tensorlayer/srgan) - Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network 

<img src='https://raw.githubusercontent.com/tensorlayer/srgan/master/img/SRGAN_Result3.png' width=820>  

- [fft-descreen](https://github.com/6o6o/fft-descreen) - Clean up deconvolution checkerboard artifacts found in style transferred images.

## Patching

## Image matting

AKA subtracting the background from the foreground. See also: [Awesome Background Subtraction](https://github.com/murari023/awesome-background-subtraction)

- Deep Image Matting - Implementations of the [Deep Image Matting paper](https://sites.google.com/view/deepimagematting).
  - [Dataset generator](https://github.com/hector-sab/DIM_DataCreation) - Generates training data for the Deep Image Matting paper.
  - [Tensorflow implementation](https://github.com/Joker316701882/Deep-Image-Matting) - Original paper author.
  - [PyTorch implementation](https://github.com/foamliu/Deep-Image-Matting-v2) - Same author as [Keras implementation](https://github.com/foamliu/Deep-Image-Matting), but this is their improved (and maintained) codebase.
  - [Another PyTorch implementation](https://github.com/huochaitiantang/pytorch-deep-image-matting)

- [Salient Object Detection](https://github.com/Joker316701882/Salient-Object-Detection) - Tensorflow implementation for cvpr2017 paper ["Deeply Supervised Salient Object Detection with Short Connections"](https://arxiv.org/abs/1611.04849) (not peer reviewed). Same author as original Deep Image Matting author.
- [AlphaGAN](https://github.com/CDOTAD/AlphaGAN-Matting) - Unofficial implementation of [AlphaGAN: Generative adversarial networks for natural image matting](https://arxiv.org/pdf/1807.10088.pdf). Uses a GAN as the name suggests.
- [DeepLab V3+](https://github.com/jfzhang95/pytorch-deeplab-xception) - Implementations of an encoder-decoder Modified Aligned Xception and ResNet as backbone [(paper)](https://arxiv.org/pdf/1802.02611.pdf).

## Deep Dream

- [deepdream](https://github.com/google/deepdream) - The original Google implementation.

## Doodle to Image

- [neural-doodle](https://github.com/alexjc/neural-doodle) - 
Turn your two-bit doodles into fine artworks with deep neural networks, generate seamless textures from photos, transfer style from one image to another, perform example-based upscaling, but wait... there's more! (An implementation of Semantic Style Transfer.) 

<img src='https://github.com/alexjc/neural-doodle/blob/master/docs/Workflow.gifx' width=820>  


- [iGAN](https://github.com/junyanz/iGAN) - iGAN: Interactive Image Generation via Generative Adversarial Networks

<img src='https://raw.githubusercontent.com/junyanz/iGAN/master/pics/demo.gif' width=820>  


## Multiple categories

- [deep-image-prior](https://github.com/DmitryUlyanov/deep-image-prior) -  Image restoration with neural networks but without learning. Does artifact removal, inpainting, super-resolution, denoising

## Lectures/Reviews

- [The Neural Aesthetic @ ITP-NYU, Fall 2018](https://ml4a.github.io/classes/itp-F18/)
- [Neural Style Transfer Review](https://github.com/ycjing/Neural-Style-Transfer-Papers) - Repo for the [Neural Style Transfer review article](https://arxiv.org/abs/1705.04058).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Richard Decal](https://www.richarddecal.com) has waived all copyright and related or neighboring rights to this work.
