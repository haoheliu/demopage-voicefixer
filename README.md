# VoiceFixer

Still working on this page, you can take a look if interest
[https://haoheliu.github.io/demopage-voicefixer/](https://haoheliu.github.io/demopage-voicefixer/)


# Overview

Speech restoration is a task to remove distortions in natural speech signal. Almost all previous methods follow Single Task Speech Restoration(SSR), such as speech declipping, meaning focuses on one distortion type. This design scheme have huge mismatch to speech in natural world, causing problems on model performance and generalization ability. We proposed a novel task called Generic Speech Restoration(GSR), which aims at handling multiple distortions simutaneously. To better address GSR task, we also proposed VoiceFixer, a generative and synthetic architecture that consists of an analysis stage and a synthesis stage. The effective use of the speaker-independent vocoder in VoiceFixer remarkably facilitates its performance. In this paper, the distortion types we focus on include noise, room reverberation, low resolution speech with samplerate ranging from 2kHz to 44.1kHz, and clipping with threhold between 0.1 and 0.9. In our experiment, we found GSR is advantageous over SSR using mainstream non-linear regression model. Also, in GSR evaluation set, our proposed VoiceFixer model surpasses the regression based GSR model and enhancement only SSR model by 0.256 and 0.755 on MOS score. We notice that VoiceFixer can effectively generalize to the seriously degraded natural speech recordings, which indicates its potential in the applications like old movies and historical speech repairing.

