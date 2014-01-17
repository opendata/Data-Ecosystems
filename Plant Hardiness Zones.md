# USDA Plant Hardiness Zones

[The U.S. Department of Agriculture defines the boundaries of each plant hardiness zone](http://planthardiness.ars.usda.gov/PHZMWeb/), using climate data to allow people to know which plants are able to grow at their location. But there is no API, and [the bulk downloads](http://planthardiness.ars.usda.gov/PHZMWeb/Downloads.aspx) are not useful to most people. Maps are provided as graphics, but data files are [sold via Climate Source](http://climatesource.com/cgi-bin/csshop/us2010b.html), a private company, for $300 per region, with the U.S. comprised of 19 regions. 

It's possible that the USDA has a contract with Climate Source that make this data impractical or legally impossible to be freed. Ideally, these data would be available as GeoJSON, and there'd be a public API to allow lat/lon pairs to be provided in exchange for a hardiness zone.
