# Airbnb Market Analysis: Columbus vs New York

## Author
Helen Kreitzer

## Project Overview
This project analyzes Airbnb listing data to compare the Columbus, Ohio and New York City markets. The goal is to help potential hosts decide when and where to list and how many listings to have, as well as if it's worth it to be a super host.

## Research Questions

1. What NYC neighborhood has the most activity (highest number of avg nights booked)?
2. What month has the highest number of booked listings (in NYC)?
3. What's the most common room type in listings from Columbus?
4. What's the average revenue difference between a host and a super host (in NYC)?
5. What's the average number of properties per host in NYC? In Columbus?

## Data Source Mapping

| # | Question | Data Needed | Source | Data Type |
|:-:|:---------|:------------|:-------|:----------|
| 1 | What NYC neighborhood has the most activity (highest number of avg nights booked)? | neighborhood, availability | listings.csv.gz | Structured |
| 2 | What month has the highest number of booked listings (in NYC)? | availability, date | calendar.csv.gz | Structured |
| 3 | What's the most common room type in listings from Columbus? | room type | listings.csv | Structured |
| 4 | What's the average revenue difference between a host and a super host (in NYC)? | host status, price, availability | listings.csv.gz, calendar.csv.gz | Structured |
| 5 | What's the average number of properties per host in NYC? In Columbus? | host_id, listing data | listings.csv (for both cities) | Structured |

## Data Overview
- **Columbus, Ohio:** [2,877] listings (as of Sept 26, 2025)
- **New York City:** [36,261] listings (as of Dec 4, 2025)
- **Primary data source:** [Inside Airbnb](http://insideairbnb.com/get-the-data)

## Project Status
- [x] Initial data exploration
- [x] Research questions defined
- [x] Data sources mapped
- [ ] Data downloaded and cleaned
- [ ] Analysis complete
- [ ] Visualizations created