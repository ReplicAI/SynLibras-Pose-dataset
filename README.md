# Data-Base
SynLibras: A database with body posture notation Model for Brazilian Sign Language Synthesis.
Wellington Silveira (FURG); Andrew Allaniz (FURG); Marina Hurtado (FURG); Bernardo Castello (FURG); 
Rodrigo de Bem (FURG).
SIBGRAPI 2022.

## Overview
<img src='img/exemplo 1.png.png' width="1000px"/>
<img src='img/exemplo 2.png.png' width="1000px"/>

Our SynLibras architecture is an CVAE-GAN model. During training, an input RGB image x is received by the Encoder (E) and reconstructed by the Decoder/Generator (G) aiming for the minimization of the L1-norm reconstruction loss. Meanwhile, the heatmap pose representation y is conditioning these two modules. It is also the input of a Prior (P), which is used in the minimization of the KL-divergence. Finally, a Discriminator module (D) classifies the output images as real or fake.

