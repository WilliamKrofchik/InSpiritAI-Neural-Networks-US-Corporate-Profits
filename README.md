# InSpiritAI-Neural-Networks-US-Corporate-Profits

## Using Neural Networks to Predict U.S. Corporate Profits on Electronic Goods, William Krofchik, November 3, 2023

## Project
This project was completed  for the 2023 InSpritAI Scholars Program.
* https://www.inspiritai.com

I collaborated with Ana Sofia Munoz Valadez who was my mentor for this project.
* https://www.linkedin.com/in/ana-sofia-mu%C3%B1oz-valadez-b01856195/

## Abstract
The 2018 trade war between the United States and China, COVID-19, supply chain disruptions, component costs, and consumer behavior have all created negative impacts on U.S. corporate profits on electronic goods. The goal of this project is to train a Neural Network AI model and a LSTM AI model to predict U.S. corporate profits on electronic goods into the future. We introduce 1) the datasets used for our model, 2) describe our Neural Network AI model and its corresponding results, 3) describe our LSTM AI model and its corresponding results, and finally 4) summarize our results and offer suggestions for future research into this area of study. Our hypothesis for the project was that even though there was a boost to U.S. corporate profits after COVID-19 due to re-opening of the economy and through government aid, these gains were completely offset by the much stronger factor of supply chain inefficiencies, thus bringing these profits down.  Our results show that supply chain inefficiencies have begun to abate worldwide and as they do, growth in corporate profits continues to stabilize to pre-pandemic levels.

## Final Paper Link

## Final Slide Deck Link

## Overview
This repository contains all models, datasets, and results from the project. For our Neural Network AI model, we implemented the scikit-learn toolkit for Python, specifically the MLPRegressor method. For our LSTM AI model we implemented the TensorFlow machine learning toolset for Python, specifically TensorFlow and Keras with the Sequential LSTM model. 

Below is the organization structure:

- `code/` folder containing all python code used in the project
  - Contains the single Python code file: `using_neural_networks_to_predict_u_s_corporate_profits_on_electronic_goods_william_krofchik.py`
  - Along with the associated Google Collab Notebook file: `Using_Neural_Networks_to_Predict_U_S_Corporate_Profits_on_Electronic_Goods_William_Krofchik.ipynb`
- `datasets/` folder containing all Excel datasets used in the project
- `results/` folder containing the final results graphs (JPG)

## Results

Our Regular Neural Network Model achieved 97.52% Accuracy Score and performed much better than our LSTM Model.

### Regular Neural Network Model Results
<b>97.52% Accuracy Score</b>

![Alt Text](https://github.com/WilliamKrofchik/InSpiritAI-Neural-Networks-US-Corporate-Profits/blob/main/results/NeuralNetworkResults.jpg)

### LSTM Model Results
<b>50.67% Accuracy Score </b>

![Alt Text](https://github.com/WilliamKrofchik/InSpiritAI-Neural-Networks-US-Corporate-Profits/blob/main/results/LSTMResults.jpg)


