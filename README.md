# PyTorch Flask API

This repo contains a sample code to show how to create a API server by deploying PyTorch model. This project is inspired by [tutorial](https://pytorch.org/tutorials/intermediate/flask_rest_api_tutorial.html).


## How to 

Install the dependencies:

    pip install -r requirements.txt


Run the Flask server:

    FLASK_ENV=development FLASK_APP=app.py flask run


From another tab, send the image file in a request:

    curl -X POST -F file=@cat_pic.jpeg http://localhost:5000/predict


## License

The mighty MIT license. Please check `LICENSE` for more details.
