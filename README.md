# What-Drives-Prices-of-a-Car
In this application, we embark on a detailed exploration of a dataset obtained from Kaggle, originally containing information on 3 million used cars. For practicality, we focus our analysis on a subset comprising details on 426K cars. The overarching objective is to uncover the factors influencing the pricing of used cars. Our mission is to equip a used car dealership with actionable insights on what consumers value in a used car, thereby guiding strategic inventory decisions.

**Basic Report Extended**

Following an in-depth analysis, we have found additional key insights that significantly impact used car prices:

**Odometer Mileage Impact:**

Cars with less than 60,000 miles on the odometer are almost twice as expensive as those with more than 90,000 miles. People really like and are willing to pay more for cars with lower mileage. The optimal mileage range aligns with higher pricing and increased consumer preference.

**Title Status Significance:**

Cars with title statuses other than clean and lien are least preferred by potential buyers. Clean title cars hold higher value in the used car market.

**Engine Size and Condition Relationship:**

Newer cars tend to have smaller engines. There is also a noticeable correlation between engine size and car condition. Cars in excellent condition are more likely to have 6 cylinders, while 4-cylinder cars are prevalent in excellent condition.

**Manufacturer Insights:**

Analysis of the manufacturer dataset reveals Ford as the most common brand in the used car market, followed closely by Chevrolet and Toyota. These insights can aid dealers in understanding brand popularity and adjusting inventory accordingly.
Key Features Impact on Pricing:

Beyond the pivotal role of the car's year in determining its price, the number of cylinders and odometer readings emerge as crucial factors. Buyers often consider these features in their decision-making process.
Fuel type also holds significance, especially with fluctuating gas prices. It is recommended to carefully consider this factor to align with consumer preferences.

## Feature Importance
Curious about the nitty-gritty? Here's the percentage importance of key features:

Year: 30.28%
Cylinders: 22.56%
Odometer: 16.17%
Fuel Type: 11.04%
Title Status: 5.33%
Transmission: 5.03%
Drive: 4.20%
Model: 1.49%
Condition: 1.11%
Type: 0.93%
Manufacturer: 0.92%
Paint Color: 0.47%
Region: 0.42%
State: 0.05%
![importance Percent](https://github.com/Hoomaaan/What-Drives-Prices-of-a-Car/assets/33916130/2f34c2c2-931f-4b9c-a13b-1bea8fc9bcd6)

These numbers tell you how much each feature matters in deciding a car's price.

This image is a vital compass for used car dealers, providing a quick guide to the impact of different features on car prices. When a coefficient is positive, it signals a positive direction—meaning, with an increase in that feature, the price tends to go up. Conversely, a negative coefficient suggests that with an increase in the feature, the price tends to go down. It's a concise visual aid to navigate the influencing factors behind used car pricing decisions.

![coeffs_direction](https://github.com/Hoomaaan/What-Drives-Prices-of-a-Car/assets/33916130/bad1ef46-8153-480b-9831-6e73d9e89377)


My findings and more details of this analysis are in [Prompt_II.ipynb](https://github.com/Hoomaaan/What-Drives-Prices-of-a-Car/blob/main/prompt_II.ipynb).
### Future Steps
Now that we've uncovered the key factors driving used car prices, the next step is to empower dealers with a powerful tool. We can introduce user-friendly software—a piece of code that harnesses the insights from our analysis. This tool internally utilizes the trained Lasso model, which has proven to be the most effective in predicting car values accurately.

Dealers are invited to leverage this intuitive tool. By entering specific car details—year, cylinders, odometer reading, fuel type, title status, and transmission—the software utilizes our advanced Lasso model. This results in a real-time estimate of the car's value, based on the most impactful factors determined through our thorough analysis.
