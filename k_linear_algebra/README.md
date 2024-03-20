# Protection of client personal data

## Project description 
The data of the clients of the insurance company 'Even if Flood' should be protected. Develop a method of data transformation in such a way that it is difficult to reconstruct personal information from it. Justify the correctness of its operation. It is necessary to protect the data so that the quality of machine learning models does not deteriorate during the transformation. It is not necessary to select the best model.

## Tools & Skills
* Python
* Pandas
* Numpy
* Matplotlib
* Sklearn

## Key Findings

Within the project, the following steps were taken:

1) We loaded and analyzed the data, performing preprocessing on it.
   
2) Developed an algorithm for data transformation and applied it to the data.
   
3) Found that the quality of linear regression did not change whether we used the original matrix or the transformed matrix obtained by multiplying it by the inverse matrix. We demonstrated this using the formula provided earlier, as well as practical exploration using the R2 metric.
