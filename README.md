# sentiment-api-python-gpt3


## Create Python 3 environment

pip install -r requirements.txt

## Set environment variable 

export OPENAI_API_KEY=sk-XXXXXXXXXX

## Run API

python sentiment-api.py

## Consume via cURL or Postman etc

`curl -X POST -H "Content-Type:application/json" -d '{"text":"I love the product"}' localhost:8080/sentiment`

> {"sentiment": "positive"

