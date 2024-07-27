# AirBnb Bash!
by Linearity Legends

## Summary
We are examining all of the factors influencing price to help vacationers make more informed decisions about their stay.

# Data dictionary

The data columns can be described as follows:

| Variable                         | Description                                                                                                                                                               |
|:-----------------|:----------------------------------------------------|
| `id`                             | The unique identifier for each Airbnb                                                                                                                                     |
| `name`                           | Contains multiple variables, listed in order: Type of home rented, Location (We are only using Austin), Rating (i.e. "★4.84"), No. of bedrooms, No. of beds, No. of baths |
| `host_id`                        | The unique identifier for each host                                                                                                                                       |
| `host_name`                      | The name of the host renting the Airbnb                                                                                                                                   |
| `neighbourhood`                  | The ZIP code that the Airbnb is in                                                                                                                                        |
| `latitude`                       | The latitude of the Airbnb                                                                                                                                                |
| `longitude`                      | The longitude of the Airbnb                                                                                                                                               |
| `room_type`                      | What was rented (i.e. "Entire home/apt", "Private room", ... etc.)                                                                                                        |
| `price`                          | The daily price in local currency. Since we are only using Airbnbs in Austin, TX, this value will be in \$.                                                               |
| `minimum_nights`                 | The minimum amount of nights that a person can rent out the Airbnb.                                                                                                       |
| `number_of_reviews`              | The number of reviews for the Airbnb.                                                                                                                                     |
| `last_review`                    | The date that the most recent review was posted for the Airbnb.                                                                                                           |
| `reviews_per_month`              | The number of reviews per month for an Airbnb.                                                                                                                            |
| `calculated_host_listings_count` | A counter for the number of Airbnbs a certain `host_id` has.                                                                                                              |
| `number_of_reviews`              | The number of reviews for the Airbnb.                                                                                                                                     |
