# Neural Network Charity Analysis

## Overview of Analysis

This project was intended to predict if companies will be successful if Alphabet Soup was to give them some funding. Aalphabet Soup was able to provide a list of 34,000 different organizations that had received funding from them before. In order to prove that a company would be successful with the funding given by Alphabet Soup, they prediction accuracy needed to be 75%

## Results

* If a target was marked as SUCCESSFUL in the DataFrame, meant that funding towards that company would be favorable.

* The IS_SUCCESSFUL column is a feature for this dataset

* Columns EIN and NAME were removed towrds the beginning of the analysis as they were not targets or features for the analysis.

* The first layer inculded 110 neurons with relu activation, as relu is best for nonlinear datasets. For the second layer, the number of neurons was reduced to 80 with relu activation as well. Layers 3 and 4 included 40 and 20 neurons respectively with sigmoid activation as it is the best choice for binary classification problems. 

* The best result that was obtained from was 72.9%

![Alt text](https://github.com/dntalx/Neural_Network_Charity_Analysis/blob/main/Resources/Screen%20Shot%202022-11-02%20at%2010.41.27%20PM.png)

## Summary
