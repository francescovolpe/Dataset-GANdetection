# Dataset GANdetection
Repository containing all training, validation and evaluation datasets used for the project [GANdetection](https://github.com/francescovolpe/GANdetection)


## Overview
All data are stored on Google Drive:

| Path | Files | Format | Resolution | FD | Filtered | Source (Original images) |
| :--- | ----: | :----: | :----: | :----: | :----: | :----: |
| [Dataset train](https://drive.google.com/drive/folders/1uLddVmSqS_TvMJwHRHkg2t3BZrtsBOda?usp=sharing) |  |  | |||
| &boxvr;&nbsp; CAHQ | 26824 | JPG | 160x160 | &check; | &check; | [&neArr;](https://github.com/tkarras/progressive_growing_of_gans) |
| &boxvr;&nbsp; StyleGAN CAHQ| 26824 | PNG | 160x160 | &check; | &check; | [&neArr;](https://github.com/NVlabs/stylegan) |
| [Dataset test](https://drive.google.com/drive/folders/12237PDZ-RBNkVzy7UylG_ZO8OriBG21D?usp=sharing)  |  |  | |||
| &boxvr;&nbsp; CAHQ  | 3000 | JPG | 160x160 | &check; | &cross; | [&neArr;](https://github.com/tkarras/progressive_growing_of_gans) |
| &boxvr;&nbsp; CelebA  | 3000 | JPG | 160x160 | &check; | &cross; | [&neArr;](https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) |
| &boxvr;&nbsp; DiscoFaceGAN  | 3000 | PNG | 160x160 | &check; | &cross; | [&neArr;](https://github.com/microsoft/DiscoFaceGAN) |
| &boxvr;&nbsp; FaceApp DFFD  | 3000 | PNG | 160x160 | &check; | &cross; | [&neArr;](http://cvlab.cse.msu.edu/project-ffd.html) |
| &boxvr;&nbsp; FFHQ| 3000 | PNG | 160x160 | &check; | &cross; | [&neArr;](https://github.com/NVlabs/ffhq-dataset) |
| &boxvr;&nbsp; GLOW | 3000 | PNG | 160x160 | &check; | &cross; | [&neArr;](https://openai.com/blog/glow/) |
| &boxvr;&nbsp; LFW | 3000 | JPG | 160x160 | &check; | &cross; | [&neArr;](http://vis-www.cs.umass.edu/lfw/) |
| &boxvr;&nbsp; ProGAN | 3000 | PNG | 160x160 | &check; | &cross; | [&neArr;](https://github.com/tkarras/progressive_growing_of_gans) |
| &boxvr;&nbsp; StyleGAN 2 FFHQ 0.5| 3000 | PNG | 160x160 | &check; | &cross; | [&neArr;](https://github.com/NVlabs/stylegan2) |
| &boxvr;&nbsp; StyleGAN CAHQ 0.5 | 3000 | PNG | 160x160 | &check; | &cross; | [&neArr;](https://github.com/NVlabs/stylegan) |
| &boxvr;&nbsp; StyleGAN FFHQ | 3000 | PNG | 160x160 | &check; | &cross; | [&neArr;](https://github.com/NVlabs/stylegan) |
| &boxur;&nbsp; Utk Face | 3000 | JPG | 160x160 | &check; | &cross; | [&neArr;](https://susanqq.github.io/UTKFace/) |

<br>
Note: <br>
FD = it indicates whether facial recognition algorithms have been applied to the datasets <br>
Filtered = it indicates whether the datasets were filtered by removing images where face detect was fail








