# CodecFake: Enhancing Anti-Spoofing Models Against Deepfake Audios from Codec-Based Speech Synthesis Systems

<p align="center">  
    <a href="https://arxiv.org/abs/2406.07237">Paper</a>,
    <a href="https://huggingface.co/datasets/rogertseng/CodecFake">Dataset</a>,
    <a href="https://codecfake.github.io/">Project Page</a>
</p>
<p align="center">  
    <i>Interspeech 2024</i>
</p>

**TL;DR**: We show that better detection of deepfake speech from codec-based TTS systems can be achieved by training models on speech re-synthesized with neural audio codecs.
We also release the CodecFake dataset for this purpose.

## Dataset Download

We provide the CodecFake dataset in two forms:
1. [**Huggingface Datasets**](https://huggingface.co/datasets/rogertseng/CodecFake)

    ```python
    from datasets import load_dataset
    a = load_dataset("rogertseng/CodecFake")
    ```

2. [**ZIP files**](https://huggingface.co/datasets/rogertseng/CodecFake_wavs/tree/main)

## Train Fake Speech Detectors on CodecFake

See instructions under [detection](https://github.com/roger-tseng/CodecDetect) for more.

## Dataset Creation Pipeline

TBA, see [dataset_creation](https://github.com/roger-tseng/AudioDecBenchmark)

## Acknowledgement

CodecFake is created based on the [VCTK](https://datashare.ed.ac.uk/handle/10283/3443) dataset, licensed under CC-BY-4.0.

