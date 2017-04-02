# Time Series Clustering

Project for [PV056 Machine learning course](https://is.muni.cz/course/fi/spring2016/PV056) on clustering of time series.

## Install

Prerequisites: Python 3, virtualenv, virtualenvwrapper.

Clone repository, create virtual environment, install dependencies and enable jupyter extensions:

    $ git clone https://github.com/effa/time-series-clustering.git
    $ cd time-series-clustering
    $ mkvirtualenv -a . time-series-clustering
    $ pip install -r requirements.txt
    $ jupyter nbextension enable --py widgetsnbextension

## Run

Activate virtual environment:

    $ workon time-series-clustering

Open jupyter notebook:

    $ jupyter notebook
