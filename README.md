It is about "Exploration of the Correlation Factors of Stock Price Rise and Fall Based on the Fundamental Information,Trend and Market Sentiment".

The project include web crawling stock comment data from Eastmoney, doing sentiment classification using bert-base-chinese after fine-tune 
and using binary classification supervised model to predict.

You can also redo whole project by using posted data and model, but you should modify your environment and download the pre-trained 
bert-base-chinese model from huggingface and using gpu to train deep learning model.

Here is project overview, including sentiment classification part, feature engineering part and time series classification part.
<img width="1028" alt="截屏2024-08-01 上午12 30 58" src="https://github.com/user-attachments/assets/d9b08753-15d0-43df-8921-72d77b0e4036">

Here is sentiment classification model architecture, including Bert layer, BiLSTM layer and Attention layer.
<img width="1030" alt="截屏2024-08-01 上午12 31 31" src="https://github.com/user-attachments/assets/94f281da-4426-415b-8476-680643edf333">

Here is time series classification model architecture using CNN-LSTM, the key point is inception part.
<img width="1028" alt="截屏2024-08-01 上午12 31 50" src="https://github.com/user-attachments/assets/273d0abb-e7e0-448a-b0f1-43f4dd39e20c">

If you have some questions and suggestions, please contact me by wenxin0727@connect.hku.hk.
