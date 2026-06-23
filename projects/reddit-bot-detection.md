# Reddit Bot Detection

## Overview
This project explored unsupervised anomaly detection methods for identifying automated and coordinated behavior in Reddit interaction networks. The system was designed to detect suspicious accounts without relying on labeled training data.

## Data
- Large-scale Reddit comment interaction network
- User activity and graph-structure features
- Sparse, highly imbalanced graph data

## Approach
- Constructed user interaction graphs from Reddit comment data
- Engineered behavioral and structural features associated with automated activity
- Implemented:
  - Isolation Forest
  - Graph embedding methods
  - Deep Graph Infomax for unsupervised representation learning
- Developed an interactive anomaly exploration dashboard using D3.js

## Results
The model identified clusters of anomalous users exhibiting:
- Highly repetitive interaction behavior
- Unusual graph connectivity patterns
- Coordinated or bot-like activity signatures

## Technologies
- Python
- PyTorch
- NetworkX
- Scikit-learn
- JavaScript
- D3.js

## Project Materials

### Poster
🖼️ [Project poster (SVG)](../assets/images/reddit-bot-detection_poster.svg)

### Report
📄 [Project report (PDF)](../assets/reports/reddit-bot-detection_report.pdf)

### Code
💻 [GitHub Repository (request access)](https://github.com/joe-ferrin/reddit-bot-detection)

