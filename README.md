In this project, I will be using the U.S. Energy Information's Residential Energy Consumption Survey (RECS) to explore the role of household square footage on electricity usage.
The RECS dataset includes detailed information on over 5,600 households in the USA. I will focus on only the total square footage (TOTSQFT_EN) and total site electricity usage, 
in kilowatthours, in 2015 (KWH) for apartments without high ceilings. Information on this rich dataset can be 
found here: https://www.eia.gov/consumption/residential/data/2015/index.php?view=microdata

For this project I utilize two resampling methods: cross-validation, and bootstrapping. Objectives for this project include:

1. Recognizing the pitfalls of overfitting, when it will occur.
2. Addressing the issue of overfitting the model by preparing the dataset for validation.
3. Understanding the trade-offs of different validation techniques: the validation set approach, k-fold cross-validation, and leave-one-out cross-validation.
4. Using bootstrapping to determine uncertainity in model coefficients.
