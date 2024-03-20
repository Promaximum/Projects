# The study of apartment sale listings

## Project description 
The available data from the Yandex Real Estate service comprises an archive of apartment sale listings in St. Petersburg and neighboring areas over several years. The goal is to learn how to determine the market value of real estate properties. Our task is to establish parameters that will enable the construction of an automated system capable of detecting anomalies and fraudulent activities.

## Tools & Skills
* Python
* Pandas
* Random
* Matplotlib
* Numpy

## Key Findings
1) The most popular apartments are those ranging from 30 to 46 square meters.

2) The most popular price range is from 1 to 7.4 million rubles.

3) The most popular types of apartments are one-bedroom and two-bedroom.

4) The most common ceiling height ranges from 2.5 meters to 3.1 meters.

5) Generally, apartments are sold within 3 to 6 months.

6) Currently, real estate agents set a specific timeframe for selling apartments, and most listings are removed because the paid publication period ends. Typically, services are paid for a certain period.

7) Price is influenced by the apartment's area. There is a significant impact of price on the number of rooms, followed by a somewhat weaker influence of price on the distance from the city center. Additionally, there is a correlation between price and floor (first floor being the least popular). The most popular category of floors is "Other", indicating that floors ranging from the second to the penultimate are the most popular.

8) The central zone of the city is within a diameter of zero to eight kilometers.

9) The proportion of apartments sold in the center is significantly higher than those sold throughout the city. Additionally, prices in the center are higher than in the rest of the city. The most sold apartments in the center are two-bedroom and three-bedroom, while throughout the city, it's one-bedroom and two-bedroom apartments. In the city center, as well as throughout the city, apartments with a height of 2.7 meters are popular. Also, three-meter apartments are more popular in the city center than throughout the city.

10) The number of rooms does not strongly affect the price in the city center. There is also a slight dependence on the distance from the center throughout the city, while there is no such dependence in the center. Similarly, apartments on the top floors are popular both in the city center and throughout the city.

11) Methods of correlation between parameters have been removed as it was determined that the relationship was non-linear.
