[![Build Status](https://travis-ci.org/lucianodato/speech-denoiser.svg?branch=master)](https://travis-ci.org/lucianodato/speech-denoiser)

**WARNING!!!!** This project is not being actively mantained currently please refer to https://github.com/werman/noise-suppression-for-voice which is similar and more updated.

speech-denoiser
------
A speech denoise lv2 plugin based on the modified Xiph's RNNoise library by GregorR

What is RNNoise?
-----
RNNoise is a library that uses deep learning to apply noise supression to audio sources with voice presence. You can learn more about it here: https://people.xiph.org/~jm/demo/rnnoise/

Requirements
-----
You will require git gnu-make gnu-autoconf gnu-m4 gnu-libtool glibc to be installed on your system in order to compile the static instance of RNNoise library

To compile and install this plug-in you will need the LV2 SDK, Meson build system (use pip3 to install it), ninja compiler and git

Installation 
-----
```bash
  git clone https://github.com/lucianodato/speech-denoiser.git
  cd speech-denoiser
  chmod +x install.sh && ./install.sh
```

Help RNNoise to get better!
-----
Remember to donate a minute of noise to the cause -> https://people.xiph.org/~jm/demo/rnnoise/donate.html

Alternative
-----
Make sure to check out Noise Repellent LV2 plugin if this is not working for you -> https://github.com/lucianodato/noise-repellent
