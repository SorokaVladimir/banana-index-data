# The Banana index

This repository contains the data behind The Economist’s Banana index - first unveiled in our article ["A different way to measure the climate impact of food"](https://www.economist.com/graphic-detail/2023/04/11/a-different-way-to-measure-the-climate-impact-of-food). To download the data, go to [the latest release](https://github.com/TheEconomist/banana-index-data/releases), where you can download the index data as a CSV file and open it in your program of choice, such as Excel or Google Sheets.

## Methodology
The banana index gives the greenhouse-gas emissions of foods - by weight, calorie, or protein - by their equivalent in bananas. Greenhouse-gas emissions are in CO2-equivalents, with non-CO2 gases converted according to the amount of warming they cause over a 100-year timescale. 

Mathematically, this means that for a given metric, the banana score is the ratio of emissions efficiency. For instance, strawberries bring about 5.18 kilograms of CO2-equivalents per 1000 kilocalories. Bananas bring about 0.88 kilograms of CO2-equivalents per 1000 kilocalories. Strawberries banana score, by calorie, is therefore equal to 5.18/0.88, which rounds to 6.

## Sources 
* [Our World in Data (2023). Data Explorer: Environmental Impacts of Food](https://ourworldindata.org/explorers/food-footprints)
* [M. Clark et al. (2022). Estimating the environmental impacts of 57,000 food products.](https://www.pnas.org/doi/full/10.1073/pnas.2120584119)
* [Poore, J., & Nemecek, T. (2018). Reducing food’s environmental impacts through producers and consumers. Science, 360(6392), 987-992.](https://www.science.org/doi/10.1126/science.aaq0216) 

## Suggested citation
The Economist and Solstad, S. (corresponding author), 2023. The Economist's Banana index. First published in the article "A different way to measure the climate impact of food", The Economist, April 11, 2023.

(We also encourage you to cite our data sources.)

## DAB5 by Reuven Lerner Challenge#1 Tasks:
1 Download the data into a data frame. Set the index to be the entity column. Remove the year, Banana values, type, and Chart? columns.

2 Three  columns contain pre-computed banana scores for kg, calories, and protein. For each of these columns, show the 10 highest-scoring food products.


3 Which foods, if any, have the highest banana score on all three lists?

4 Create a new column, named Bananas index (land use 1000 kcal), calculating that food item's use of land for every 1,000 kcal. Which 10 foods have the highest score? Do any appear on the three previous lists?

5 What kind of cheese has the highest banana score per 1,000 kcal?

6 Show the correlations among the four computed banana scores. Which values seem to correlate most highly?

7 Highlight any correlations in the range 0.8 to 0.99 using a different color

My solutions are in 
# Week 16 (October 10) Practice Week1 Challenge1 Banana Index