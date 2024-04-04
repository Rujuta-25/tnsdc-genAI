# Anomaly Detection in ECG Signals using Autoencoder Neural Network

## Overview
This project aims to develop a system for detecting anomalies in Electrocardiogram (ECG) signals using deep learning techniques, specifically an autoencoder neural network architecture. The project utilizes ECG data from the MIT-BIH Arrhythmia Database and implements an autoencoder model to identify anomalies in the ECG signals, which could indicate potential cardiac abnormalities.

## Features
- Preprocessing of ECG data to filter out non-beat symbols and categorize beats as normal or abnormal.
- Implementation of an autoencoder neural network architecture using TensorFlow and Keras.
- Training the autoencoder model on normal ECG signals and monitoring training/validation loss.
- Evaluation of model performance on both normal and anomalous ECG signals.
- Visualization of reconstruction results to identify anomalies in the ECG signals.

## Installation
1. Clone the repository:
     https://github.com/Rujuta-25/tnsdc-genAI/
2. Install dependencies



## Usage
1. Prepare ECG data:
- Obtain ECG signals in a compatible format (e.g., .csv, .mat) or use datasets such as the MIT-BIH Arrhythmia Database.
- Ensure that the data is preprocessed and formatted according to the project's requirements.

2. Training the model:
- Run the training script to train the autoencoder model on normal ECG signals:
  ```
  python train.py
  ```

3. Evaluate the model:
- Run the evaluation script to assess the model's performance on normal and anomalous ECG signals:
  ```
  python evaluate.py
  ```

4. Visualize results:
- Use the provided visualization scripts to visualize reconstruction results and identify anomalies in the ECG signals.

## Contributing
Contributions to the project are welcome! Feel free to open issues, submit pull requests, or suggest improvements. Please adhere to the project's code of conduct.

## License
This project is licensed under the MIT License.

## Acknowledgements
- This project was inspired by research in the field of cardiac anomaly detection using deep learning techniques.
- We acknowledge the creators and contributors of the MIT-BIH Arrhythmia Database for providing valuable datasets for research purposes.


