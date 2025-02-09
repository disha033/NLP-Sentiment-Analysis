# **TWITTER SENTIMENTAL ANALYSIS**
### _This project implements a sentiment analysis application using machine learning & NLP and provides a user interface with Streamlit._

**SETUP**
----
1.Clone this repository.

2.Install the required packages:

```PYTHON
pip install -r requirements.txt
```
3.Place your `twitter_training (1).csv` and `twitter_validation.csv` files in the `data/` directory.

## USAGE

1.Train the models:
```python
python src/sentiment_analysis.ipynb
```
2.Run the streamlit app:
```python
streamlit run app.py
```
3.Open your web browser and go to the URL provided by Streamlit (usually `http://localhost:8503`)
## PROJECT STRUCTURE
* `data/` : Contains the training and validation datasets.
* `src/` : Contains the source code for model training and prediction.
* `models/` :  Stores the trained models and vectorizers. 
* `app.py` : The main Streamlit application.
* `requirements.txt` : List of Python dependencies.
## APPLICATION
![alt text](<Screenshot (4).png>)