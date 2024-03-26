# FakeNewsPredict
A Machine Learning Project that is able to predict wheter a news is fake or not using pyton scikit-learn for model prediction

## Usage
Use ```main.ipynb``` to train the models using the datasets from `/data`.

After training your models, you can use the `Server.py` to initialize a Python server, there, you can pass the parameters for the prediction and wait for the server response.

The server is made with flask and to initialize it use: `python -m flask --app .\Server.py run`



