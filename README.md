# Forecast Time Series
<img src="data\BostonCity_ExploratoryAnalysis.jpg">

 Project involves applying different kind of forecasting models

 This project aims to summarize some forecast models, such as :

 - **LSTM (Long-Short Term Memory)**
 LSTM is a type of Recurrent Neural Network (RNN) designed to learn long-term dependencies in sequential data. It addresses the vanishing gradient problem common in traditional RNNs, making it suitable for time series forecasting.

 - **GRU (Gated Recurrent Unit)**
 GRU is similar to LSTM but with a simpler architecture and fewer parameters, making it faster and often as effective. It uses gating mechanisms to manage information flow without separate memory cells.

 - **TCN (Temporal Convolution Network)**
 TCN uses dilated causal convolutions to handle sequential data, providing an alternative to RNNs. TCNs maintain long memory and are parallelizable, making them efficient for training.

 - **CNN (Convolutional Neuronal Network)**
 Originally developed for image processing, CNNs can be adapted for time series forecasting by treating the sequence as a one-dimensional input. Convolutions help detect patterns over time.

 - **MLP (Multi-Layer Perceptron)**
MLP is a class of feedforward neural networks consisting of multiple layers of neurons. Although not inherently designed for sequential data, it can be applied to time series forecasting with proper input preprocessing.

Some considerations:
-   Performance: LSTM and GRU excel at capturing long-term dependencies, whereas CNNs and TCNs are often faster due to their parallel nature.
-   Computational Efficiency: GRU and TCN tend to be more computationally efficient compared to LSTM.
-   Ease of Use: MLPs are simpler to implement but may require more feature engineering for time series tasks.

 In the end, there will be a brief comparison between models.
 
 Note: I have been working on updating libraries and function; however, I devoloped this project a long time ago.
