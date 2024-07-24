## Calculating lengths of curved lines

### Possibilities
Calculating of river lengths represented by a set of geodetic coordinates.

### Description
We study a generalized method for measuring the lengths of curved lines based on the summation of arc lengths of inscribed circles. 
The operation of the underlying algorithm is analyzed and the results of this method are compared with the traditional method of measuring the lengths of broken lines by successive summation of segment lengths. 
Both results are compared with a benchmark. The considered algorithm takes into account the admitted errors in mapping and shows more accurate values. 

Translated with DeepL.com (free version)

### Publications
Included in the core of RINC with	eLIBRARY ID: 60717843 (https://elibrary.ru/item.asp?id=60717843)

### Input data
An entire object represented by a geojson or shp file containing latitude and longitude coordinates characterizing it. 

### Output data
Calculation results:
  * Calculating the sum of distances in meters between successive pairs of coordinates of a set on a spheroid
  * Calculating the distance using the haversine formula and the value of the Earth's radius on the spheroid
  * Calculation of the sum of distances in meters between successive pairs of set coordinates on a WGS-84 ellipsoid 

### Testing
  * fast_test
  * first_test
  * latest_test
