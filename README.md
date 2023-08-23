1. This project aims at solving for the Lack of Visibility on the Youth Employment Status in the Country for Policy Making and Decisioning by building a Predictive Tool that Tracks the Number of Employed Youth in Kenya and a Monitoring Tool that allows Policy Makers to Track the Employment Status of Youth in the IT Sector.

2.  Data loaded is from the World Data Lab' Hackathon Competition.

3. Other than the columns provided from the datasets, a few more features are created through Feature Engineering:Feature Engineering: Total_employed_population, Population_growth_rate, Inactive_population_growth_rate, Labor_force_growth_rate, Unemployed_growth_rate, Total_employed_population_growth_rate, Population_growth_rate_rolled2, Inactive_population_growth_rate_rolled2, Labor_force_growth_rate_rolled2, Unemployed_growth_rate_rolled2, Total_employed etc.

4. Feature Selection is done using CatBoost Feature importance on the best features bringing the total useful features: Year, Total_employed_population_growth_rate, Labor_force_growth_rate_rolled2, Inactive_population_growth_rate, Inactive_population_growth_rate_rolled2.

5. Modeling is done using CatBoostRegressor with a time-based train-test split of 2000-2021 as train and 2022 as test.
