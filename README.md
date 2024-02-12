# Edinburgh_Airbnb_Analysis

Airbnb is an online marketplace where people can book short-term stays in hotels or in other people's houses.
Recent developments in Edinburgh regarding the growth of Airbnb and its impact on the housing market means a better understanding of the Airbnb listings is needed.
Using data provided by Airbnb, we can explore how Airbnb availability and prices vary by neighbourhood.

## Column Descriptors

The `edibnb` data set contain `r nrow(edibnb)` listings in Edinburgh, with values about `r ncol(edibnb)` different variables that includes the property neighborhood location, number of rooms and review ratings.

Edinburgh council collects the second data set from their assessments of a randomly selected sample of listings.

The variables in this data set are: <br>
- `id`, the ID number of the listing (according to `edibnb`) <br>
- `price`, the daily rate of the accommodation unit<br>
- `neighborhood`, indicates in which neighbourhood the accommodation is located<br>
- `accommodates`, indicates how many people the accommodation can accommodate<br>
- `bathrooms`, indicates how many bathrooms the accommodation unit<br>
- `bedrooms`, indicates how many bedrooms are in the accommodation unit<br>
- `beds`, indicates how many beds are in the accommodation unit<br>
- `review_scores_rating`, the council's rating of the listing of the property either being good, adequate or poor.<br>
- `number of reviews`, indicates how many of the people who have stayed here before have made a review<br>
- `listing url`, the url of the accommodation