---
title: "Broadband DOA Estimation Using Convolutional Neural Networks Trained with Noise signals"
authors: "**S. Chakrabarty**, and E. A. P. Habets"
collection: publications
permalink: /publication/2017-10-WASPAA-CNNDOA
excerpt: 'This work our first study into application of deep learning to microphone array processing. With a simple representation of the multi-channel input data, that we call "Phase Map", it is shown that synthesized noise signals can be used to train a convolutional neural network for the task of source localization.'
docs: '<i class="fa fa-file-pdf-o" aria-hidden="true"></i> [PDF](https://arxiv.org/pdf/1705.00919.pdf)&emsp;
<i class="fa fa-television" aria-hidden="true"></i> [Presentation](http://Soumitro-Chakrabarty.github.io/files/17_WASPAA_presentation.pdf)&emsp;
<i class="fa fa-book" aria-hidden="true"></i> [Bibtex](http://Soumitro-Chakrabarty.github.io/files/17_WASPAA_bib.tex)'
date: 2017-10-15
venue: 'IEEE Workshop on Applications of Signal Processing to Audio and Acoustics (WASPAA), USA'
---

'<i class="fa fa-file-pdf-o" aria-hidden="true"></i> [PDF](https://arxiv.org/pdf/1705.00919.pdf)&emsp;
<i class="fa fa-television" aria-hidden="true"></i> [Presentation](http://Soumitro-Chakrabarty.github.io/files/17_WASPAA_presentation.pdf)&emsp;
<i class="fa fa-book" aria-hidden="true"></i> [Bibtex](http://Soumitro-Chakrabarty.github.io/files/17_WASPAA_bib.tex)

Abstract: A convolution neural network (CNN) based classification method
for broadband DOA estimation is proposed, where the phase component
of the short-time Fourier transform coefficients of the received
microphone signals are directly fed into the CNN and the features
required for DOA estimation are learnt during training. Since only
the phase component of the input is used, the CNN can be trained
with synthesized noise signals, thereby making the preparation of the
training data set easier compared to using speech signals. Through
experimental evaluation, the ability of the proposed noise trained
CNN framework to generalize to speech sources is demonstrated. In
addition, the robustness of the system to noise, small perturbations
in microphone positions, as well as its ability to adapt to different
acoustic conditions is investigated using experiments with simulated
and real data.
