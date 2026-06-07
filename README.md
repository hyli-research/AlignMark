# Feature-Aligned Speech Watermarking for Robustness to Reconstruction Distortions

Official demo for **"Feature-Aligned Speech Watermarking for Robustness to Reconstruction Distortions"** (ICME 2026).

Authors: Haiyun Li, Shuhai Peng, Zhisheng Zhang, Jingran Xie, Xiaofeng Xie, Hanyang Peng, and Zhiyong Wu.

## Demo

Visit the [demo](https://hyli-research.github.io/AlignMark) to compare different audio watermarking methods.

## Abstract

Audio watermarking aims to embed identifiable information into audio while remaining imperceptible. Existing methods adopt high-fidelity, low-energy designs to preserve perceptual quality, but the resulting watermarks lack robustness under suppression by speech reconstruction models. Improving robustness is challenging due to the inherent robustness-fidelity trade-off in existing designs, where increasing watermark energy improves robustness but reduces fidelity.

To address this problem, we propose a feature-aligned watermarking method that aligns the watermark with the original speech feature distribution, allowing higher watermark energy to improve robustness while preserving imperceptibility. We use a pretrained speech codec to generate a pseudo-speech watermark and fuse it into the spectrogram of the input audio, with VAD loss and perceptual losses guiding embedding within voiced regions. Experiments show that our method maintains imperceptibility comparable to existing approaches while substantially improving robustness under both seen and unseen speech reconstruction models.

## Features

- Compare 6 watermarking methods side-by-side
- Audio samples from LibriSpeech, LJSpeech, and VCTK datasets
- Offline-friendly static demo page with local JavaScript and audio assets

## Contact

For questions, please contact Haiyun Li at <lihaiyun24@mails.tsinghua.edu.cn>.

## License

Please contact the authors for licensing and redistribution questions.
