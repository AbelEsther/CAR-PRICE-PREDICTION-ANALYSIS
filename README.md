# CAR-PRICE-PREDICTION-ANALYSIS
By building a reliable pricing model, I aim to understand how different attributes contribute to a car’s value, which can help stakeholders set fair, competitive prices and make informed purchasing or lending decisions.

![image](https://github.com/AbelEsther/CAR-PRICE-PREDICTION-ANALYSIS/blob/578bfa62a232bcbdc9e38267d48602ea053ab86f/car_price.avif)

## Notebook used in Data analysis and Model Building
[Car-price-prediction.pynb](https://github.com/AbelEsther/CAR-PRICE-PREDICTION-ANALYSIS/blob/5160d37273f21a42b3cfe06f0d773fe8ec7d03b4/car_prediction_analysis.ipynb)


## Dataset
[car_pricing.csv](https://github.com/AbelEsther/CAR-PRICE-PREDICTION-ANALYSIS/blob/6a4284ec1dee85382e65eb0a54318fe19cc0c64c/car_pricing.csv)



## **Problem Statement**
The primary challenge in the car industry is accurately valuing vehicles amid fluctuating market demands, changing consumer preferences, and diverse product offerings. Car manufacturers, dealerships, and resellers need a reliable way to price vehicles competitively while accounting for features that consumers value most. Incorrect pricing, whether too high or too low, can lead to lost sales, reduced profitability, or diminished brand perception. By developing a model that predicts car prices based on key attributes, businesses can address this issue, ensuring that pricing aligns with market expectations and maximizes revenue potential.


In this project, I aim to accurately predict the **Manufacturer’s Suggested Retail Price (MSRP)** of a car based on various features such as engine specifications, fuel efficiency, vehicle size, and popularity. By building a reliable pricing model, we aim to understand how different attributes contribute to a car’s value, which can help stakeholders set fair, competitive prices and make informed purchasing or lending decisions.

### **Who Might Be Interested in This Problem and Why?**

This problem is relevant to car manufacturers, dealerships, insurance companies, financial institutions, and consumers, all of whom rely on accurate car pricing. For manufacturers and dealerships, insights into price drivers enable competitive positioning and tailored offerings. Insurance and finance companies use price predictions for risk assessment and loan structuring. Additionally, consumers benefit by making informed purchasing decisions, while market analysts gain valuable insights into trends and consumer preferences. Overall, understanding what influences car pricing supports strategic decisions across the automotive industry.

### **Dataset Description**

This data contains over 10,000 automobiles (each record represents an actual car) and their attributes. The target variable of interest is MSRP (manufacturer-suggested price).The dataset includes the following attributes:

- **Make**: Brand of the car (e.g., BMW).
- **Model**: Specific model name or number of the car (e.g., 1 Series M).
- **Year**: Manufacturing year of the car model, which may influence price due to factors like age and technology (e.g., 2011).
- **Engine Fuel Type**: Type of fuel the engine requires, such as premium unleaded, diesel, or electric, impacting performance and cost (e.g., premium unleaded).
- **Engine HP**: Engine horsepower, indicating the power output of the engine; higher horsepower generally correlates with higher prices (e.g., 335.0).
- **Engine Cylinders**: Number of cylinders in the engine, affecting performance and efficiency (e.g., 6.0).
- **Transmission Type**: Type of transmission, such as manual or automatic, influencing driving experience and appeal (e.g., MANUAL).
- **Driven Wheels**: Describes the drivetrain layout, such as front-wheel drive, rear-wheel drive, or all-wheel drive, which can impact handling and market value (e.g., rear wheel drive).
- **Number of Doors**: Number of doors on the vehicle, which may relate to the car’s category (e.g., 2.0).
- **Market Category**: Labels indicating the car's market positioning, such as luxury or performance, which can affect consumer demand (e.g., Luxury, High-Performance).
- **Vehicle Size**: Classification of the car based on size, such as compact, midsize, or large, which influences price and market segment (e.g., Compact).
- **Vehicle Style**: Body style of the car, such as sedan, SUV, or coupe, which influences consumer preference and pricing (e.g., Coupe).
- **Highway MPG**: Fuel efficiency measured in miles per gallon for highway driving, often associated with operating costs (e.g., 26).
- **City MPG**: Fuel efficiency in miles per gallon for city driving, reflecting potential cost savings in urban areas (e.g., 19).
- **Popularity**: Popularity index of the car, indicating its demand or market presence (e.g., 3916).
- **MSRP**: The target variable, representing the manufacturer-suggested retail price for the car (e.g., $46,135).

I will use this dataset to perform a regression analysis, focusing on categorizing the MSRP (price) based on the available car features. This analysis will provide insights into the key factors that influence car pricing categories in the market.

## Conclusion
### **Satisfaction with Model Performance**
I am moderately satisfied with the final model’s performance, as it achieves an R² of 0.597, meaning it explains approximately 59.7% of the variance in car prices (MSRP). The model incorporates a well-rounded set of predictors that influence pricing, capturing a meaningful level of accuracy while balancing complexity and interpretability. However, there is still room for improvement in both predictive accuracy and feature relevance, especially as some variance remains unexplained.

### **Proposed Next Steps:**
- Introduce additional features or transformations (e.g., interaction terms, polynomial features for non-linear relationships) to capture more complex relationships in car pricing.
- Collect or integrate additional data sources, such as car brand reputation, market trends, or regional economic indicators, to improve model context and accuracy.
- Experiment with advanced models (e.g., Ridge, Lasso, or Random Forest regression) to assess if they can improve predictive accuracy and reduce error rates.

### **Potential Improvements**
- Address Non-linear Relationships More Thoroughly: Certain features, like Engine HP, may have diminishing effects on price. Incorporating non-linear regression techniques could better reflect real-world pricing dynamics.

### **Recommendations to Business Leadership**
Engine performance (HP and cylinders), fuel efficiency (MPG), and popularity are strong indicators of car price. Investments in enhancing these attributes or positioning high-performance models could align well with pricing strategies.

