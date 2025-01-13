# AI-Powered Personality and Mental Wellness Tracker

## Overview
This project aims to develop an **AI-driven Personality and Mental Wellness Tracker** that:
- Assesses personality traits using **Big Five Personality Traits** and **MBTI** frameworks.
- Detects **mental health conditions** such as **stress, anxiety, and depression**.
- Provides **real-time insights** for **employers, clinicians, and individuals**.
- Suggests **personalized treatment recommendations** (e.g., therapy, mindfulness exercises, exercise routines).
- Uses **wearable devices** to track biometric data for continuous monitoring.
- Ensures **privacy, consent management, and anonymous usage options**.

## Features
### 1. **Personality Assessment**
- Uses **Big Five Personality Traits** and **MBTI** frameworks.
- Analyzes data from:
  - **Speech** (tone, pitch, cadence).
  - **Facial expressions** (micro-expressions, emotional analysis).
  - **Written text** (word choices, sentiment analysis).

### 2. **Mental Health Detection**
- Identifies **stress, anxiety, depression** through:
  - **Speech Analysis** (monotone voice → depression, fast speech → anxiety).
  - **Facial Micro-Expressions** (subtle frowns, lip biting → stress).
  - **Text-Based Sentiment Analysis** (negative keywords indicating distress).

### 3. **Iris Dilation-Based Stress & Lie Detection**
- Tracks **iris dilation** to assess:
  - **Stress Levels**
  - **Deception (Lie Detection)**
  - **Cognitive Load**
- Uses **computer vision (OpenCV, Mediapipe, CNN models)** to analyze pupil variations.

### 4. **Real-Time Monitoring with Wearable Devices**
- Tracks:
  - **Heart Rate Variability (HRV)**
  - **Skin Conductance (EDA - Electrodermal Activity)**
  - **Sleep Patterns**
- Provides **alerts** for **mood changes** or mental health crises.

### 5. **Customizable Dashboards**
- **Employers**: Evaluate personality and emotional stability.
- **Clinicians**: Use data-driven insights for therapy planning.
- **Individuals**: Get personalized well-being insights and recommendations.

### 6. **Privacy and Consent Management**
- Ensures **explicit user consent** before data collection.
- Provides **anonymous mode** for sensitive environments.
- Implements **strong data security & encryption**.

## Technologies Used
- **AI & Machine Learning**: Deep Learning (CNNs, RNNs/LSTMs), NLP (Sentiment Analysis)
- **Computer Vision**: OpenCV, Mediapipe, Dlib
- **Wearable Device Integration**: Smartwatches, Biometric Sensors
- **Data Visualization**: Dashboards using React.js, D3.js
- **Cloud & Security**: Encrypted Data Storage, Privacy Protection Measures

## Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/mental-wellness-tracker.git
   cd mental-wellness-tracker
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt  # For backend
   npm install  # If using a frontend
   ```
3. Run the application:
   ```sh
   python app.py  # Backend
   npm start  # Frontend
   ```

## Contribution
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`feature-xyz`).
3. Commit your changes.
4. Submit a Pull Request.

## License
This project is licensed under the **MIT License**.

## Contact
For inquiries or collaboration, contact **your-email@example.com** or open an issue in the repository.

