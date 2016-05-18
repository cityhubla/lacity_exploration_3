# lacity_exploration_3

![Alt Text](https://raw.githubusercontent.com/cityhubla/lacity_exploration_3/master/laex1_chart.PNG)

##This is an exploration identifying
* Properties identified as Single Family Residences (SFR) in the City of Los Angeles.
* A chart was created showing how many properties are based on the assessed land base year and a comparision of those properties with those rolled back by Proposition 13 (A California Voter's Initiative passed in 1978 reducing property tax rates on homes, businesses and farms).
* Data was filtered by 
 * `TaxRateArea_CITY` = LOS ANGELES
 * `PropertyType` = SFR
* Data for chart made using pivot tables in Excel (data can be downloaded on this repo)
 * This chart used attributes in `LandBaseYear`, which is the "Land base year established by Proposition 13. Changes to land base year are triggered only by re-appraisable change-of-ownership." -LA COUNTY Open Data Portal
 * This chart does not include the attributes in `ImpBaseYear`, which is the "Improvement base year established by Proposition 13. Changes to improvement base year are triggered only by re-appraisable change-of-ownership or major new construction." - LA County Open Data Portal
 * This chart does not include condos, as they are listed as a separate `PropertyType`. The total number of Condos is 95,273 and the total number of Condo Conversions is 24,914

##Sources
* 2015 LA County Assessor Data, [LA County Open Data Portal](https://data.lacounty.gov/Parcel-/Assessor-Parcels-Data-2015/hvzm-fn38)
* Proposition 13 Info, [www.californiataxdata.com](http://www.californiataxdata.com/pdf/Prop13.pdf)

##Discrepancies
* The data was provided by the LA County Assessor through the County's Open Data Portal, there will be some errors.

##Next Steps
* Chart Commerical Properties using `LandBaseYear`
