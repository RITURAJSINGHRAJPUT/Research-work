# **Sign Language to Text Conversion System**

## **Project Overview**  
This project aims to bridge the communication gap between individuals with hearing or speech impairments and the general population by converting sign language gestures into text. The system leverages computer vision and deep learning techniques to recognize hand gestures and translate them into meaningful text outputs. It focuses on real-time recognition of Indian Sign Language (ISL) using MediaPipe for keypoint detection and Long Short-Term Memory (LSTM) networks for gesture-to-text conversion.

---

## **Features**
- Real-time recognition of hand gestures using a webcam.
- Conversion of recognized gestures into text.
- Focused on Indian Sign Language (ISL).
- Efficient and cost-effective solution without the need for specialized hardware.
- User-friendly interface for ease of use.

---

## **Technologies Used**
1. **Computer Vision**: MediaPipe for hand and finger keypoint detection.  
2. **Deep Learning**: LSTM neural networks for sequential gesture recognition.  
3. **Programming Languages**: Python.  
4. **Libraries and Frameworks**:  
   - TensorFlow/Keras  
   - OpenCV  
   - MediaPipe  

---

## **System Workflow**
1. **Input**: The system captures hand gestures using a webcam.  
2. **Key Point Detection**: MediaPipe detects and extracts hand keypoints (landmarks).  
3. **Data Preprocessing**: Keypoint data is normalized and preprocessed to remove noise.  
4. **Gesture Recognition**: The preprocessed data is passed to an LSTM model to identify the gesture.  
5. **Text Conversion**: Recognized gestures are mapped to their corresponding textual representation.  
6. **Output**: The translated text is displayed in real time.

---

## **Setup Instructions**
### **Prerequisites**
- Python 3.8 or higher.  
- Webcam-enabled computer or external webcam.  
- Install required libraries using `pip`.  

### **Installation**
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-repo/sign-language-to-text.git
   cd sign-language-to-text
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:  
   ```bash
   python main.py
   ```

---

## **Usage**
1. Ensure your webcam is properly connected.  
2. Run the program.  
3. Position your hand in front of the camera, ensuring good lighting and minimal background clutter.  
4. Perform gestures corresponding to Indian Sign Language.  
5. The recognized text will be displayed in real-time on the screen.

---

## **Dataset**
The system uses a custom dataset of ISL gestures, captured using MediaPipe keypoints. Data augmentation techniques have been applied to enhance model robustness. You can add new gestures by updating the dataset and retraining the model.

---

## **Challenges Addressed**
- Variability in hand movements and gestures.  
- Differences in skin tones and lighting conditions.  
- Real
