# Linear Regression on Bike Share Scenerio

> Linear Regression model applied using statsmodels library on Bike sharing Dataset to predict the number of bike rented in a day and find important features of the data.

## Table of Contents

- [Linear Regression on Bike Share Scenerio](#linear-regression-on-bike-share-scenerio)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
    - [Business Problem](#business-problem)
    - [Goal of the Project](#goal-of-the-project)
    - [Dataset information](#dataset-information)
  - [Conclusions(Business Recomendation)](#conclusionsbusiness-recomendation)
  - [Result](#result)
  - [Technologies Used](#technologies-used)
  - [Acknowledgements](#acknowledgements)
  - [Contact](#contact)
  - [License](#license)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Business Problem

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

### Goal of the Project

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

### Dataset information

Dataset taken from Paper "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.

## Conclusions(Business Recomendation)

- The bikes rented will be more with each passing year.
- The bikes rented are more in summer season thus hosting events or advertisements will be beneficial.
- Month of August and October are the best months to rent bikes as they see most increase in bikes rented.
- Days with low windspeed also see increase in bikes rented and are good opportunities for business.
- The bikes rented are decreased in rainy and cloudy weather.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Result

We achieved the following results:

- Test Accuracy: 0.795
- RMSE : 0.0986
- Mean Absolute Error : 0.0746
- Durbin-Watson value : 1.9896

## Technologies Used

- Pandas - version 1.3.4
- NumPy - version 1.20.3
- MatplotLib - version 3.4.3
- Seaborn - version 0.11.2
- Scikit-Learn - version 0.24.2
- StatsModels - version 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.

Thanks to Fanaee-T, Hadi and Gama, Joao for the sharing the dataset with the world.

## Contact

Created by [@sukhijapiyush] - feel free to contact me!

<!-- Optional -->

## License

This project is open source and available without restrictions.

<!-- You don't have to include all sections - just the one's relevant to your project -->
