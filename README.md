COVID-19 Detection Using Convolutional Neural Networks (CNN) </br>

Overview</br>
This project aims to create an automated system for detecting COVID-19 from chest X-ray images using Convolutional Neural Networks (CNN). The model is trained to differentiate between COVID-19 infected lungs and normal lungs with high accuracy.
</br>
Features: </br>
Deep Learning Model: Utilizes a deep learning model built with Keras and TensorFlow. </br>
Model Architecture: The model architecture includes multiple convolutional layers, max-pooling layers, batch normalization, dropout layers, and dense layers to achieve optimal performance. </br>
Image Preprocessing: Preprocesses chest X-ray images to fit the model's input requirements. </br>
Prediction: Classifies new X-ray images into COVID-19 positive or normal categories. </br>
</br>
</br>
29_Covid19DetectionusingCNN/</br>
│</br>
├── TrainingDataset/</br>
│   ├── Covid/</br>
│   ├── Normal/</br>
│</br>
├── model.json</br>
├── model.h5</br>
├── main.py</br>
├── requirements.txt</br>
└── README.md</br>
Installation</br>
Clone the repository:</br>
git clone https://github.com/yourusername/29_Covid19DetectionusingCNN.git</br>
cd 29_Covid19DetectionusingCNN</br>
</br>
Install the required packages:</br>
pip install -r requirements.txt</br>
</br>
Usage</br>
Ensure you have the model files model.json and model.h5 in the project directory.</br>
</br>
Run the main script to classify X-ray images:</br>
python main.py</br>
</br>
How It Works:</br>
1. Loading the Model: The model is loaded from the saved JSON and H5 files.</br>
2. Image Preprocessing: The input X-ray image is preprocessed to fit the model's input size of 128x128 pixels.</br>
3. Prediction: The model predicts whether the input image is of a COVID-19 infected lung or a normal lung, displaying the result accordingly.</br>
</br>
Dependencies:</br>
1.Python 3.6+</br>
2.TensorFlow</br>
3.Keras</br>
4.NumPy</br>
5.Pillow</br>
6.Contributing</br>
</br>
Contributions are welcome! Please fork this repository and submit a pull request for any improvements or bug fixes.</br>
</br>
License</br>
This project is licensed under the MIT License. See the LICENSE file for details.</br>

