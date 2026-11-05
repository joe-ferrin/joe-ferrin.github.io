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

Isolation Forest applied to engineered behavioral and structural features produced the most interpretable anomaly rankings during qualitative analysis. Highly ranked accounts frequently displayed unusual posting activity or interaction patterns.

Deep Graph Infomax identified additional structural anomalies, providing a complementary representation of user behavior.

An interactive D3.js network visualization was developed to explore anomalous accounts and their relationships.

Because ground-truth bot labels were unavailable, the results represent potentially anomalous behavior rather than confirmed automated accounts.

## Technologies

- **Python, pandas, NumPy:** Data processing and behavioral feature engineering.
- **NetworkX:** Graph construction and extraction of structural network features.
- **PyTorch, PyTorch Geometric:** Graph neural network implementation and representation learning using Deep Graph Infomax.
- **Scikit-learn:** Unsupervised anomaly detection using Isolation Forest.
- **JavaScript, D3.js:** Interactive network visualization and anomaly exploration.

## Project Materials

### Poster
🖼️ [Project poster (SVG)](/assets/images/reddit-bot-detection_poster.svg)

### Report
📄 [Project report (PDF)](/assets/reports/reddit-bot-detection_report.pdf)

### Visualization
📈 [Graph Demo (HTML)](/assets/visualization/network.html)

### Code
💻 [GitHub Repository](https://github.com/joe-ferrin/reddit-bot-detection)

