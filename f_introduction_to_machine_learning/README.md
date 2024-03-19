# Determining a prospective tariff plan for a telecom company

## Project description 
The mobile operator "Megaline" has found out that many customers are using outdated tariff plans. They want to build a system capable of analyzing customer behavior and suggesting a new tariff: "Smart" or "Ultra". We have data on the behavior of customers who have already switched to these tariffs (from the "Statistical Data Analysis" course project). We need to build a classification model that will select the appropriate tariff. Data preprocessing is not required - we have already done it. The goal is to build a model with the highest possible accuracy, aiming for an accuracy of at least 0.75. You need to independently verify the accuracy on the test dataset.

## Tools & Skills
Python, Pandas, Numpy, Seaborn, Matplotlib, SKlearn

## Key Findings
1) During the exploratory data analysis, we found that until 2015, there were relatively few films shown, although their number was increasing, and their share varied from 10% to 30%. The highest number of films was shown in 2019, although their share in the overall cinema screening rating is not at the top. The maximum box office earnings were in 2017. The minimum box office earnings were in the years 2010-2013. This is indicated by both the average and median lines.
We found that there is a large dispersion in the data, reflected in the difference between the mean and median values. We observe a situation where there are very low box office earnings for some movies and extremely high earnings for others. It was also revealed that in almost all years except 2015, films for audiences aged 16+ are the most popular.

2) During the investigation of films that received government support, it was noted that most of these films do not break even, however, films with average ratings can bring in significant profits. The most funded genres turned out to be drama, comedy, and animation. Fyodor Bondarchuk earned the most, having directed only two films with average ratings. The most profitable director was K. Shipenko.
