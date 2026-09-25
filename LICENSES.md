# Third-party model notices

Nocturne Align Models redistributes or derives runtime assets from the following upstream projects.

## Khmer Wav2Vec2 acoustic model

- Project: `seanghay/wav2vec2-base-khmer-phonetisaurus`
- Runtime file: `wav2vec2-km-base-1500.onnx`
- License: CC BY 4.0
- Author: Seanghay Yath
- Source: https://huggingface.co/seanghay/wav2vec2-base-khmer-phonetisaurus

The FP32 model is redistributed unchanged. Attribution must be preserved.

## KFA assets

- Project: `seanghay/kfa`
- Runtime files: `g2p.fst`; source `lexicon.pkl` used to generate `lexicon.tsv`
- License: Apache License 2.0
- Source: https://github.com/seanghay/kfa

`lexicon.tsv` is a serialization-format conversion of the KFA lexicon for native mobile loading.

## KhmerCut Rust model

- Project: `seanghay/khmercut-rs`
- Runtime file: `khmercut.crfsuite`
- License: MIT
- Source: https://github.com/seanghay/khmercut-rs

Nocturne Studio also links open-source runtime code for Khmer segmentation and G2P. Their notices belong with the application source/binary notices rather than this model-only repository.
