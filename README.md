# Deception-Detection-via-Acoustic-Prosodic-Cues-with-Maximized-Dataset-Utilization

## Overview

This project implements a method for detecting deception in speech by leveraging acoustic and prosodic cues. The approach focuses on maximizing dataset utilization to improve performance and generalizability. Thee data

## Features
- Dataset Preprocessing: Efficient handling and preprocessing of audio data for analysis.

- Feature Extraction: Extraction of acoustic and prosodic features from speech samples.

- Machine Learning Models: Implementation of various classifiers to detect deceptive speech.

- Evaluation Metrics: Performance evaluation using metrics such as accuracy, precision, recall, and F1-score.

## Summary of Dataset Maximization

1) Audio Segmentation:

Long audio files are divided into smaller, meaningful chunks (e.g., by pauses or time intervals) to treat each segment as an independent sample.
Tools like Voice Activity Detection (VAD) ensure segments align with natural speech boundaries.
Advantages: Reduces noise, enhances feature quality, and focuses on granular speech units.

2) Selective Feature Extraction:

Acoustic Features: Extract MFCCs, chroma features, and spectral contrast.
Prosodic Features: Capture pitch, intensity, and rhythm.
Temporal Features: Include duration and timing patterns.
Methods like PCA or feature importance are used to retain impactful features.

3) Combining Features:

Features are concatenated or fused (e.g., MFCC with pitch) to leverage their strengths.
Aggregating features from overlapping segments preserves context and temporal dependencies.

4) Maximization Strategy:

Handling Redundancy: Overlapping segments ensure no critical information is missed.
Expanding Dataset: Segmentation creates more samples, improving generalization.

### Advantages: Increases dataset size, captures nuanced cues, and preserves context for improved model performance.

