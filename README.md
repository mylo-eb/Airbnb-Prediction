# Predicting the rent prices of various houses based on different variable features
Making accurate predictions for rental prices of houses based on factors such as neighbourhood, longitude, latitude, and room type can greatly benefit hosts in determining the most profitable price to charge. By analyzing these key features, we can better understand the factors that influence demand for rental properties. Our machine learning system will provide hosts with recommendations for setting optimal prices, resulting in a more satisfying experience for them and increased profitability for Airbnb. As a result, many hosts will likely rely on the application to improve their earnings, thereby benefiting Airbnb as a whole.

## Dataset Information
This data was downloaded from Kaggle — a website that gives permissions to users to download large datasets for machine learning purposes. Here is the link that was used to download the data for this machine learning problem.

https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data

## Requirements
- numpy
- scikit-learn
- scipy
- matplotlib
- panda
## EDA 
Below picture is the Word Cloud for neighborhood column. visual representation of the column, where the size of each word in the cloud corresponds to its frequency or importance in the text. It helped for quickly identifying the most prominent keywords in a large body of text in the neighborhood column.
![Screenshot 2023-02-22 135008](https://user-images.githubusercontent.com/121390440/220730975-93b3d31c-53e0-4621-a2d5-4028848de8a0.png)
Below picture shows the distribution of data based on longtitude and latitude. it is used to visually explore the geographic distribution of different neighborhoods in a dataset, where each point on the scatter plot represents a location in latitude and longitude coordinates and the color of the point represents the neighborhood group.
![Screenshot 2023-02-22 135155](https://user-images.githubusercontent.com/121390440/220731124-9ef934e5-1256-4837-b91a-3d1f792a636d.png)

## Outcome
Airbnb hosts stand to gain significant advantages from utilizing these algorithms to establish rental prices, ultimately resulting in increased profitability. This approach can also foster growth and boost revenue for Airbnb as a whole.In order to evaluate the effectiveness of a regression model for price prediction, it is essential to select appropriate metrics. One such metric is the Mean Squared Error (MSE), which is commonly used to measure the accuracy of regression models.
## Future Scope
- The inclusion of supplementary factors like weather patterns and crime rates within neighborhoods can further enhance the accuracy of machine learning models in predicting rental prices. 
- Integrating the output of the top-performing models into the Airbnb app, hosts will be able to easily determine the most optimal price points, which can increase their engagement with the platform. 
- Deploying the machine learning model on cloud platforms such as Amazon Web Services (AWS) would enable us to make our product available on websites and accessible to users in various locations.
