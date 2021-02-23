# shopping-cart
Intro to Bus App dev class

This program is built with 20 products in it, and will produce a command line receipt after entering product numbers between 1-20. This receipt can also be sent to a user's email, if they so choose.

### Setup:
To run, set up a virtual environment with conda:

```
conda create -n shopping-env python=3.8
conda activate shopping-env
```

Additionally, you will need to install package dependencies:

```
pip install -r requirements.txt
```

Finally, create a .env file in your respository, using the file to specify your email address (that you will be sending from):
```
EMAIL_ADDRESS = "example@example.com"
```
Additionally, you will be required to provide a [sendgrid](http://sendgrid.com/) API key:
```
SENDGRID_API_KEY = SG.something
```

### To Run:

```
python shopping_cart.py
```
Then, follow the prompts and insert your chosen items, and decide if you want the 