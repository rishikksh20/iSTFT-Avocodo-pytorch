# iSTFT Avocodo
iSTFT like generator and Avocodo like discriminators

## Training :
```
python train.py --config config_v1.json
```

## Notes :
* Two of iSTFT Generator version can be used with Avocodo discriminaators.
* Losses should similar to HiFi-GAN.
* 50 % speed up  in training and 60 % improvement in inference speed.


## Citations :
```
@inproceedings{kaneko2022istftnet,
title={{iSTFTNet}: Fast and Lightweight Mel-Spectrogram Vocoder Incorporating Inverse Short-Time Fourier Transform},
author={Takuhiro Kaneko and Kou Tanaka and Hirokazu Kameoka and Shogo Seki},
booktitle={ICASSP},
year={2022},
}
```
```
@misc{https://doi.org/10.48550/arxiv.2206.13404,
  doi = {10.48550/ARXIV.2206.13404},
  
  url = {https://arxiv.org/abs/2206.13404},
  
  author = {Bak, Taejun and Lee, Junmo and Bae, Hanbin and Yang, Jinhyeok and Bae, Jae-Sung and Joo, Young-Sun},
  
  keywords = {Audio and Speech Processing (eess.AS), Artificial Intelligence (cs.AI), Sound (cs.SD), FOS: Electrical engineering, electronic engineering, information engineering, FOS: Electrical engineering, electronic engineering, information engineering, FOS: Computer and information sciences, FOS: Computer and information sciences},
  
  title = {Avocodo: Generative Adversarial Network for Artifact-free Vocoder},
  
  publisher = {arXiv},
  
  year = {2022},
  
  copyright = {arXiv.org perpetual, non-exclusive license}
}
```
