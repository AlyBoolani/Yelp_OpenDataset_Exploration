# Yelp_OpenDataset_Exploration
An exploration of the Yelp dataset downloaded from the website. 

The data set was download in compressed form and is about 4.4GB in size compressed and about 9.8GB uncompressed. 

The files that come with the dataset are as follows:
##### JSON files:
    - Business.json - Contains business data including location data, attributes, and categories.
    - review.json - Contains full review text data including the user_id that wrote the review and the business_id the review is written for.
    - user.json - User data including the user's friend mapping and all the metadata associated with the user.
    - checkin.json - Checkins on a business.
    - tip.json - Tips written by a user on a business. Tips are shorter than reviews and tend to convey quick suggestions.
    - photo.json - Contains photo data including the caption and classification (one of "food", "drink", "menu", "inside" or "outside").
    
PDF file:



The first step is to convert these json files using pandas for python in order to transfer it to a tabular format for better viewing and analysis. Once these json files are converted into a tabular form, we'll save these as csv's and combine all six csv files in one consolidated csv comprising of all metadata linked by the common elements such as business and user id. 


Detailed information can be found [here](https://www.yelp.com/dataset/documentation/main)

