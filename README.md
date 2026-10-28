# DriftAudio audio demo

[Listen to the comparisons](https://xingyuaudio.github.io/driftaudio-demo/) · [Paper](https://arxiv.org/abs/2609.27598) · [Code](https://github.com/xingyuaudio/DriftAudio) · [Model weights](https://huggingface.co/xingyuchen-8/DriftAudio)

The page compares MeanAudio-S-Full, DriftAudio from MeanAudio-S-Full (step 4400), official FdAudio, DriftAudio from FdAudio (step 1800), and real reference audio for ten AudioCaps test clip IDs. Every generated sample in a row uses the displayed caption. The clip IDs were selected to match examples on the [FdAudio demo](https://fdoneaudio.github.io/); they were not selected by listening to DriftAudio outputs. See [`samples.json`](samples.json) for captions, file paths, and audio processing details.

These listening examples illustrate individual outputs; they are not the aggregate AudioCaps-877 evaluation. Real reference recordings originate from third-party source media. This repository's code or model licenses do not grant rights to reuse those recordings.
