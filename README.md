# EBM-TextTranscribe

**Overview**  
This repository implements an energy-based model for word image transcription. The system uses a fully convolutional network to produce an energy matrix over sliding windows, then finds the best alignment with a Viterbi algorithm. The project covers:
- Synthetic dataset generation for word images.
- Per-character pre-training.
- Sequence-level training with dynamic programming loss.
