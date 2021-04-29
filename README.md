# YelpSense API

An API for sentiment analysis of Yelp reviews. Uses a Transformers model trained on reviews in the Yelp Academic Dataset.

# Running locally

Clone the repo:

```git clone <URL>```

In the project directory, create a .env file with the following environment variables:

```
FLASK_APP=api:APP 
```

Create a virtual environment and install the required dependencies with:

```
python -m venv virt
pip install -r requirements.txt
```

Start the dashboard with the following command:

```
flask run
```