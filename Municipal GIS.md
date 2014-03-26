# Municipal GIS Data

## Source

Many (all?) municipalities possess and provide GIS data about that municipality, and frequently have departments of employees whose job is the production and management of that data. This would presumably need to be acquired directly from municipalities, unless there are one or more existing timely, authoritative aggregators. Sometimes that data can be harvested from their website (e.g., [Albemarle County, VA](http://www.albemarle.org/department.asp?department=gds&relpage=3914)), sometimes the data can only be browsed via a map interface (see [Washington D.C.'s map site](http://atlasplus.dcgis.dc.gov/)), and sometimes the municipality provides no GIS on the internet.

## Types of data

* property boundaries
* assessments
* zoning
* easements

## Examples of uses

* creating a centralized repository of GIS data for an MSA/state/country
* collecting a single type of data that crosses municipal boundaries
  * show every 2 acre parcel zoned "commercial," fronting a state highway, assessed at less than $100,000, that's within 20 miles of a given city
  * map the route of a buried water pipe across six counties
* create an open geocoder, e.g. [OpenAddresses](https://github.com/openaddresses/openaddresses/)

## Related efforts

* DataMade's [address matching tool](https://github.com/datamade/address-matching)
* OpenAddresses' [just-begun collection of municipal GIS data sources](https://github.com/openaddresses/openaddresses/tree/master/sources)
