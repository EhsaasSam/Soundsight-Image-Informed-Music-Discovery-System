This project aims to create a personalized music recommendation system that analyzes facial expressions from images to detect emotions and recommends music tracks that correspond to these detected emotions. The system leverages Convolutional Neural Networks (CNNs) for emotion detection and clustering algorithms for music recommendation. It enhances user experience by aligning music choices with the user's current emotional state.

**Key Features**

1. Emotion Detection: Uses a CNN model trained on the FER2013 dataset to classify facial expressions into emotions.
2. Music Recommendation: Clusters music tracks based on features like danceability, energy, and valence to match detected emotions.
3. Data Augmentation: Employs data augmentation techniques to improve model robustness.
4. Real-Time Analysis: Processes images in real-time to provide immediate music recommendations.

**Technologies Used**

1. Python
2. TensorFlow/Keras
3. OpenCV
4. Scikit-learn
5. Pandas

**How to Use**

**1. Upload an Image:** Provide an image with a clear view of the face.
**2. Emotion Detection:** The system analyzes the image to detect emotions.
**3. Music Recommendation:** Based on the detected emotions, the system recommends a list of music tracks.

Explore the repository to find detailed implementation steps, code, and additional documentation.
