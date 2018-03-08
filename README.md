# Spaceship-Time-Series-Prediction
Predicting monthly sales of multiple merchants

This was part of the coursework from Coursera's Advanced Machine Learning(ML) Specialization. The goal of this project is similar to a ML project which was implemented at my previous startup www.spaceship.com.sg. Spaceship is a warehouse storage and logistic service provider for other merchants. This project was started with a simple question “Can we predict what our clients are selling next month so that we can optimize the warehouse items’ position in advance?“. 

Due to privacy concern, we cannot use the actual from Spaceship. However, the provided data has identical structure to the real world data we had.

Data URL: https://www.kaggle.com/c/competitive-data-science-final-project/data

#File descriptions

sales_train.csv - the training set. Daily historical data from January 2013 to October 2015.
test.csv - the test set. You need to forecast the sales for these shops and products for November 2015.
sample_submission.csv - a sample submission file in the correct format.
items.csv - supplemental information about the items/products.
item_categories.csv  - supplemental information about the items categories.
shops.csv- supplemental information about the shops.
Data fields

ID - an Id that represents a (Shop, Item) tuple within the test set
shop_id - unique identifier of a shop
item_id - unique identifier of a product
item_category_id - unique identifier of item category
item_cnt_day - number of products sold. You are predicting a monthly amount of this measure
item_price - current price of an item
date - date in format dd/mm/yyyy
date_block_num - a consecutive month number, used for convenience. January 2013 is 0, February 2013 is 1,..., October 2015 is 33
item_name - name of item
shop_name - name of shop
item_category_name - name of item category
