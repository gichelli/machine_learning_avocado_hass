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
The main findings of the code can be found at the post available [here](https://gichellivento.medium.com/avocado-hass-market-in-united-states-433322a88012).

 ## FilesDescription <a name="FilesDescription"></a>

 There is only one notebook that was used to work on this project: avocado.ipynb -> This notebook was used to prepare, analyze and visualize the data.
 
 ## Acknowledgements <a name="Acknowledgements"></a>
 We have our data from internet. We are going to use Avocado Prices data csv file that we found in [Kaggle](https://www.kaggle.com/neuromusic/avocado-prices) and Hass Avocado Board [here](https://hassavocadoboard.com/). Also we would like to thanks Udacity [here](https://review.udacity.com/?utm_campaign=ret_600_auto_ndxxx_ungradeable-plagiarism_global&utm_source=blueshift&utm_medium=email&utm_content=ret_600_auto_ndxxx_ungradeable-plagiarism_global&bsft_clkid=021201ec-6269-4dca-92de-025f1c41e744&bsft_uid=8349d38f-99d1-40db-8e9f-892744f5e6fb&bsft_mid=6bd5b847-21af-4c0a-a008-e2710c44a779&bsft_eid=430bec6a-2ba7-fb2a-7181-ba32a7f413fb&bsft_txnid=e87fc881-e397-4787-9497-f1e204c7c36a&bsft_link_id=5&bsft_mime_type=html&bsft_ek=2021-04-21T20%3A38%3A25Z&bsft_aaid=8d7e276e-4a10-41b2-8868-423fe96dd6b2&bsft_lx=5&bsft_tv=6#!/reviews/2893604) for providing useful code to build our matrix. We were also able to get a nice code to convert some of our data types from [ProgrammerSought](https://www.programmersought.com/article/68227485870/)
