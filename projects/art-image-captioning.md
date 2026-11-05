# Emotion-Aware Art Caption Generation

## Overview
This project investigated deep learning approaches for generating captions for artwork that capture both semantic content and emotional or stylistic meaning. Unlike traditional image captioning tasks, the objective was to model subjective artistic interpretation in addition to visual recognition.

## Data
- Artwork images paired with human-written descriptions
  - 76,799 distinct painting images
  - 436,152 captions matched to those images
- Style and emotion annotations
- Viewer reaction and interpretation data

## Approach

- Implemented image captioning architectures using a pretrained ResNet-50 image encoder and LSTM and Transformer decoders.
- Used the ArtEmis and Wikiart datasets, containing artwork images paired with human-written descriptions and emotion annotations.
- Explored style and emotion representations and contrastive learning approaches for modeling subjective artistic interpretation.
- Trained and evaluated a Transformer-based captioning model, using multiple reference captions for evaluation.

## Results

The models generated artwork descriptions capturing visual content and, in some cases, emotional interpretation. However, generated captions could also be generic or inaccurate, highlighting the challenges of subjective artwork interpretation.

The project investigated the effectiveness and limitations of deep learning architectures for art caption generation.

## Technologies

- **Python, PyTorch:** Deep learning model development, training, and evaluation.
- **ResNet-50:** Pretrained CNN used to extract visual features from artwork.
- **LSTM and Transformer architectures:** Sequence decoders implemented for image caption generation.
- **Natural Language Processing (NLP):** Text preprocessing, tokenization, and caption generation.
- **Contrastive Learning:** Explored style and emotion representations for capturing subjective artistic interpretation.

## Project Materials

### Report
📄 [Project report (PDF)](../assets/reports/art-image-captioning_report.pdf)

### Code
💻 [GitHub Repository](https://github.com/joe-ferrin/emotion-aware-art-captioning)
