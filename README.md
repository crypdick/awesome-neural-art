# Awesome Neural Art 

A curated list of awesome neural network-based art resources. 


### [Multiple categories](#multi-category)

- [deep-image-prior](#deep-image-prior)

### [Colorization](#colorization)

- [Interactive Deep Colorization](#interactive-deep-colorization)
- [Colornet](#colornet)
- [Colorful Image Colorization](#colorful-image-colorization)
- [style2paints](#style2paints)

### [Style Transfer](#style-transfer)

- [Neural Style](#neural-style)
- [adaptive-style-transfer](#adaptive-style-transfer)
- [deep-photo-styletransfer](#deep-photo-styletransfer)
- [fast-style-transfer](#fast-style-transfer)
- [texture_nets](#texture_nets)
- [AdaIN-style](#AdaIN-style)
- [Image-to-Image Transfer](#image-to-image-transfer)
- [Neural Style Transfer](#Neural-Style-Transfer)
- [Deep Painterly Harmonization](#deep-painterly-harmonization)

### [Super Resolution](#super-resolution)

- [waifu2x](#waifu2x)
- [srgan](#srgan)
- [fft-descreen](#fft-descreen)


### [Patching](#patching)


### [Deep Dream](#deep-dream)

- [deepdream](#deepdream)

### [Doodle to Image](#doodle-to-image)

- [neural-doodle](#neural-doodle)
- [iGAN](#iGAN)

### [Lectures](#lectures)

- [The Neural Aesthetic](#neural-aesthetic)
- [Neural Style Transfer Review](#neural-style-transfer-review)



# Multiple categories

## [deep-image-prior](https://github.com/DmitryUlyanov/deep-image-prior)

Image restoration with neural networks but without learning.

artifact removal, inpainting, super-resolution, denoising





# Colorization

A subreddit where people do this manually: https://www.reddit.com/r/Colorization

## [Interactive Deep Colorization](https://github.com/junyanz/interactive-deep-colorization)


<img src='https://github.com/junyanz/interactive-deep-colorization/blob/master/imgs/demo.gif' width=600>  

<img src='https://richzhang.github.io/ideepcolor/index_files/imagenet_showcase_small.jpg' width=800>

## [colornet](https://github.com/pavelgonchar/colornet)

<img src='https://raw.githubusercontent.com/pavelgonchar/colornet/master/summary/209000_0.png' width=600>  

## [Colorful Image Colorization](https://github.com/richzhang/colorization)

<img src='https://camo.githubusercontent.com/0f54d76e1561911ef2c423251c386a9368551365/687474703a2f2f726963687a68616e672e6769746875622e696f2f636f6c6f72697a6174696f6e2f7265736f75726365732f696d616765732f746561736572342e6a7067' width=600>  


## [style2paints](https://github.com/lllyasviel/style2paints/)

sketch + style = paints art 

# Style Transfer

## [neural-style](https://github.com/jcjohnson/neural-style)

Torch implementation of neural style algorithm 

<img src='https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/outputs/starry_stanford_bigger.png' width=600>  


## [adaptive-style-transfer](https://github.com/tensorlayer/adaptive-style-transfer)

Arbitrary Style Transfer in Real-time with Adaptive Instance Normalization

https://github.com/tensorlayer/adaptive-style-transfer#results

## [deep-photo-styletransfer](https://github.com/luanfujun/deep-photo-styletransfer)

Code and data for paper "Deep Photo Style Transfer": https://arxiv.org/abs/1703.07511


https://github.com/luanfujun/deep-photo-styletransfer#examples

## [fast-style-transfer](https://github.com/lengstrom/fast-style-transfer)

TensorFlow CNN for fast style transfer

https://github.com/lengstrom/fast-style-transfer#image-stylization

Our implementation uses TensorFlow to train a fast style transfer network. We use roughly the same transformation network as described in Johnson, except that batch normalization is replaced with Ulyanov's instance normalization, and the scaling/offset of the output tanh layer is slightly different. We use a loss function close to the one described in Gatys, using VGG19 instead of VGG16 and typically using "shallower" layers than in Johnson's implementation (e.g. we use relu1_1 rather than relu1_2). Empirically, this results in larger scale style features in transformations.

## [texture_nets](https://github.com/DmitryUlyanov/texture_nets)

Code for "Texture Networks: Feed-forward Synthesis of Textures and Stylized Images" paper. 

## [AdaIN-style](https://github.com/xunhuang1995/AdaIN-style)

Arbitrary Style Transfer in Real-time with Adaptive Instance Normalization https://arxiv.org/abs/1703.06868

Neat features:

- [Transfer style but not color](https://github.com/xunhuang1995/AdaIN-style#transfer-style-but-not-color)
- Style interpolation

<img src='https://raw.githubusercontent.com/xunhuang1995/AdaIN-style/master/examples/style_interp.jpg' width=600>  
 - spatial control
 
<img src='https://raw.githubusercontent.com/xunhuang1995/AdaIN-style/master/examples/spatial_control.jpg' width=600>  


## Image-to-Image Transfer

[Bicycle GAN](https://github.com/junyanz/BicycleGANg) 

NIPS 2017 Toward Multimodal Image-to-Image Translation

<img src='https://github.com/junyanz/BicycleGAN/blob/master/imgs/results_matrix.jpg' width=820>  


Pytorch implementation for multimodal image-to-image translation. For example, given the same night image, our model is able to synthesize possible day images with different types of lighting, sky and clouds. The training requires paired data.


## [Neural Style Transfer & Neural Doodles](https://github.com/titu1994/Neural-Style-Transfer)


Keras Implementation of Neural Style Transfer from the paper "A Neural Algorithm of Artistic Style" (http://arxiv.org/abs/1508.06576) in Keras 2.0+ 

https://github.com/titu1994/Neural-Style-Transfer#examples


## [Deep Painterly Harmonization](https://github.com/luanfujun/deep-painterly-harmonization)

Photoshopping an object into a painting, and then neural network changes the style (pallete, strokes, luminosity, etc) of the object to match the painting style. Paper: https://arxiv.org/abs/1804.03189

# Super Resolution

## [waifu2x](https://github.com/nagadomi/waifu2x)

Image Super-Resolution for Anime-Style Art 

<img src='https://raw.githubusercontent.com/nagadomi/waifu2x/master/images/slide.png' width=820>  

## [srgan](https://github.com/tensorlayer/srgan)

Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network 

<img src='https://raw.githubusercontent.com/tensorlayer/srgan/master/img/SRGAN_Result3.png' width=820>  

## [fft-descreen](https://github.com/6o6o/fft-descreen)

Originally intended to clean up deconvolution checkerboard artifacts, found in style transferred images, I thought it may have its uses in other areas, like cleaning low-dpi scans and therefor would be better off as a separate script. I excluded the optional despeckle step, found in original plugin for being too destructive. Instead, I find waifu2x to give a superior result in case of artistically styled images, thus tend to use it with maximum noise reduction as a second step.


# Patching



# Deep Dream

## [deepdream](https://github.com/google/deepdream)

# Doodle to Image

## [neural-doodle](https://github.com/alexjc/neural-doodle)


Turn your two-bit doodles into fine artworks with deep neural networks, generate seamless textures from photos, transfer style from one image to another, perform example-based upscaling, but wait... there's more! (An implementation of Semantic Style Transfer.) 

<img src='https://github.com/alexjc/neural-doodle/blob/master/docs/Workflow.gifx' width=820>  


## [iGAN](https://github.com/junyanz/iGAN)

iGAN: Interactive Image Generation via Generative Adversarial Networks

<img src='https://raw.githubusercontent.com/junyanz/iGAN/master/pics/demo.gif' width=820>  


# Lectures/Reviews

## [The Neural Aesthetic @ ITP-NYU, Fall 2018](https://ml4a.github.io/classes/itp-F18/)

## [Neural Style Transfer Review](https://github.com/ycjing/Neural-Style-Transfer-Papers)

Repo for the review article: https://arxiv.org/abs/1705.04058

