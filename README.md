# Liikennemerkit

Yksinkertainen visualisointidemo Turun kaupungin liikennemerkkidatasta. 

Data muokattu komennolla ` ogr2ogr.exe -f GeoJSON -sql "select signtype,signdrager,signtext,fid_ from turun_liikennemerkit_3877" -lco RFC7946=YES target.geojson`
, alkuperäisessä API-rajapinnan kautta haetussa datassa ei ollut `fid_`-kenttää.

# Lisenssi
 * Koodi: MIT 
 * Data: data &copy; [Turun kaupunki](http://www.lounaistieto.fi/blog/2016/03/30/turun-kaupungin-liikennemerkit/) [CC BY 4.0](https://creativecommons.org/licences/by/4.0/deed.fi)