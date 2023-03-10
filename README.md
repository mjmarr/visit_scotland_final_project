## CodeClan final project

# Visit Scotland Tourism Analysis :sunrise_over_mountains: 

## Brief :scroll:

VisitScotland.com is the official consumer website of VisitScotland, Scotland's national tourist board.

Working closely with private businesses, public agencies and local authorities, we work to ensure that our visitors experience the very best of Scotland and that the country makes the most of its outstanding tourism assets and realises its potential.

To do this, VisitScotland:

 * markets Scotland to all parts of the world to attract visitors.
 * provides information and inspiration to visitors and potential visitors so they get the best out of a visit to Scotland.
 * provides quality assurance to visitors and quality advice to our industry partners to help the industry meet - and strive to exceed - visitors' expectations.

## Data Used :books:
Visit Scotland tourism open data which is freely available to download from the the links below.

| Dataset Name | link to data|
|--------------|-------------|
Council Areas|[here](https://www.opendata.nhs.scot/sl/dataset/geography-codes-and-labels/resource/967937c4-8d67-4f39-974f-fd58c4acfda5)
Regional Domestic Tourism|[here](https://statistics.gov.scot/resource?uri=http%3A%2F%2Fstatistics.gov.scot%2Fdata%2Fregional-domestic-tourism)
Scottish Accomodation Occupancy|[here](https://statistics.gov.scot/resource?uri=http%3A%2F%2Fstatistics.gov.scot%2Fdata%2Fscottish-accommodation-occupancy)
Tourism Day Visits - Activities|[here](https://statistics.gov.scot/resource?uri=http%3A%2F%2Fstatistics.gov.scot%2Fdata%2Ftourism-day-visits---activities)
Tourism Day Visits - Demographics|[here](https://statistics.gov.scot/resource?uri=http%3A%2F%2Fstatistics.gov.scot%2Fdata%2Ftourism-day-visits---demographics)
Tourism Day Visits - Location|[here](https://statistics.gov.scot/resource?uri=http%3A%2F%2Fstatistics.gov.scot%2Fdata%2Ftourism-day-visits---location)
Tourism Day Visits - Transport|[here](https://statistics.gov.scot/resource?uri=http%3A%2F%2Fstatistics.gov.scot%2Fdata%2Ftourism-day-visits---transport)
International Passenger Survey Scotland|[here](https://tourismobservatory.scot/insights/international-visitors-to-scotland)

## Data cleaning :hammer:
The cleaning steps can be found [here..](data/data_cleaning.ipynb)

specific cleaning for Q8 clustering testing etc can be found [here..](data/extra_cleaning.ipynb) data produced from this can be found [here](data/clean_data/countries/)

## Analysis :notebook_with_decorative_cover:
All the analysis using the data can be found [here..](analysis/analysis.ipynb)
Machine learning for Q8: 
- Clustering can be found [here..](analysis/q8_clustering.ipynb)
- Predicting can be found [here..](analysis/q8_prediction.ipynb)
