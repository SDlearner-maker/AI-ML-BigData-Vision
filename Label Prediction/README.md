## Music Genre Classification Project  
- **Objective:** Developed and implemented neural network models to classify music data into three genres: classical, jazz, and 
metal.    
- **Task 1:** Utilized an Artificial Neural Network (ANN) to handle 1D music features, specifically 20 Mel-frequency cepstral coefficients (MFCC) with added random noise. The ANN, configured with 7 layers and RELU activation, achieved an accuracy of 80% with a training time of 1.9 seconds. Optimal results were obtained with 800 epochs, demonstrating the 
model’s ability to manage noisy audio features effectively. 
- **Task 2:** Implemented a Recurrent Neural Network (RNN) with Long Short-Term Memory (LSTM) units for classifying 2D audio data, represented as 10x10 Short-Time Fourier Transform (STFT) features. The RNN model, 
using RELU activation, achieved a high accuracy of 93.33% with a training time of 24 seconds. The optimal performance was observed with 45 epochs and 64 hidden units, showcasing the RNN's proficiency in handling complex 2D audio data.  
- **Conclusion:** Overall, the project highlighted the effectiveness of both ANN and RNN architectures in classifying music genres, 
with improvements suggested for further enhancing model performance through additional neural network designs 
and hyperparameter tuning.
- **Navigating files:**  
  - **test_task1.ipynb:** This Jupyter Notebook contains the program of *Task 1* which is explained above.
  - **test_task2.ipynb:** This Jupyter Notebook contains the program of *Task 2* which is explained above.
  - **Final Project Report_SwetaDas_18080395d.docx:** This document contains all details of the project, the reasons of choosing a certain model, the features of the dataset, the results and the possible improvements.