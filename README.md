# Acoustic-DL

## Music/Audio/Voice/Speech Source Separation

Source separation for music is the task of isolating contributions, or stems, from different instruments recorded individually and arranged together to form a song. Such
components include voice, bass, drums and any other accompaniments.

Unlike audio synthesis tasks that generate waveforms directly, state-of-the-art source separation methods compute masks on the magnitude spectrum.


Waveform Domain Architectures:
- Demucs
- Hybrid Demucs
- Demucs with Transformers
- Band-split RNN
- Conv-Tasnet

## 1. ![DEMUCS](https://arxiv.org/abs/1911.13254): (Deep Extractor for Music Sources)

- Demucs takes a stereo mixture as input and outputs a stereo estimate for each source (C = 2).
- It is an encoder/decoder architecture composed of a **convolutional encoder, a bidirectional LSTM, and a convolutional decoder, with the encoder and decoder
linked with skip U-Net connections.** 


![image](https://user-images.githubusercontent.com/129742046/230777568-c2ba40fa-d839-4300-9ba3-f3bc29eea57d.png)

#### Note: Batch Normalization was not used as  it was found to be detrimental to the model performance.
