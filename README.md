# Sunspot-Prediction-Using-GRU
Understanding and predicting solar activity, such as sunspot counts, is crucial for various scientific and practical applications, including space weather forecasting and its impact on Earth's climate. In this project, we delve into the realm of time series prediction using cutting-edge neural network architectures, specifically Gated Recurrent Unit (GRU) and 1D Convolutional Neural Network (Conv1D) layers, to forecast sunspot activity.

## Dataset
The dataset consists of daily sunspot counts gathered from the World Data Center SILSO, Royal Observatory of Belgium, Brussels. This dataset offers a comprehensive record of sunspot numbers, meticulously collected and processed, eliminating any missing values for robust analysis and prediction. The data spans from January 1850 to April 2024, providing a comprehensive view of sunspot activity over a significant period. Dataset [link](https://www.kaggle.com/datasets/patrickfleith/daily-sunspots-dataset)

For this project, the dataset was preprocessed to include only the columns needed for forcasting, the date, and the average sunspot number, resulting in 2092 non-null records.

## Project Objectives
- Data Exploration and Visualization: started by exploring the dataset, visualizing the temporal patterns of sunspot activity, and identifying any underlying trends or anomalies.

- Data Preparation: The dataset is preprocessed and formatted to facilitate training neural networks. Segmented the time series data into windows, preparing it for input into the GRU and Conv1D layers.

- Model Building: The neural network architecture combines Conv1D and GRU layers to capture both short-term patterns and long-term dependencies in the sunspot time series data.

- Learning Rate Optimization: Employed learning rate scheduling techniques to find the optimal learning rate for training the neural network, ensuring efficient convergence and improved performance.

- Model Training and Evaluation: The neural network model is trained on the preprocessed data, and its performance is evaluated using standard metrics such as Mean Absolute Error (MAE) on a validation dataset.

## Results
The model's performance is visualized through plots of MAE and loss over epochs, as well as a comparison between the predicted and actual sunspot numbers. The MAE on the validation data provides a quantitative measure of the model's prediction accuracy.

