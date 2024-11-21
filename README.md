# Dyslexia Detection Project

This project is designed to detect dyslexia using machine learning and natural language processing (NLP). By analyzing handwriting samples, the system classifies letters, detects anomalies, and provides comprehensive reports to assist educators, researchers, and medical professionals.

---

## Key Features

- Handwriting Analysis:
  - Uses Convolutional Neural Networks (CNNs) to process handwritten characters.
  - Classifies characters as "Normal" or indicative of "Dyslexic Patterns."

- Text Sequence Analysis:
  - Leverages NLP techniques to detect anomalies in text sequences.
  - Assesses text flow to identify potential dyslexia markers.

- Multi-Layer Perceptron (MLP):
  - Adds an additional layer of classification support.
  - Enhances accuracy in detecting handwriting irregularities.

- Dynamic Report Generation:
  - Automatically creates PDF reports summarizing analysis results.
  - Includes detailed character detection and overall classification.

- Interactive Web Interface:
  - Upload handwriting images for analysis.
  - Real-time feedback and downloadable reports.

---

## Technologies Used

- Machine Learning:
  - CNN for image processing and feature extraction.
  - MLP for additional classification.
- Natural Language Processing (NLP):
  - Text sequence anomaly detection.
- Web Development:
  - Flask for backend services.
  - HTML, CSS, and JavaScript for the user interface.
- PDF Generation:
  - Automated detailed report creation.

---

## Dataset

The project uses a handwriting dataset with images categorized into:
1. Normal: Typical handwriting samples.
2. Reversed: Samples containing reversed letters.
3. Corrected: Handwriting corrected for dyslexic errors.

---

## How It Works

1. Image Input: Users upload handwriting images through the web interface.
2. Preprocessing: The system converts the image to binary format and segments it into individual characters.
3. Prediction:
   - CNN and MLP models classify characters.
   - NLP analyzes the text sequence for patterns and anomalies.
4. Report Generation: A detailed PDF is created summarizing the analysis, including character-level detection and sequence results.

---

## Applications

- Early detection of dyslexia in children and adults.
- Support for educators and therapists in creating personalized interventions.
- Research on handwriting and its link to learning disabilities.

---

## Installation and Usage

1. Clone the Repository:  
   ```bash
   git clone https://github.com/your-username/dyslexia-detection.git
