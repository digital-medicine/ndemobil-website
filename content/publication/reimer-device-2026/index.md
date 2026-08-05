---
title: On-Device Transformer Architectures for Speech Evaluation in Neurodegenerative
  Disease Detection
authors:
- Lara Marie Reimer
- Leonard Pries
- Florian Schweizer
- Leon Nissen
- Stephan M. Jonas
date: '2026-05-01'
publishDate: '2026-08-05T14:38:18.822054Z'
publication_types:
- article-journal
publication: '*Computers*'
doi: 10.3390/computers15050287
abstract: Speech alterations are early markers of neurodegenerative diseases. Transformer-based
  speech models such as Whisper have advanced automated speech assessment, but most
  systems rely on cloud-based computation, raising privacy concerns. On-device processing
  could offer a scalable and privacy-preserving alternative. This research’s objective
  was to evaluate whether a fully on-device speech analysis pipeline can achieve competitive
  accuracy in detecting Alzheimer’s disease and to quantify the contributions of acoustic,
  linguistic, and embedding features. Therefore, we developed an iOS application running
  all components, including acoustic analysis, two transformer-based speech-to-text
  modules (WhisperBase and quantized CrisperWhisper), linguistic feature extraction,
  and embedding generation, directly on the device. Using the ADReSS Challenge 2020
  dataset (N = 156), we trained classical machine-learning classifiers across 20 configurations
  and evaluated them via a stratified 10-fold cross-validation. Area under the receiver
  operating curve (AUC), accuracy, precision, recall, and F1 scores were used as performance
  metrics. An ablation study examined the relevance of each feature group. The best-performing
  setup (Random Forest with CrisperWhisper transcription and Apple embeddings) achieved
  an accuracy of 85.4% and an AUC of 0.85. Performance was 5–7% below benchmark models
  relying on manual transcripts or server-based processing. Embedding features provided
  the strongest individual contribution, but the highest accuracy required combining
  acoustic, linguistic, and embedding information. A fully on-device pipeline for
  Alzheimer’s disease detection from speech is feasible and achieves competitive accuracy
  while maintaining strict data privacy. These findings highlight the potential of
  on-device transformer architectures for scalable, privacy-preserving digital screening.
  Future work should validate the approach in larger and more diverse cohorts.
links:
- name: URL
  url: https://www.mdpi.com/2073-431X/15/5/287
---
