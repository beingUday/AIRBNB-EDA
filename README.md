# AIRBNB-EDA
# Overview
An exploratory data analysis of Airbnb listings in New York City (2019) focusing on pricing, geography, room types, availability, and host behavior, with clean sectioning, visualizations, and summary statistics to uncover patterns and support further modeling or BI reporting.

# Dataset
Shape: 48,895 rows × 13 columns after initial load and column filtering for analysis.

Core fields: id, neighbourhood_group, neighbourhood, latitude, longitude, room_type, price, minimum_nights, number_of_reviews, last_review, reviews_per_month, calculated_host_listings_count, availability_365.

Missingness: last_review and reviews_per_month contain approximately 20.56% missing values in the raw data used by the notebook’s checks before imputation.

# Objectives
Understand price distributions and outliers across boroughs and room types to assess market variance and positioning opportunities.

Examine geographic patterns using latitude and longitude to reveal spatial clustering and borough-level differences.

Assess availability and minimum stay requirements to infer supply dynamics and operational constraints.

Analyze review activity and host portfolio sizes to explore demand signals and hosting strategies.

