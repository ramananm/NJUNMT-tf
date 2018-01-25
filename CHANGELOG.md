# Changelog
All notable changes to this project will be documented in this file.

## [Unreleased]

### Added
- Evaluation entrance (bin/eval.py).
- Cache for decoders (especially for TransformerDecoder).
- Change Log.


### Changed
- Tensorflow 1.4 requirement.
- Attention file format when output_attention flag is enabled with mode=INFER.
- BPE in ``Vocab`` accepts an extra vocab file (also see --vocabulary in njunmt/tools/apply_bpe.py).
- ``maximum_features_length`` and ``maximum_labels_length`` now indicate the length of encoded symbols (e.g. after BPE).
- More flexible and concise code structure of decoders.
- Attention classes.

### Removed
- ``input_prepose_processing_fn`` interface in decoders.

### Fixed
...


## 0.5.0 - 2018-01-09
### Added
- Transformer model.
- Model ensemble.
- Learning decaying functions.
- Evaluation metrics with loss or BLEU score (multi-bleu.perl).
- Beam search strategy with batch.
- Tensorboard visualization.
- Capability for BPE.
- Shell script to fetch WMT2014 en-de data.

### Changed
- More flexible and concise code structure.


## 0.1.0 - 2017-11
### Added
- Sequence-to-sequence model with attention.


[Unreleased]: https://github.com/zhaocq-nlp/NJUNMT-tf/compare/v0.5...master
