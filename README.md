# Weather Dataset using Open-Meteo API

This is a small project that shows an example of using the Open-Meteo API to get daily data for a location. This was built using an example from the Open_Meteo website with some alterations to make it more usable and straightforward. This uses only a sample of the features that are available. For more information and other API use please visit https://open-meteo.com/.

## Parameters

* lat - The Latitude of the area of interest
* long – The Longitude of the area of interest
* startDate – The date of the first day of interest structed as “YYYY-MM-DD”. See website for earliest possible date.
* endDate – The date of last day of interest structed as “YYYY-MM-DD”. There can be a slight delay to current date.
* features – A list of strings of the features names. See the official website for all features supported.
