# Cryptocurrencies

## Overview
This analysis was completed on various cryptocurrencies for an accounting firm which would like to start offering a crypto portfolio to its clients. The purpose was to filter all cryptocurrencies to determine all actively traded currencies and group them by their principal components in order to create a classification system for this new investment. 

## Results
* For this analysis, we filted out all unactive cryptocurrencies.
![active_cryptos](https://github.com/BryantKlewer/Cryptocurrencies/blob/main/Pictures/active_cryptos.png)

* The next step was to group all the remaining active crypto's by their principle components.
![pc_grouping](https://github.com/BryantKlewer/Cryptocurrencies/blob/main/Pictures/pc_grouping.png)

* A KMeans algorithm was run to determine how many categories we should utilize. Next, a 3D graph was created to visualize the categories of the various currencies.
![elbow_curve](https://github.com/BryantKlewer/Cryptocurrencies/blob/main/Pictures/elbow_curve.png)
![crypto_grouping](https://github.com/BryantKlewer/Cryptocurrencies/blob/main/Pictures/crypto_grouping.png)

* The next step was to create a sortable table for the tradable cryptocurrencies and determine the total number of tradable cryptocurrencies.
![tradable_crypto_table](https://github.com/BryantKlewer/Cryptocurrencies/blob/main/Pictures/tradable_crypto_table.png)
![num_of_cryptos](https://github.com/BryantKlewer/Cryptocurrencies/blob/main/Pictures/num_of_cryptos.png)

* The final step to was graph the number of mined coins vs. the supply of coins available. 
![coins_mined_supply](https://github.com/BryantKlewer/Cryptocurrencies/blob/main/Pictures/coins_mined_supply.png)
