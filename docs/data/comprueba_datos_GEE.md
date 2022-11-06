
Comprobar que se realiza bien la extracción de los puntos, i.e. que cada punto que le proporcionamos a GEE descarga datos de EVI de una zona mas o menos homogénea y que no coincide con la esquina de un pixel. 

- Descargo una imagen de MODIS MOD13Q1 (en formato hdf) de Earth data explorer https://search.earthdata.nasa.gov/search
- Tengo que seleccionar el tile h17v05 que es la zona de interés
- Lo abro en QQIS y recorto por extensión de interés (en este caso SN)
- Exporto el tiff como pixel_mod13q1_sn.tiff 

- En QGIS incorporo los puntos de las parcelas y exploro. 