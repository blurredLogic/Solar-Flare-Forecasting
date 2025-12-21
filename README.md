# Solar-Flare-Prediction
Using machine learning and data science, this project is using solar data obtained publicly to predict the class of a solar flare as they happen on Sol


Data for this project can be found here: https://drive.google.com/drive/folders/1ZIGNgBmsaFaN4IuyXvtmb8h_ToCHPIZW?usp=sharing

The data exists in a .rar file. To use the data, please extract the folders within and place it in the same directory as the Python notebook. If needed, please do change the location specified in the code to point it to the correct location of the data.


To use this project, make sure to set up and run multiyear_models.CNN.ipynb as this notebook contains the code to preprocess and transform the data into the multi-year dataset that will be used to train anf evaluate the models. The aforementioned notebook contains only the CNN model. The other notebook, multiyear_models_RNN_LSTM_GRU.ipynb, contains the model code for RNN, LSTM and GRU.
