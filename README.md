## LSTM Text Generation Model with Anvil Integration
This GitHub project showcases an LSTM (Long Short-Term Memory) neural network designed for text generation. The project encompasses the following functionalities:

### Key Features:

1. Text Data Processing: Utilizes Pandas to preprocess text data from a CSV file containing news articles. Tokenization and sequence preparation for training an LSTM model are done using NLTK's RegexpTokenizer.
2. Model Training and Visualization: Implements an LSTM neural network architecture using Keras/TensorFlow. Trains the model on the preprocessed data and visualizes the training history through accuracy and loss graphs using Matplotlib.
3. Next Word Prediction: Provides a function to predict the next probable words in a sequence based on the trained LSTM model. The prediction function takes user input and returns the top 5 predicted words with their associated weights.
4. Anvil Server Integration: Integrates with Anvil, allowing the prediction function to be served remotely. Establishes a connection to the Anvil server, making the prediction function callable through the Anvil platform.

### How to Use:

### Setup : 
1. Clone the repository
2. Put the ipynb file in google colab
3. Put the mymodel.h5 and Data_berita.csv in the root of your gdrive
4. Run the ipynb file in google colab
5. Open the anvil link

### Repository Structure:

1. model_training.ipynb: Jupyter Notebook containing the code for data preprocessing, model training, and visualization.
2. prediction_function.py: Python script containing the function for next word prediction and Anvil server integration.
3. Data_berita.csv: Sample dataset (news articles) used for model training.
4. mymodel.h5: Pre-trained LSTM model for text prediction.
