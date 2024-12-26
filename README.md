
# Age, Gender, and Ethnicity Prediction  

This repository contains a deep learning-based application designed to predict **age**, **gender**, and **ethnicity** from facial images. The model leverages advanced custom-built transformers to achieve high accuracy in real-time demographic classification.

## Features  
- **Age Prediction**: Accurately estimates the age of a person from a facial image.  
- **Gender Detection**: Identifies whether the subject is male or female.  
- **Ethnicity Classification**: Classifies individuals into various ethnicity categories based on facial features.  
- **Real-Time Inference**: Supports real-time predictions on live or uploaded images.  

## How It Works  
1. **Image Input**: Upload a facial image or provide real-time input via a connected camera.  
2. **Feature Extraction**: The model extracts relevant features from the image using deep learning techniques.  
3. **Prediction**: The custom transformer-based model predicts age, gender, and ethnicity.  
4. **Results**: Displays predictions in a user-friendly format.  

## Requirements  
- Python 3.8+  
- Libraries:  
  - `tensorflow`  
  - `keras`  
  - `opencv-python`  
  - `numpy`  
  - `matplotlib`  

## Setup Instructions  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/janakiram180/Age-Gender-and-Ethinicity-Prediction.git  
   cd Age-Gender-and-Ethinicity-Prediction  
   ```  
2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Download the pretrained model weights:  
   - Add the model weights to the appropriate directory (details provided in the repository).  

4. Run the application:  
   ```bash  
   python app.py  
   ```  

## Usage  
- **Image Upload**: Provide an image file for analysis.  
- **Real-Time Mode**: Use a camera to capture live input for predictions.  
- The application will output the predicted age, gender, and ethnicity.  

## Technologies Used  
- **TensorFlow/Keras**: For model development and training.  
- **Custom Transformers**: Designed for enhanced feature extraction and classification.  
- **OpenCV**: For image preprocessing and real-time camera input handling.  

## Dataset  
The model is trained on publicly available datasets containing diverse facial images annotated with age, gender, and ethnicity.  

## Future Enhancements  
- Extend model capabilities to handle low-resolution images.  
- Add support for multi-ethnicity predictions.  
- Optimize for deployment on edge devices.  

## License  
This project is licensed under the MIT License. See the `LICENSE` file for more details.  

---

