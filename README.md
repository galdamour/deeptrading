# DeepTrading


DeepTrading is a collection of Jupyter notebooks. The objective is to organize in a systematic but flexible way all the necessary steps to calculate and conceive trading systems based on the Tensorflow software.

For more info see: [TodoTrader DeepTrading Tensorflow serie](https://todotrader.com/deeptrading-with-tensorflow/)

### Installation

It is highly recommended to run DeepTrading in designated Conda virtual environment.
To install Conda you can be guided by any of the many tutorials that are disseminated
throughout the Web.

```
git clone https://github.com/parrondo/deeptrading.git
cd deeptrading
conda env create --file environment.yml
```

It's likely you want to have a .env file. It is a configuration text file that is used to define some variables you want to pass into your application's environment.

Example of .env file:

~~~
PROJ_DIR=.
DATA_DIR=../data/
RAW_DIR=../data/raw/
INTERIM_DIR=../data/interim/
PROCESSED_DIR=../data/processed/
FIGURES_DIR=../reports/figures/
MODEL_DIR=../models/
EXTERNAL_DIR=../data/external/
PRODUCTION_DIR=/home/PRODUCTION/
~~~

