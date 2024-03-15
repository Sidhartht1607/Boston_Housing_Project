# Boston Suburban Housing Values Analysis
### Executive Summary

This project delves into analyzing housing trends in the suburbs of Boston, aiming to make predictive insights based on various factors. Key variables considered include crime rates, land zoning, proximity to the Charles River, nitrogen oxide concentration, dwelling characteristics, demographic composition, and accessibility to amenities like employment centers and highways.

### Key Findings:

    The average age of owner-occupied buildings is around 68-69 years, with a range from 2 to 100 years.
    Crime rates are generally low but spike in specific regions, warranting caution.
    Nitrogen oxide concentration is relatively low, ranging from 0.385 to 0.871 parts per 10 million.
    Houses typically have 4 to 8 rooms, with a mean average of 6.
    Strong correlations exist between factors such as non-retail business proportions, crime rates, and population density.
    The median value of owner-occupied homes correlates closely with socioeconomic factors like lower status population percentages and accessibility to highways.

### Technical Report:

    Utilized the Boston dataset from the Mass package, consisting of 13 independent variables and 506 cases.
    Employed log(medv) for a more robust model.
    No missing values were observed in the dataset.
    8 predictors were initially considered, with later inclusion of 3 additional variables due to their significant impact on model performance.
    The final model achieved an adjusted R-squared value of 0.777, indicating reliability.
    Key predictors contributing positively to median house value include room count, proximity to Charles River, and distance to employment centers.
    The model equation for log(medv) is provided for reference.

### Conclusion:
This analysis provides valuable insights into the housing market dynamics in Boston suburbs, facilitating informed decision-making for investors and homebuyers. Further exploration and refinement of predictive models can enhance understanding and accuracy in future analyses.

For detailed analysis and code implementation, refer to the project repository.
