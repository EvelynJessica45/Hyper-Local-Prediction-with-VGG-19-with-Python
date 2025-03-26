# **Hyperlocal Weather Prediction Using VGG-19**

## **Overview**
This project leverages the VGG-19 deep learning model for hyperlocal weather prediction using high-frequency meteorological data. By applying transfer learning, the model captures intricate weather patterns and provides accurate short-term forecasts.

## **Features**
- Uses VGG-19 for weather prediction
- Processes high-resolution meteorological data
- Fine-tuned with transfer learning for optimal accuracy
- Supports applications in agriculture, disaster management, and urban planning

## **Installation**
1. Clone the repository:
   ```sh
   git clone https://github.com/EvelynJessica45/Hyper-Local-Prediction-with-VGG-19-with-Python.git
   cd Hyper-Local-Prediction-with-VGG-19-with-Python
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## **Usage**
1. Prepare and preprocess the dataset.
2. Train the VGG-19 model:
   ```sh
   python train.py
   ```
3. Evaluate the model:
   ```sh
   python evaluate.py
   ```
4. Make predictions:
   ```sh
   python predict.py --input data/sample_input.csv
   ```

## **Dataset**
The dataset consists of high-frequency weather parameters such as temperature, humidity, wind speed, and pressure. Ensure the data is preprocessed before training the model.

## **Model Training**
- The pre-trained VGG-19 model is modified by replacing the fully connected layers for weather prediction.
- The model is trained using an adaptive learning rate with optimizers like Adam.
- Performance is evaluated using Mean Absolute Error (MAE) and Root Mean Square Error (RMSE).

## **Results**
The VGG-19 model effectively captures hyperlocal weather patterns, improving predictive accuracy compared to traditional machine learning models.

## **My Contribution**
- Developed the data preprocessing pipeline.
- Fine-tuned VGG-19 for weather prediction.
- Evaluated and optimized model performance.

## **License**
This project is licensed under the MIT License.

## **Acknowledgments**
Special thanks to the open-source community and datasets used for training.

