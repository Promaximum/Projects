# Customer Churn Prediction in the "Just Like Home" Hotel Chain

## Project description 
The customer of this research is the "Just Like Home" hotel chain. In order to attract customers, this hotel chain has added the option to book a room on their website without prepayment. However, if a customer cancels the reservation, the company incurs losses. Hotel staff could, for example, purchase products for the guest's arrival or simply fail to find another customer in time. To address this issue, you need to develop a system that predicts reservation cancellations. If the model predicts that the reservation will be canceled, the customer is offered to make a deposit. The deposit amount is 80% of the cost of the room for one day and the cost of one-time cleaning. The money will be deducted from the customer's account if they do cancel the reservation.

## Tools & Skills
Python, Pandas, Numpy, Matplotlib, Seaborn, Sklearn

## Key Findings

1) We found that the hotel's profit was 32,943,580 rubles without deposits in the test sample.
2) We calculated that the net profit after introducing deposits was 54,576,610 rubles, and the additional profit after introducing deposits considering the cost of developing the forecasting system was 5,595,080 rubles.
3) We identified the profile of an unreliable customer.
4) We wrote a general conclusion. The best model is the decision tree with a maximum depth of 1 and the following quality metrics on the test sample: F1-score = 0.634, and ROC-AUC = 0.775.
