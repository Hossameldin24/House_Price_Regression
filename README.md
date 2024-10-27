# California House Price Prediction

## Project Overview
This project aims to predict the median house values in California using a dataset derived from the 1990 California census. The dataset contains various features related to houses and their locations, which will be used to develop regression models.

## Dataset Description
The dataset contains the following columns:
- **Median House Value**: Median house value for households within a block (measured in US Dollars) [$]
- **Median Income**: Median income for households within a block of houses (measured in tens of thousands of US Dollars) [10k$]
- **Median Age**: Median age of a house within a block; a lower number indicates a newer building [years]
- **Total Rooms**: Total number of rooms within a block
- **Total Bedrooms**: Total number of bedrooms within a block
- **Population**: Total number of people residing within a block
- **Households**: Total number of households, a group of people residing within a home unit
- **Latitude**: A measure of how far north a house is; a higher value is farther north [°]
- **Longitude**: A measure of how far west a house is; a higher value is farther west [°]
- **Distance to Coast**: Distance to the nearest coast point [m]
- **Distance to Los Angeles**: Distance to the center of Los Angeles [m]
- **Distance to San Diego**: Distance to the center of San Diego [m]
- **Distance to San Jose**: Distance to the center of San Jose [m]
- **Distance to San Francisco**: Distance to the center of San Francisco [m]

## Steps Undertaken

1. **Data Splitting**: 
   - The dataset is randomly split into three sets:
     - **Training Set**: 70%
     - **Validation Set**: 15%
     - **Testing Set**: 15%
   - Note: The validation and testing sets are not used during model tuning.

2. **Regression Models**:
   - Applied the following regression techniques to predict the median house value:
     - **Linear Regression**
     - **Lasso Regression**
     - **Ridge Regression**

3. **Model Evaluation**:
   - The performance of each model is evaluated using:
     - **Mean Squared Error (MSE)**
     - **Mean Absolute Error (MAE)**

4. **Results and Comparison**:
   - A summary of the results for each model will be presented, including MSE and MAE values.
   - Observations and comments on the performance of each regression technique will be included for comparison.

## Conclusion
This project demonstrates the application of regression techniques to predict house prices based on census data. The comparison of different regression models will provide insights into their effectiveness in handling the dataset.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
