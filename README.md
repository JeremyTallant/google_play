# The Android App Market on Google Play
## Description
Mobile apps are everywhere. They are easy to create and can be lucrative. Because of these two factors, more and more apps are being developed. In this project, we will do a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play across different categories. We'll look for insights in the data to devise strategies to drive growth and retention. The [data](https://www.kaggle.com/datasets/lava18/google-play-store-apps) for this project was scraped from the [Google Play](https://play.google.com/store/apps?hl=en&pli=1) website. While there are many popular datasets for Apple App Store, there aren't many for Google Play apps, which is partially due to the increased difficulty in scraping the latter as compared to the former. The data files are as follows:

* `apps.csv`: contains all the details of the apps on Google Play. These are the features that describe an app.
* `user_reviews.csv`: contains 100 reviews for each app, [most helpful first](https://www.androidpolice.com/2019/01/21/google-play-stores-redesigned-ratings-and-reviews-section-lets-you-easily-filter-by-star-rating/). The text in each review has been pre-processed, passed through a sentiment analyzer engine and tagged with its sentiment score.
## Usage
Clone this repository and open the Jupyter notebook file (`*.ipynb`) in a Jupyter environment with Python kernel support. Make sure to install the required packages such as `pandas`, `numpy`, and `matplotlib`. You can do this by running the following commands in a code cell within the notebook:
```python
!pip install pandas numpy matplotlib 
```
Once the packages are installed, run the code cells in the notebook to generate the plots and analyses.

If you don't have a Jupyter environment set up, you can install Jupyter Notebook and the Python kernel using the following steps:

1. Install Jupyter Notebook by following the instructions on the [official Jupyter website](https://jupyter.org/install).

2. Ensure you have Python installed. If not, you can download and install Python from the [official Python website](https://www.python.org/downloads/).
## Contents
1. **Google Play Store apps and reviews:** Import the data, drop duplicate rows, and inspect the data.
2. **Data cleaning:** Clean the dataset.
3. **Correcting data types:**
4. **Exploring app categories:** Create data for a bar chart that shows the distribution of apps across different categories.
5. **Distribution of app ratings:** Create a plot annotation for average app rating.
6. **Size and price of an app:** Examine the relationship between size, price, and rating of apps using `jointplot()`.
7. **Relation between app category and app price:** Use a strip plot to visualize the distribution of paid apps across different categories.
8. **Filter out "junk" apps:** Filter out "junk" apps.
9. **Popularity of paid apps vs free apps:** Prep the data for a box plot that compares the number of installs of paid apps vs. number of installs of free apps.
10. **Sentiment analysis of user reviews:**