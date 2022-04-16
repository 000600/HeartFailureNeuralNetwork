# Heart Failure Neural Network

## The Neural Network

The network is densely connected and  predicts the probability of one's heart failing. Since the dataset is categorical (the model predicts either 0 or 1 for a death event), the model uses a sparse categorical crossentropy loss function and has 2 output neurons. The model uses a standard Adam optimizer with a learning rate of 0.001. The model's architecture contains:
- 1 Batch Normalization Layer
- 1 Input Layer (with 512 input neurons)
- 3 Hidden Layers (2 with 256 neurons and 1 with 512; each with a ReLU activation function)
- 3 Batch Normalization Layers (one after each hidden layer)
- 1 Output Layer (with 2 output neurons)
- 1 Softmax Layer

Feel free to further tune the hyperparameters or build upon the model!

## The Dataset
The dataset can be found at this link: https://www.kaggle.com/andrewmvd/heart-failure-clinical-data. Credit for the dataset collection goes to **Larxel** on *Kaggle*. It describes the death event (0 or 1) of a patient based on 11 factors, inluding:
- Age
- Anaemia
- Creatinine Phosphokinase
- Diabetes
- Blood Pressure
- Platelets

## Libraries
This neural network was created with the help of the Tensorflow and Scikit-Learn libraries.
- Tensorflow's Website: https://www.tensorflow.org/
- Tensorflow Installation Instructions: https://www.tensorflow.org/install
- Scikit Learn's Website: https://scikit-learn.org/stable/
- Scikit Learn's Installation Instructions: https://scikit-learn.org/stable/install.html
