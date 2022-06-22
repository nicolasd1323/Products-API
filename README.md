# Project Overview

## Products-python

## Project Description

The idea of this project is to have a REST API With Flask & SQL Alchemy and Marshmallow using Python.

### Sample Data
```
[
{
description: "The iPhone is a smartphone made by Apple that combines a computer, iPod, digital camera and cellular phone into one device with a touchscreen interface. The iPhone runs the iOS operating system, and in 2021 when the iPhone 13 was introduced, it offered up to 1 TB of storage and a 12-megapixel camera.",
id: 1,
name: "iPhone 13",
price: 999.99,
qty: 200
},
{
description: "The Samsung Galaxy S21 specs are top-notch including a Snapdragon 888 chipset, 5G capability, 8GB RAM coupled with 128/256GB storage, and a 4000mAh battery.",
id: 2,
name: "samsung s21",
price: 657.39,
qty: 122
},
{
description: "Pixel 6 is built from Pixel's toughest Gorilla Glass yet, with up to 2x better scratch resistance than previous Pixel phones. And with IP68 protection, it can take on a little water and dust no problem. It's just as durable as it is beautiful. The display adapts to you.",
id: 3,
name: "Google Pixel 6",
price: 899.99,
qty: 132
}
]
```
### Activate venv
```
$ pipenv shell

# Install dependencies
$ pipenv install

# Create DB
$ python
>> from app import db
>> db.create_all()
>> exit()

# Run Server (http://localhst:5000)
python app.py
```
# Endpoints
```
GET /product
GET /product/:id
POST /product
PUT /product/:id
DELETE /product/:id
```




