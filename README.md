# machine_learning_avocado_hass


### Table of Contents

- [Installation](#Installation)
- [FilesDescription](#FilesDescription)
- [Acknowledgements](#Acknowledgements)

## Installation <a name="Installation"></a>
Anaconda Distribution of Python  
Sklearn  
Numpy  
Seaborn  
Statsmodels  
Scipy  
Patsy  


This project follows the CRISP-DM Process (Cross Industry Process for Data Mining)

1. [BusinessUnderstanding](#BusinessUnderstanding)
2. [DataUnderstanding](#DataUnderstanding)
3. [PreparingData](#PreparingData)
4. [DataModeling ](#DataModeling)
5. [Results](#Results)


## BusinessUnderstanding <a name="BusinessUnderstanding"></a>

In this project we are interestes in answering questions regarding a product that is reffered in some places as "Green Gold", more specifically the avocado bussiness in United States. These questions can be of interest for indivuals that are thinkins into getting their own plantation or interested in commercialize this product. With greater understanding of the market a more robust decision can be made prior to embark into avocado business vewnture.

A few of the questions we want to answer are: What are the average prices of avocado in different states?, Do some states have different prices or are the prices the same everywhere?, What is the time of the year with have higher sales or lowest sales? From highest sales of the year, can we figure it out what week was the most profitable, the least? Have the prices have been increasing as years go by or is there a variation? 

These are just some of the questions we will attempt to find answers in our project. We will be using data analysis as well as some machine learning models to help us understant the commercial behavior of this demanded and profitable product around the world.


## DataUnderstanding <a name="DataUnderstanding"></a>
In order to answer these questions we must have a better understanding of the data we have access to. For this we use open source data that is available to us on the internet in [Kagle](https://www.kaggle.com/neuromusic/avocado-prices) website. In this site we found data that is related to Avocado businesses in United States. We were able to expand on this data also thanks to Hass Avocado Board [here](https://hassavocadoboard.com/). This website allowed us to download the most current data and add it to our dataset we extracted from Kaggle.

We will prepare the data next to be able to start to visualizing with the help of our Data Modeling techniques. 

## PreparingData <a name="PreparingData"></a>
We are working with one set of data belonging to avocado sales information in United States. The list of columns are: average_price, total_volume (Total number of avocados sold), 4046 (Total number of avocados with PLU 4046 sold), 4225 (Total number of avocados with PLU 4225 sold), 4770 (Total number of avocados with PLU 4770 sold), total_bags, small_bags ,large_bags, xlarge_bags, type (organic or conventional avocado), year, geography (cities where avocado sales are followed) and month.

## DataModeling <a name="DataModeling "></a>
We do this to see how well our model fits.

## Results <a name="Results"></a>
The main findings of the code can be found at the post available [here](https://medium.com/p/433322a88012/edit).

 ## FilesDescription <a name="FilesDescription"></a>

 There is only one notebook that was used to work on this project: prepare_data.ipynb -> This notebook was used to prepare, analyze and visualize the data.
 
 ## Acknowledgements <a name="Acknowledgements"></a>
 We have our data from internet. We are going to use Avocado Prices data csv file that we found in [Kaggle](https://www.kaggle.com/neuromusic/avocado-prices) and Hass Avocado Board [here](https://hassavocadoboard.com/).# disaster-response-data-science
