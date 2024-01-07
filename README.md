# USA Accident Analysis

This repository contains a Jupyter Notebook that conducts a comprehensive analysis of road accidents in the USA. The analysis explores various aspects such as date and time, state-wise and city-wise distribution, weather conditions, visibility, and interaction with the road or other vehicles.

## Aim

The aim of this project is to understand the patterns and factors contributing to road accidents in the USA, and to propose recommendations to improve road safety and reduce the number of accidents.

## Dataset

The Dataset used for this project is the [US Accidents](https://www.kaggle.com/sobhanmoosavi/us-accidents) dataset from Kaggle. It contains information about 3.5 million road accidents. The dataset was collected from various sources such as traffic cameras, traffic sensors, and other government agencies. It contains 49 attributes, including date and time, location, weather conditions, and severity of the accident.

**Citation:**

- Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, and Rajiv Ramnath. "A Countrywide Traffic Accident Dataset." (2019).
- Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, Radu Teodorescu, and Rajiv Ramnath. "Accident Risk Prediction based on Heterogeneous Sparse Data: New Dataset and Insights." In proceedings of the 27th ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems, ACM, 2019.

## Dependencies

This project requires the following Python libraries:

- Pandas
- Numpy
- Matplotlib
- Seaborn
- Plotly

You can install these dependencies using pip:

```bash
pip install pandas numpy matplotlib seaborn plotly
```

## Key Findings

- Majority of the accidents occur during the day time, specifically between 8 am to 6 pm.
- The number of accidents has been increasing over the years, with California having the highest number of accidents followed by Texas and Florida.
- December and January have the highest number of accidents, possibly due to holiday celebrations.
- Houston, Miami, Los Angeles, Charlotte, and Dallas are the cities with the highest number of accidents.
- Accidents are less frequent on weekends, indicating that people tend to stay at home during weekends.
- Fair weather conditions have the highest number of accidents, but accidents also occur during cloudy and rainy weather.
- Most accidents occur when visibility is less than 10 miles.
- The majority of accidents happen when there is no interaction with the road or other vehicles.

## Recommendations

Based on these findings, several recommendations to improve road safety and reduce the number of accidents are proposed:

1. Increase awareness and enforcement of road safety measures during peak hours, especially between 8 am to 6 pm.
2. Implement targeted road safety campaigns during December and January to reduce accidents during holiday celebrations.
3. Focus on improving road infrastructure and traffic management in cities with high accident rates, such as Houston, Miami, Los Angeles, Charlotte, and Dallas.
4. Enhance visibility on roads during adverse weather conditions by implementing better lighting systems and road signage.
5. Promote safe driving practices and educate drivers about the importance of maintaining a safe distance and adjusting speed based on visibility conditions.
6. Implement measures to encourage interaction with the road or other vehicles, such as speed breakers, traffic signals, and roundabouts.

## Future Work

This analysis provides valuable insights into the patterns and factors contributing to road accidents in the USA. It can serve as a foundation for further research and the development of targeted interventions to prevent accidents and improve road safety measures.
