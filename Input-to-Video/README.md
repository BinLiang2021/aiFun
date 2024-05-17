# Input-to-Video Category

Welcome to the Input-to-Video section of our AI for Fun repository. This category explores various functionalities within the realm of video synthesis. Here, you will find a collection of tools and examples that showcase different aspects of video generation technology.

## Sub-Categories

Each sub-category provides specialized models and tools designed to cater to different aspects of video synthesis. Below, you will find a list of sub-categories, along with a brief description and example models.

### 1. Standard image-to-video animation
- **Description**: Converts image into animation
- **Open-soured Method**:


[Thin-Plate-Spline-Motion-Model](https://github.com/yoyo-nb/Thin-Plate-Spline-Motion-Model)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1DREfdpnaBhqISg0fuQlAAIwyGVn1loH_?usp=sharing)

[open-mmlab/pia](https://github.com/open-mmlab/PIA)
[playground](https://replicate.com/open-mmlab/pia)


However, the closed source program has higher resolution, there are multiple tools that can be used: 

[D-ID](https://www.d-id.com/)
[synthesia](https://www.synthesia.io/)
[Vidnoz](https://aiapp.vidnoz.com/avatar/index.html)



### 2. lip sync
- **Description**: Accurately Lip-syncing Videos In The Wild, create Avatar with text/audio and image/video
- **Open-soured Method**:

Classic wav2lip, input video and audio file, output the video which sync the lip to the audio file.

[Wav2Lip](https://github.com/Rudrabha/Wav2Lip)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1tZpDWXz49W6wDcTprANRGLo2D_EbD5J8?usp=sharing)

[Sync Labs](https://synclabs.so/)

It hosts free wave2lip model for public and it also hosts higher resolution model sync-1.6.0 for lip sync.


There is another method called SadTalker, which has similar performance compared to the wave2lip model.
Unlike wave2lip, the input of SadTalker is image and audio.
[SadTalker](https://github.com/OpenTalker/SadTalker)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Winfredy/SadTalker/blob/main/quick_demo.ipynb)

The microsoft reserach has just publish a paper that adds eyes movement to the lip sync with 512*512 relosultion, here is the [link](https://arxiv.org/abs/2404.10667).

Again, the closed source program has higher resolution, and most of them provide both functionalities ofimage-to-video animation and lip sync: 

[D-ID](https://www.d-id.com/)

[synthesia](https://www.synthesia.io/)

[Vidnoz](https://aiapp.vidnoz.com/avatar/index.html)


### 3. text to video
- **type 1**: generate video based on text input:

The hottest model sora, is not yet published.
[sora](https://openai.com/index/sora/)

There are several alternative:

prompt: an astonishing asian girl work on the stone street under the rain, with umbrella in hand

[Haiper](https://haiper.ai/product)

https://github.com/protagolabs/aiFun/assets/33402371/9cc0fa82-7c6e-4f78-8b79-2aabb43a4750



[runway](https://app.runwayml.com/video-tools/teams/xiangpengwan/ai-tools/gen-2)

https://github.com/protagolabs/aiFun/assets/33402371/481df6ce-42a6-4ebd-90ba-da94a6a5d9c0



