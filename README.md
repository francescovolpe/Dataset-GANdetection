# Dataset GANdetection
Repository contenente tutti i dataset di addestramento, validazione e valutazione utilizzati per il progetto [GANdetection](https://github.com/francescovolpe/GANdetection)


## Overview
Tutti i dati sono memorizzati su Google Drive:

| Path | Files | Format | Resolution | FD | Filtered | Source |
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
FD = indica se sono stati applicati algoritmi di riconoscimento facciale sui dataset <br>
Filtered = indica se i dataset sono stati filtrati rimuovendo immagini in cui il face detect non ha avuto successo









