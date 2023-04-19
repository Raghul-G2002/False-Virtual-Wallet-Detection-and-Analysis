# False-Virtual-Wallet-Detection-and-Analysis
This project aims to detect 11 types of false Crypto keys using LSTM and Conjugated LSTM models. The models were trained on a large dataset of Crypto keys, and the results showed that the LSTM model achieved a final accuracy of 90%, while the Conjugated LSTM model had an accuracy of 86%, which is better than other models suggested.

The models were also used to forecast the future volume of Crypto transactions. The results showed that both LSTM and Conjugated LSTM models were able to accurately predict the future volume of Crypto transactions, based on historical data.

Overall, this project demonstrates the effectiveness of using LSTM and Conjugated LSTM models for detecting false Crypto keys and forecasting future Crypto transaction volumes. The findings of this project can be useful in improving the security of Crypto transactions and making better decisions regarding future Crypto investments.

## Architecture Diagram: False Key Analysis
![image](https://user-images.githubusercontent.com/83855692/224467866-3878453c-b11f-4995-9df1-bcde7b4c01da.png)

## Architecture Diagram: Virtual / Electronic Asset Analysis
![image](https://user-images.githubusercontent.com/83855692/224467881-2d27f18f-146c-4cb3-aa93-dee74584b09c.png)

# Results
The final Comparitive Results is shown in below table

| Evaluation Metrics | MAE | MSE | MAPE | MRE | RMSE | R2 Score |
| -------------------|-----|-----|------|-----|------|----------|
| XGBoost Regressor | 2.7962 | 79.027 | 21376.138 | 0.0290 | 8.88975 | 0.9963 |
| LSTM 	| 32.5534 | 5124.4740 | 700714.59 | 0.78012 | 71.5854 | 0.76322 |
| Conjugated LSTM with RNN | 33.8529 | 5618.1730 | 296144.242 | 0.81986 | 74.9544 | 0.74045 |
| Conjugated LSTM with Bi-directional RNN | 52.3152 | 18886.07 | 203681.2 | 0.6565 | 137.4266 | 0.12737 |
| Conjugated LSTM with CNN | 21.5005 | 2869.269 | 102855.467 | 0.42172 | 53.5655 | 0.90331 |

![result1](https://user-images.githubusercontent.com/83855692/233098523-48daf062-2802-4c62-92ba-af7ac8e49abf.png)
![result2](https://user-images.githubusercontent.com/83855692/233098592-91059001-1299-414e-8cfb-a02cdcd1eed2.png)
![result3](https://user-images.githubusercontent.com/83855692/233098646-7402a94b-01e7-48d9-85fa-561fa047b491.png)
![result4](https://user-images.githubusercontent.com/83855692/233098677-066c9c89-d59e-4687-8839-84e6156cb644.png)
![result5](https://user-images.githubusercontent.com/83855692/233098702-8d81adfd-a29e-474d-8081-9a698777f027.png)
![result6](https://user-images.githubusercontent.com/83855692/233098420-15e5c7a6-9b14-4521-a1d3-b928c8dbb812.png)


# Requirements
## SOFTWARE REQUIREMENTS
1. Deep learning frameworks: TensorFlow, Keras, 
2. GPU support: LSTMs and CLSTMs are computationally intensive and can benefit from GPU acceleration. Therefore, the software must have support for GPUs, either through the deep learning framework or the hardware.
3. Data pre-processing tools: NumPy, Pandas, and Scikit-learn, 
4. Evaluation metrics: Scikit-learn
5. Development environment: Jupyter Notebook, VS Code

## HARDWARE REQUIREMENTS
1. Processor: GPU or a specialized hardware accelerator such as a TPU.
2. Memory: The amount of memory required depends on the size of the model, the batch size used during training, and the size of the input data.
3. Storage: The size of the input data and the model parameters can be large, so sufficient storage is required to store these data. Additionally, it is important to have a backup and version control system for the data and models.
4. Network: A high-speed network connection is required to communicate between the machines.

## LANGUAGE SPECIFICATION
- Python Version: Deep learning frameworks and libraries support Python versions 3.5
- Keras: Version 3.5 – 3.8
- Tensorflow: Version 3.5 – 3.9
