# GreenhouseData
As part of a University Autonomous of Zacatecas initiative to promote the development of machine learning algorithms for more accurate modeling in agricultural greenhouses, data collection was conducted using a meteorological station installed within the greenhouses. The station recorded internal data (such as temperature, humidity, and dew point) and external data (such as temperature, humidity, and solar radiation).

## Data acquisition
A weather station collected the data from a greenhouse with a curved roof. This type of greenhouse is for traditional use with no climate control and has natural ventilation. The greenhouse has an area of 165m2, 27.5m long, 6m wide. This is located in South Mezquitera, Juchipila, Zacatecas, Mexico, with latitude and longitude (21.42624033959812, -103.10935313358475) and orientation 21°25'34.5"N 103°06'33.8"W.

Inside and outside the greenhouse are nine sensors as a part of the Davis Vantage Pro 2 central weather system. Seven sensors outside the greenhouse measure temperature, humidity, solar radiation, barometric pressure, rainfall, wind speed, and direction. Inside the greenhouse, there are sensors for humidity and temperature. These sensors work together to create a uniform system within the greenhouse. 

Data were collected from July 12, 2020, to June 24, 2021, with sampling at 5-minute intervals. Information was not collected during two periods: December 16th, 2020 - January 3rd, 2021, and March 7th, 2021 - March 21st, 2021. A total of 85,989 samples were obtained to train and test the prediction models. 

During data collection, tomatoes were grown from July 2019 to January 2020, and bell peppers from February 2020 until the end of the data.

## Paper related and citation
1. Prediction of Internal Temperature in Greenhouses using the Supervised Learning Techniques: Linear and Support Vector Regressions

Link to paper: https://www.mdpi.com/2076-3417/13/14/8531

@article{analysis_of_regression_and_SVM_models,
    title={Prediction of Internal Temperature in Greenhouses using the Supervised Learning Techniques: Linear and Support Vector Regressions},
    author={García-Vázquez, F.; Ponce-González, J.R.; Guerrero-Osuna, H.A.; Carrasco-Navarro, R.; Luque-Vega, L.F.; Mata-Romero, M.E.; Martínez-Blanco, M.d.R.; Castañeda-Miranda, C.L.; Díaz-Flórez, G},
    journal={Applied Sciences},
    volume={13},
    number={1},
    pages={8531},
    year={2023},
    publisher={MDPI}}

2. Long Short-Term Memory Recurrent Neural Network and Extreme Gradient Boosting Algorithms Applied in a Greenhouse’s Internal Temperature Prediction

Link to paper: https://www.mdpi.com/2076-3417/13/22/12341

@article{LSTM_and_XGBoost_models,
    title={Long Short-Term Memory Recurrent Neural Network and Extreme Gradient Boosting Algorithms Applied in a Greenhouse’s Internal Temperature Prediction},
    author={Esparza-Gómez, J. M.; Luque-Vega, L. F.; Guerrero-Osuna, H. A.; Carrasco-Navarro, R.; García-Vázquez, F.; Mata-Romero, M. E.; Olvera-Olvera, C. A.; Carlos-Mancilla, M. A.; Solís-Sánchez, L. O},
    journal={Applied Sciences},
    volume={13},
    number={22},
    pages={12341},
    year={2023},
    publisher={MDPI}}

## Acknowledgements
The authors want to thank the Mexican National Council of Science and Techology CONACYT for its support to the National Laboratory of Embedded Systems, Advanced Electronics Design and Micro systems (LN-SEDEAM by its initials in Spanish), projects number 445 282357, 293384, 299061, 314841, and 315947, and also for the scholarship 1012274.