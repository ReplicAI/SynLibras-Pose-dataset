# Data-Base
SynLibras: A database with body posture notation Model for Brazilian Sign Language Synthesis.
Wellington Silveira (FURG); Andrew Allaniz (FURG); Marina Hurtado (FURG); Bernardo Castello (FURG); 
Rodrigo de Bem (FURG).
SIBGRAPI 2022.

## Overview
<img src='Img/exemplo 1.png' width="1000px"/>
<img src='Img/exemplo 2.png' width="1000px"/>

The database was collected from the videos of the Libras-Portuguese dictionary project (Uni-Federal University of Viçosa, 2017).Using image manipulation in the Python language, theframe-by-frame videos, and these were resized to 1024x1024 pixels.

## Dataset
<img src='Img/0.jpg' width="250px"/><img src='Img/1.jpg' width="250px"/><img src='Img/2.jpg' width="250px"/><img src='Img/3.jpg' width="250px"/>

the bank is available at this link:(https://mega.nz/file/JFZmkJQR#DGAgMi1NVBWaD72aTJGh9EQrXAWFAZCe9wrDlm7mIZQ)

427 videos were obtained containing more than 73,000 frames numbered by actors. Each video represents a word or a concept of it, we divided the videos by their 4 actors remaining after pre-processing. split up still the data in videos, frames and poses, with each video having its frames and poses associated with their respective names.
The generated poses consist of 12 body points, 10 points for thehands, and also possessed 8 facial points.
With high definition images dot loss is minimal for each frame making dot accuracy much higher than those of other banks. Despite this, there may still be consistencies in the estimation of poses that can harm the training of methods based on these data. Thus, one of the contributions of this work was the development of a tool for viewing and editing component points of the body pose. Thus, it was possible to correct errors in the active giving greater precision and accuracy to the pose estimates

<img src='Img/correcao.png' width="1000px"/>

[OpenPose](https://github.com/CMU-Perceptual-Computing-Lab/openpose)

