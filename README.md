## Team
Shreesha Bharadwaj (181CO249)
Shruthan R (181CO250)

## Usage

* Register
* Search books by name, author or ISBN
* Get info about a book and submit your own review!


## To run locally:
# Create a virtualenv (Optional but reccomended)
$ python3 -m venv bookReviewWebsite

# Activate the virtualenv
$ source bookReviewWebsite/bin/activate (Linux)

# Install all dependencies
$ pip install -r requirements.txt

# ENV Variables (Use set instead of export if on Windows)
$ export FLASK_APP=application.py # flask run
$ export DATABASE_URL=postgres://usbnwnavqnsyne:1247c5fdaa0b8b893646a871fde5796576aa49f6c187ddc5b60a0300ca69fe55@ec2-54-243-128-95.compute-1.amazonaws.com:5432/d12p65no9a2avi
$ export GOODREADS_KEY=ElA9AzHFfCmghvuvHN8Uw 

