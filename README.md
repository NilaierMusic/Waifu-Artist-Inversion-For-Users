# Waifu-Artist-Inversion-For-Users

> **A large library of textual inversion embeddings trained on a works of a real anime artists**<br>
> Nilaier <br>

>**Overview**: <br>
> Using techniques such as An Image is Worth One Word: Personalizing Text-to-Image Generation using Textual Inversion[![arXiv](https://img.shields.io/badge/arXiv-2208.01618-b31b1b.svg)](https://arxiv.org/abs/2208.01618) and DreamArtist: Towards Controllable One-Shot Text-to-Image Generation via Contrastive Prompt-Tuning[![arXiv](https://img.shields.io/badge/arXiv-2211.11337-b31b1b.svg)](https://arxiv.org/abs/2211.11337), this project aims to provide users with embeddings for their favorite anime models to accurately replicate the style of their favorite anime artists to enchance their creativity in their own project. Owner of this repository highly encourages anyone interested to contribute in enlarging this project to share your own textual inversion embeddings in the pull requests.

## ✒Description✒
This repo contains embeddings, negative embeddings and their examples for a different models.

## ⚠**WARNING**⚠
**This repository contains Not Safe For Work images and embeddings, but don't worry, they're always separated in NSFW directory**

## TODO:
- [x] Write README.md
- [x] Add initial embeddings
- [ ] Add some cool images, because this is so gloomy to read
- [x] Add AnythingV3 embeddings
- [ ] Add Waifu Diffusion v1.4 embeddings
- [ ] Create a discord server

## 📁Structure📁

This repository contains embeddings for a different anime-related models.
These models are:

- Anything V3.0
- NovelAI anime full pruned
- Waifu Diffusion v1.3

Over time this list would grow larger and larger.
If you want to help, open a PR with your embeddings, their settings (vectors, steps trained, amount of images trained), model name and examples.

First folder names usually include names of the models that was used to train embeddings. Then, after that, directory is divided into two folders usually named as ***SFW*** and ***NSFW***. As you can probably tell, that means that embeddings and artists produce mostly *Safe For Work* content or not. If you venture further, either of the directories contains a folders with artist names. Further down the line you would see a folder/s titled **TI** or **DA**. **TI** - means trained with [Automatic WebUI's](https://github.com/AUTOMATIC1111/stable-diffusion-webui) textual inversion. **DA** - means trained with [Dream Artist](https://github.com/7eu7d7/DreamArtist-stable-diffusion). After that, embeddings, grid3x3 examples and img2img examples.
```
         <model-name>/
         └╴SFW/
           ├╴<artist-name>/
           │ ├╴TI/
           │   ├╴<embeddings>.pt
           │   ├╴<grid-example>.png
           │   ├╴<img2img-example>.png
           │ └╴DA/
           │   ├╴<embeddings>.pt
           │   ├╴<embeddings-neg>.pt
           │   ├╴<grid-example>.png
           │   ├╴<img2img-example>.png
           │
         └╴NSFW/
           ├╴...
```

## Usage

### Textual Inversion [![Github](https://files.catbox.moe/oo19z8.png)](https://github.com/rinongal/textual_inversion)

I recommend using embeddings in [WebUI made by Automatic1111](https://github.com/AUTOMATIC1111/stable-diffusion-webui). So, if you want to do that, drag embeddings into **stable-diffusion-webui/embeddings** folder and use embeddings filename in your prompt to initialize it.

### Dream Artist [![Github](https://files.catbox.moe/oo19z8.png)](https://github.com/7eu7d7/DreamArtist-stable-diffusion)

For using Dream Artist embeddings, process mostly similar to Textual Inversion case, but you would also need to download [Dream Artist WebUI Extension](https://github.com/7eu7d7/DreamArtist-sd-webui-extension) into webui's extension folder or use a [standalone Dream Artist WebUI](https://github.com/7eu7d7/DreamArtist-stable-diffusion).

## For artists🎨
If you want me to remove embeddings assosiated with your style. Please, send me a DM on [twitter!](https://twitter.com/NilaierMusic)[![Twitter](https://files.catbox.moe/1z7x6d.png)](https://twitter.com/NilaierMusic)

## Discord Server![Discord](https://files.catbox.moe/v3q557.png)
Soon (or not)
