[//]: # (WARNING: this file is automatically generated. Please find the sources at the bottom and edit those sources)

 bank 
======



<img src='https://mapcomplete.osm.be/circle:white;./assets/layers/bank/bank.svg' height="100px"> 

A financial institution to deposit money






  - This layer is shown at zoomlevel **0** and higher




#### Themes using this layer 





  - [atm](https://mapcomplete.osm.be/atm)
  - [personal](https://mapcomplete.osm.be/personal)




 Basic tags for this layer 
---------------------------



Elements must have the all of following tags to be shown on this layer:



  - <a href='https://wiki.openstreetmap.org/wiki/Key:amenity' target='_blank'>amenity</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:amenity%3Dbank' target='_blank'>bank</a>


[Execute on overpass](http://overpass-turbo.eu/?Q=%5Bout%3Ajson%5D%5Btimeout%3A90%5D%3B(%20%20%20%20nwr%5B%22amenity%22%3D%22bank%22%5D(%7B%7Bbbox%7D%7D)%3B%0A)%3Bout%20body%3B%3E%3Bout%20skel%20qt%3B)



 Supported attributes 
----------------------



Warning: 

this quick overview is incomplete



attribute | type | values which are supported by this layer
----------- | ------ | ------------------------------------------
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/atm#values) [atm](https://wiki.openstreetmap.org/wiki/Key:atm) | Multiple choice | [yes](https://wiki.openstreetmap.org/wiki/Tag:atm%3Dyes) [no](https://wiki.openstreetmap.org/wiki/Tag:atm%3Dno) [separate](https://wiki.openstreetmap.org/wiki/Tag:atm%3Dseparate)




### has_atm 



The question is  *Does this bank have an ATM?*





  - *This bank has an ATM*  corresponds with  `atm=yes`
  - *This bank does <b>not</b> have an ATM*  corresponds with  `atm=no`
  - *This bank does have an ATM, but it is mapped as a different icon*  corresponds with  `atm=separate`




#### Filters 





id | question | osmTags
---- | ---------- | ---------
open_now.0 | Opened now | _isOpen=yes




id | question | osmTags
---- | ---------- | ---------
has_atm.0 | With an ATM | atm=yes
 

This document is autogenerated from [assets/layers/bank/bank.json](https://github.com/pietervdvn/MapComplete/blob/develop/assets/layers/bank/bank.json)
