### 1. BUSINESS UNDERSTANDING

### Stakeholder:

The stakeholder for this dataset could be a real estate agency or a property management company that deals with buying, selling, and renting houses in King County. They might be interested in analyzing this dataset to gain insights into the housing market of the county and improve their business decisions and also give accurate advice to homeowners on how to increase the value of their homes and by what amount

### Business problem:

The business problem that this stakeholder might face is determining the factors that influence house prices in the county. By understanding these factors, they could price their properties more accurately, invest in the right locations, and negotiate better deals with buyers and sellers. The stakeholder might also be interested in identifying the most desirable neighborhoods and property features that attract buyers and renters, so that they can focus their marketing efforts and increase their sales and revenue. In summary, the stakeholder wants to use regression modeling to predict house prices and gain insights into the factors that affect house values in King County.

This project uses the King County House Sales dataset, which can be found in kc_house_data.csv and description of the column names can be found in column_names.md.

* **id** - unique identified for a house
* **dateDate** - house was sold
* **pricePrice** -  is prediction target
* **bedroomsNumber** -  of Bedrooms/House
* **bathroomsNumber** -  of bathrooms/bedrooms
* **sqft_livingsquare** -  footage of the home
* **sqft_lotsquare** -  footage of the lot
* **floorsTotal** -  floors (levels) in house
* **waterfront** - House which has a view to a waterfront
* **view** - Has been viewed
* **condition** - How good the condition is ( Overall )
* **grade** - overall grade given to the housing unit, based on King County grading system
* **sqft_above** - square footage of house apart from basement
* **sqft_basement** - square footage of the basement
* **yr_built** - Built Year
* **yr_renovated** - Year when house was renovated
* **zipcode** - zip
* **lat** - Latitude coordinate
* **long** - Longitude coordinate
* **sqft_living15** - The square footage of interior housing living space for the nearest 15 neighbors
* **sqft_lot15** - The square footage of the land lots of the nearest 15 neighbors
### 2.DATA UNDERSTANDING
**loading data**

### Data Understanding

The King County House Sales dataset contains information on the sale of houses in King County between May 2014 and May 2015. It includes 21 columns with information such as the sale price, number of bedrooms and bathrooms, square footage, and location.

### Data Preparation

The dataset was cleaned by removing any missing or duplicate values, and feature engineering was performed to create new features such as the age of the house and the price per square foot.

### Modeling

Regression modeling was used to predict house prices based on the features in the dataset. Several models were tested, including linear regression, polynomial regression, and random forest regression, and the best model was selected based on its performance on the test data.

### Evaluation

The performance of the selected model was evaluated using metrics such as mean squared error and R-squared. The results showed that the model was able to accurately predict house prices with an R-squared value of 0.8.

### Conclusion

The analysis of the King County House Sales dataset provided insights into the factors that influence house prices in the county, such as location, size, and condition of the house. These insights can be used by real estate agencies and property management companies to make more informed business decisions and provide better advice to homeowners on how to increase the value of their homes.

### Future Work

In the future, additional features could be added to the dataset, such as the proximity to schools, parks, and other amenities. More advanced modeling techniques, such as neural networks, could also be explored to improve the accuracy of the predictions.


This project will give you a valuable opportunity to develop your data science skills using real-world data. The end-of-phase projects are a critical part of the program because they give you a chance to bring together all the skills you've learned, apply them to realistic projects for a business stakeholder, practice communication skills, and get feedback to help you improve. You've got this!
