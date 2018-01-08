# Twitter Data Mining For Religious Hashtags

We interested on data mining on twitter while using hashtags(#). Some of the hashtags included but not limited to (Bible, Jesus, Christianity etc.) 

Some of my findings can be seen from the below picture. 

![alt text](https://preview.ibb.co/m12qjw/jda_twitter.png)


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Things you need to install in your local computer are given below. 

```
- [NumPy](http://www.numpy.org/)
- [Pandas]
- [matplotlib]
- [tweepy]
- [Ipython]
- [nltk]
- [BaseMap]

```

### Installing Python 2.7 ( I like this a lot sometimes you might need to install python 2.7) 

A step by step series of examples that tell you have to get a development env running

* For installing Python 2.7 into anaconda environment 

```
conda create -n python2 python=2.7 anaconda
```

Above terminal code will create an environment named python2 that contains Python 2.7 version of Anaconda.


```
source activate python2 
```

Above terminal execution will activate the environment. 

* Another approach for installing 2.7 and changing the environment inside of the Jupyter notebook explained below. If you have Python 3, you can set up Python 2 Kernel like this;

```
python -m pip intall ipykernel
python -m ipykernel install --user
```
If you have Python 2;

```
python3 -m pip install ipykernel
python3 -m ipykernel install --user
```
Then you can see in your Jupyter notebook both Python 2.7 and 3.5 versions shown in below picture. 

![alt text](https://preview.ibb.co/gKZSSw/Screen_Shot_2017_12_04_at_3_14_37_AM.png)

* Note: Installing basemap could be sometimes cumbersome so its recommended to install after anaconda installation. After installing your Anaconda you simply need to do above command to install Basemap on your computer. This instruction is for Mac Os. 

```
conda install -c anaconda basemap=1.0.7
```




## Built With

* [Python 3.5](http://www.dropwizard.io/1.0.2/docs/) - The code framework used.
* [Anaconda](https://maven.apache.org/) 
* [tweepy](http://www.tweepy.org/) - Used to generate data from twitter. 
* [Ipython](https://jupyter.readthedocs.io/en/latest/install.html)
* [NumPy](http://www.numpy.org/)
* [matplotlib](https://matplotlib.org/) - Needed for plots 
* [NLTK](http://www.nltk.org/) - For natural language processing and using their stopwords library
* [Basemap](https://matplotlib.org/basemap/) - This is for getting the world map and plotting the locations of the tweets.
* [pandas](https://pandas.pydata.org/) - Important !! for putting the json file into dataframe! 

## Data 

Data used in this project can be found in;
* [Twitter](twitter.com)

## Authors

* **Borga Edionse Usifo** - 

