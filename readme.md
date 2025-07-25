# Crop Disease Classification

An AI-powered web application that detects crop diseases using deep learning

## Features

- **Crop Disease Detection:** Utilizes a CNN model to classify diseases in potato crops with 88% accuracy.
- **User-friendly Interface:** Built with **Flask** for easy image upload and real-time disease classification.
- **Deep Learning Model:** Trained a CNN using **TensorFlow** and **Keras** for high-accuracy classification.

## Tech Stack

- **Deep Learning:** TensorFlow, Keras
- **Backend:** Flask
- **Data Processing:** OpenCV, NumPy, Pandas

## Installation & Setup

### Prerequisites

- Python 3.x
- pip

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/crop-disease-classification.git
   cd crop-disease-classification
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Flask web application:
   ```sh
   python app.py
   ```

## Usage

1. Open the web application in your browser.
2. Upload an image of the affected crop.
3. The system predicts the disease.

## Dataset

The model was trained on:

- **Potato crop disease dataset** with labeled images.
- **Data preprocessing and augmentation** were performed using OpenCV and NumPy.

## Model Details

- **Algorithm:** Convolutional Neural Network (CNN)
- **Training Library:** TensorFlow, Keras
- **Feature Engineering:** Image preprocessing and augmentation

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
