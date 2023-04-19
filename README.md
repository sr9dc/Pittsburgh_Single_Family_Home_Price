# [Predicting Single Family Home Prices in Pittsburgh](https://github.com/sr9dc/Pittsburgh_Single_Family_Home_Price/blob/main/Final%20Report.pdf)

<!--
*** Thanks for checking out this project. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
-->



<!-- ABOUT -->
## Topic
This project aims to build models that can better predict the cost of real estate in Pittsburgh. We will use a variety of data sources related to Pittsburgh to bolster real estate data from sources such as Redfin. 



## Overview

With today’s hot real estate market, it is more difficult than ever to find value in a home purchase. Our product leverages non-conventional data streams to better predict the actual selling price of homes. This problem is important because it allows real estate investors to identify properties that are potentially undervalued relative to the market, and find value where other investors may not think to look. 


Current approaches are through companies like Redfin, Zillow, and Realtor.com. These companies use a mix of resources to predict home prices. We decided to utilize Redfin's data.  Based on their publicly available data, they predict home prices based on bedrooms, bathrooms, the year the home was built, and the neighborhood. The input for our model is the basic information that is publicly available on Redfin, as well as additional data for crime, local school information, and census information, to predict a home selling price, which is our output.


## Goal

Our criteria for success is centered around accuracy. This can be measured by comparing the predicted values to the actual values and calculating the percentage of predictions that are within a certain range of the actual values. “According to Redfin, its estimates are approximately 74% accurate within 5% of the sales price for listed homes”.   We are running our own Redfin baseline model to verify Redfin’s claim on their accuracy. The goal is for our improved model to increase accuracy relative to that baseline model. We will consider our model successful if it performs better than the Redfin model.


## Team Responsibilities

Hannah Fairfield: Baseline linear regression model, Redfin dataset

Sai Rajuladevi: Redfin dataset, Clustering, SciKit learn modeling, AutoML modeling

Kraig Sheetz: Crime dataset, Schools dataset

Cole Thomas: AutoML modeling, SciKit learn modeling, Census Bureau dataset

## Code

#### [EDA Sample 1](https://github.com/sr9dc/Pittsburgh_Single_Family_Home_Price/blob/main/Project%20Code/Census_EDA.ipynb)

#### [Census_Model_Run.ipynb](https://github.com/sr9dc/Pittsburgh_Single_Family_Home_Price/blob/main/Project%20Code/Census_Model_Run.ipynb)

#### [Census_Model_Run_AutoML.ipynb](https://github.com/sr9dc/Pittsburgh_Single_Family_Home_Price/blob/main/Project%20Code/Census_Model_Run_AutoML.ipynb)



## Results

View the report pdf to see our detailed findings. 


#### [Final Report](https://github.com/sr9dc/Pittsburgh_Single_Family_Home_Price/blob/main/Final%20Report.pdf)


## Presentation

View the presentation slides. 


#### [Presentation](https://github.com/sr9dc/Pittsburgh_Single_Family_Home_Price/blob/main/Presentation/Home%20Price%20Presentation%2C%20Thursday%20DEC%208.pdf)



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.


<!-- CONTACT -->
## Contact

Sai Rajuladevi: https://www.linkedin.com/in/sai-rajuladevi/






