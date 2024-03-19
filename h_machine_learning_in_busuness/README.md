# Choosing a location for an oil well

## Project description 
The task from the extraction company "X" is to decide where to drill a new oil well.

We have samples of oil in three regions: in each region, there are 10,000 oil fields where the quality of the oil and the volume of its reserves were measured. The goal is to build a machine learning model that will help determine the region where extraction will bring the highest profit. Additionally, we need to analyze the potential profit and risks using the Bootstrap method.

## Tools & Skills
Python, Pandas, Numpy, Matplotlib, Sklearn

## Key Findings

During the research, we completed the following steps:

1) We studied the data and prepared it for training.

2) We noticed that the predicted values roughly coincided with the actual values. The model performed best in the second region (geo_data_1 - 0.88), followed by the first (geo_data_0 - 37.61), and then the third (geo_data_2 - 40.18). The data from the second model most likely overfit due to skewness. Due to the lack of data, considering the second region as profitable doesn't make sense.

3) We developed a function to calculate profit and assessed the profitability and risks for each region.

4) We calculated the profit and risks for each region and selected the best region, justifying our choice. The second region was chosen because it had the best indicators (the lowest risk among other regions); however, its data did not follow the normal distribution law.
