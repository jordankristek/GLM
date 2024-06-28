# GLM

The goal of this project was to create a Generalized Linear Model to predict pass completions of NFL quarterbacks over a 7 year span.

First, i fit a GLM using one independent variable of air yards to predict the dependent variable of completed pass.

![image](https://github.com/jordankristek/GLM/assets/150874257/c9788d3a-3f70-47a7-94f6-fa628b03132c)

![image](https://github.com/jordankristek/GLM/assets/150874257/feff72e4-64ed-4d31-ae6a-ee5cdcec5531)

Next, i extracted the predictions and stored them in a column within my dataframe. I used the predictions to calculate the difference between my actual results and predicted results, which i called "CPOE"

Below are the average CPOE leaders over the last 7 seasons:

![image](https://github.com/jordankristek/GLM/assets/150874257/82c0b254-ffa9-4b7c-8f77-b9706e430514)

I re-did this exercise, but this time I created a GLM that used multiple independent variables, such as: down, yards to go, yards from endzone, air yards, pass location, and qb hit.

![image](https://github.com/jordankristek/GLM/assets/150874257/8ef3f22a-1a90-4aa0-b553-131a6cf11f1b)

Again, I extracted the predictions and used them to calculate average CPOE. The new results are as follows:

![image](https://github.com/jordankristek/GLM/assets/150874257/aa51791c-2631-49ed-aa3d-2c767e246911)

The last step was to compare the predicability of average CPOE year-over-year vs standard completion percentage.

![image](https://github.com/jordankristek/GLM/assets/150874257/3c7e541f-23df-4819-ae38-e68ed4cbe8ea)

![image](https://github.com/jordankristek/GLM/assets/150874257/3fd50c6f-4882-4f50-932f-368655979e32)

The data shows that average CPOE is slightly more correlated year-over-year than standard pass completion percentage.
