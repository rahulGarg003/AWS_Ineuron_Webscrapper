# Ineuron Scrapper

Ineuron Scrapper is used to scrapper courses from Ineuron Website and store it in MysqlDb and MongoDB

## Features

- Scrap data from [Ineuron Website](https://www.ineuron.ai) using Beautiful Soup
- Store whole data in MongoDB and MySql
- Generate course curriculum pdfs and store them on Amazon S3 bucket
- Used flask framework as backend


## Tech

- Python
- Flask
- Beautiful Soup
- FPDF
- Bootstrap 5
- MongoDB
- MySql
- Flask SqlAlchemy
- AWS BeanStalk
- AWS Code Pipeline
- Amazon S3

## Requirements
- Python-3.8 or above 

## Installation

```sh
git clone https://github.com/rahulGarg003/AWS_Ineuron_Webscrapper.git
```

Install the dependencies

```sh
pip install -r requirements.txt
```

Create a .env file in root folder of your project and provide below details
```sh
AWS_S3_REGION_NAME='<>'
AWS_S3_BUCKET_NAME='<>'
AWS_ACCESS_KEY_ID='<>'
AWS_SECRET_ACCESS_KEY='<>'
SQL_DB_ENGINE='mysql'
SQL_DB_HOSTNAME='<>'
SQL_DB_PORT='<>'
SQL_DB_USERNAME='<>'
SQL_DB_PASSWORD='<>'
SQL_DB_NAME='<>'
MONGO_DB_USERNAME='<>'
MONGO_DB_PASSWORD='<>'
MONGO_DB_HOSTNAME='<>'
MONGO_DB_NAME='<>'
MONGO_DB_COLL_COURSE='<>'
MONGO_DB_COLL_CATEGORY='<>'
MONGO_DB_COLL_COURSE_BNDL_CNT_CATGRY='<>'
MONGO_DB_COLL_COURSE_BNDL_CNT='<>'
APP_UPDATE_PASSWORD='<>'[give any password you want.]
```

start flask server
go to root directory of project and  open terminal

```sh
python application.py
```

