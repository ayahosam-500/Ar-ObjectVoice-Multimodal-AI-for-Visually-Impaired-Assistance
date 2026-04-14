AI Assistant for Object Detection & Verbal Description
Overview
An AI-powered assistant designed to support the visually impaired by identifying objects in their environment and announcing them in Arabic. This project integrates Computer Vision (Faster R-CNN) with Natural Language Processing (gTTS) to bridge the gap between visual data and auditory feedback.

Key Features
Precise Detection: Powered by Faster R-CNN Inception ResNet V2 for high-accuracy object localization.

Multimodal System: Combines image processing with automated speech generation.

Arabic Localization: Translates detected labels into Arabic and generates natural-sounding voice alerts.

Confidence Filtering: Implements a confidence threshold (>30%) to ensure reliability in real-world scenarios.

Tech Stack
Framework: TensorFlow & TensorFlow Hub.

Image Processing: PIL (Pillow), NumPy.

Visualization: Matplotlib & Patches.

Speech Synthesis: gTTS (Google Text-to-Speech).
How it Works
Preprocessing: Resizes and normalizes input images for the model.

Detection: Extracts bounding boxes, labels, and scores.

Translation: Maps English labels (e.g., "Dog") to Arabic equivalents (e.g., "كلب").

Speech Output: Converts the translated text into an .mp3 file for immediate playback.
![Project Result](195083_result.jpg)
<img width="932" height="653" alt="image" src="https://github.com/user-attachments/assets/60bcf028-d4fd-4612-85d2-1a496aa8a12d" />
