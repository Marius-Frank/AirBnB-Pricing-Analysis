# The AirBnB Berlin Dataset Analysis (2022-2023)

This repository contains an analysis of the AirBnB Berlin dataset for the years 2022 and 2023. The data, sourced from [InsideAirbnb](http://insideairbnb.com/get-the-data/), comprises listings and calendar information of the available AirBnB offerings in Berlin over the course of a year.

## Table of Contents

- [About the Data](#about-the-data)
- [Objectives](#objectives-of-the-study)
- [Dependencies](#dependencies)
- [Main Findings](#main-findings)
- [Licensing, Authors, Acknowledgements](#licensing-authors-acknowledgements)


## About the Data

The dataset has been organized in the `data` directory of this repository. Within the `data` directory, there are four subdirectories, each corresponding to a distinct quarter of the year. Specifically:

- `Dec_2022`: Contains `listings.csv` and `calendar.csv` for the period from December 2022 to March 2023.
- `Mar-2023`: Houses the data for the months from March 2023 to June 2023.
- `Jun-2023`: Provides the records for the timeframe from June 2023 to September 2023.
- `Sep-2023`: Encompasses the listings and calendar data for the last quarter of 2023 (September 2023 to December 2023).

Each subdirectory holds:
- **`listings.csv`**: Detailed information about the host and property such as location, price, amenities, number of bed and bathrooms, and more.
- **`calendar.csv`**: Day-wise data about the availability, price, and rental duration requirements of the listings for that particular time frame.

In our Jupyter notebook analysis, we have consolidated these separate files into a single comprehensive dataset for a holistic view of the year.

## Objectives of the Study

The primary research questions guiding this study include:
- **District-based Price Differences**: Understanding the price trends across different districts, their reputation, and location-based pricing patterns.
- **Yearly Price Dynamics**: Analyzing price variations throughout the year, impacts of inflation, and how booking times influence prices.
- **Listing Properties and Their Effect on Price**: Identifying features and amenities of listings that significantly influence pricing.
- **Most Influential Factors on Price**: Finding out which features influence price the most by using information theory and machine learning.

## Dependencies

To run the Jupyter notebook associated with this study, the following libraries and dependencies are required:

- pandas
- glob
- numpy
- seaborn
- matplotlib
- scikit-learn

Ensure that these libraries are installed in your environment before executing the code.

## Main Findings

To delve into the main findings of this analysis, please refer to our [blog post](<https://marius-frank.github.io>). It provides an extensive breakdown of the insights derived from the study.

The main findings can be summarized as follows:
- Prices in Berlin's AirBnB market are predominantly mid-range, catering to a broad audience.
- Location emerges as a consistent determinant of price, with central areas being both popular and pricier.
- Prices have seen a steady ascent throughout 2023, hinting to the high inflation in 2023 as a key driver of price.
- Amenities, while influential, seem secondary to location and guest feedback in dictating prices. However, invesing in some convenient amenities might be beneficial for hosts in order to demand higher prices.
- All in all, these findings suggest that profit oriented investors or wealthy individuals are dictating Berlin's AirBnB market. If the fraction of private and professional listings was equal, then the number of listings in different districts should also be closer to each other.




## Licensing, Authors, Acknowledgements

The data for this analysis was obtained from [InsideAirbnb](http://insideairbnb.com/get-the-data/). Although there is no specific licensing attached to this study, it would be appreciated if any use of these results credits the author. 


