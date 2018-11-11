# Awesome Neural Art 

A curated list of awesome neural network-based art resources.

### [Intro](#intro-1)

- [Image-to-Image Transfer](#image-to-image-transfer)
- [Interactive Deep Colorization](#interactive-deep-colorization)
- [First steps](#first-steps)
- [Minimal vimrc](#minimal-vimrc)
- [What kind of Vim am I running?](#what-kind-of-vim-am-i-running)
- [Cheatsheets](#cheatsheets)

### [Usage](#usage-1)

- [Getting help offline](#getting-help-offline)
- [Getting help offline (alternative)](#getting-help-offline-alternative)
- [Getting help online](#getting-help-online)
- [Autocmds in practice](#autocmds-in-practice)
  - [User events](#user-events)
  - [Nested autocmds](#nested-autocmds)
- [Clipboard](#clipboard)
  - [Clipboard usage (Windows, macOS)](#clipboard-usage-windows-macos)
  - [Clipboard usage (Linux, BSD, ...)](#clipboard-usage-linux-bsd-)
- [Restore cursor position when opening file](#restore-cursor-position-when-opening-file)
- [Temporary files](#temporary-files)
  - [Backup files](#backup-files)
  - [Swap files](#swap-files)
  - [Undo files](#undo-files)
  - [Viminfo files](#viminfo-files)
  - [Example configuration for temporary files](#example-configuration-for-temporary-files)
- [Editing remote files](#editing-remote-files)
- [Managing plugins](#managing-plugins)
- [Block insert](#block-insert)
- [Running external programs and using filters](#running-external-programs-and-using-filters)
- [Cscope](#cscope)
- [MatchIt](#matchit)
- [True colors](#true-colors)

# Intro

## Image-to-Image Transfer

[Bicycle GAN](https://github.com/junyanz/BicycleGANg) 
NIPS 2017 Toward Multimodal Image-to-Image Translation

<img src='https://github.com/junyanz/BicycleGAN/blob/master/imgs/results_matrix.jpg' width=820>  


Pytorch implementation for multimodal image-to-image translation. For example, given the same night image, our model is able to synthesize possible day images with different types of lighting, sky and clouds. The training requires paired data.

## Interactive Deep Colorization

[nteractive-deep-colorization](https://github.com/junyanz/interactive-deep-colorization)


<img src='https://github.com/junyanz/interactive-deep-colorization/blob/master/imgs/demo.gif' width=600>  

<img src='https://richzhang.github.io/ideepcolor/index_files/imagenet_showcase_small.jpg' width=800>

Vim adheres to the modal editing philosophy. This means that it provides
multiple modes and the meaning of keys changes according to the mode. You
navigate files in _normal mode_, you insert text in _insert mode_, you select
lines in _visual mode_, you access commands in _command-line mode_ and so on.
This might sound complicated at first, but has a huge advantage: you don't have
to break your fingers by holding several keys at once, most of the time you
simply press them one after the other. The more common the task, the fewer keys
are needed.

A related concept that works well with modal editing are operators and motions.
_Operators_ start a certain action, e.g. changing, removing, or selecting text.
Afterwards you specify the region of text you want to act on using a _motion_.
To change everything between parentheses, use `ci(` (read _change inner
parentheses_). To remove an entire paragraph of text, use `dap` (read _delete
around paragraph_).

If you see advanced Vim users working, you'll notice that they speak the
_language of Vim_ as well as pianists handle their instruments. Complex
operations are done using only a few key presses. They don't even think about it
anymore as [muscle memory](https://en.wikipedia.org/wiki/Muscle_memory) took
over already. This reduces [cognitive
load](https://en.wikipedia.org/wiki/Cognitive_load) and helps to focus on the
actual task.

