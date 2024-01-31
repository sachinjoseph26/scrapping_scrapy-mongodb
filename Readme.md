# WEb Scrapping data and store in MongoDB

## Create/ Activate an virtaul environment(venv) 
    python -m venv spy_mng
    .\spy_mng\Scripts\activate.ps1

## Install required packages(Scrapy, pymongo)
    pip install Scrapy
    pip install pymongo

## Start new scrapy project

    scrapy startproject stack
### Then we will get a folder structure as follows:

    ├── scrapy.cfg
    └── stack
        ├── __init__.py
        ├── items.py
        ├── pipelines.py
        ├── settings.py
        └── spiders
            └── __init__.py

## Specifies Data (Use items.py)
