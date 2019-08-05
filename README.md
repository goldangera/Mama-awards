# [AWWWARDS CLONE](https://www.awwwards.com/)

#### This is a Python web application using Django  framework and Postgresql, 2019

#### By **[Golda Ngera](https://github.com/goldangera)**

### Description

This is a minimal imitation of the popular social network Awwwards.It mimics the system where it allows a user to post a project he/she has created and get it reviewed by his/her peers..

### Prerequisites

> Python3.6
> POSGRESQL


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

* Clone the repo into your local machine
```
git clone https://github.com/goldangera/Mama-awards.git
```
* cd into the instagram clone folder
```
cd instagram-clone
```
* create a virtual environment to run django in and activate it 
```
python3.6 -m venv --without-pip virtual && source virtual/bin/activate
```
* get pip to install dependencies with
```
curl https://bootstrap.pypa.io/get-pip.py | python
```
* install all requirements from requirements.txt
```
pip install -r requirements.txt
```
* prefered database is POSTGRESQL
* create a .env file in the root of the app and specify the environment variables required in the **settings.py** file
* run migrations
```
python manage.py migrate
```
* initiate the server
```
python manage.py runserver
```

## Deployment

To get more on deployement look up [Heroku Deployment](https://gist.github.com/newtonkiragu/42f2500e56d9c2375a087233587eddd0)

## Built With

* [Django](https://docs.djangoproject.com/en/2.2/) - The web framework used
* [Python](https://docs.python.org/3/) - Dependency Management


## Versioning

We use [Heroku](https://www.heroku.com/home) for versioning. 

## Authors

* **goldangera** email:nkirotegolda6888@gmail.com



## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments
