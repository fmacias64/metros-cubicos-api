API Metros Cúbicos
==================

API no oficial para buscar propiedades en venta y renta de Metros Cúbicos

## Endpoint

http://m.metroscubicos.com/proxy.php

### Propiedades

https://github.com/mexicapis/metros-cubicos-api/master/ejemplos/propiedades.json

| Parámetro              | Valor      |
|------------------------|------------|
| do                     | properties |
| params[propertyOp]     | 2          |
| params[propertyType]   | 8          |
| params[bathrooms]      | 0          |
| params[cars]           | 0          |
| params[development]    | 0          |
| params[rooms]          | 0          |
| params[m2cons]         | 0          |
| params[order]          | asc        |
| params[sort]           | pesosPrice |
| params[state]          | 10058      |
| params[limit]          | 15         |
| params[start]          | 0          |
| params[reduceResponse] | true       |
| params[pesosPrice]     | 1          |
| method                 | GET        |

### Búsqueda de zonas

https://github.com/mexicapis/metros-cubicos-api/master/ejemplos/zonas.json

| Parámetro              | Valor              |
|------------------------|--------------------|
| do                     | tools.autocomplete |
| params[query]          | distrito           |

### Estados

| Estado | Id                  |   
|--------|---------------------|
| 3      | Aguascalientes      |
| 906    | Baja California     |
| 2365   | Baja California Sur |
| 2774   | Campeche            |
| 3274   | Chiapas             |
| 5324   | Chihuahua           |
| 7951   | Coahuila            |
| 9623   | Colima              |
| 10058  | Distrito Federal    |
| 12366  | Durango             |
| 14205  | Estado De México    |
| 18741  | Guanajuato          |
| 22108  | Guerrero            |
| 25036  | Hidalgo             |
| 26925  | Jalisco             |
| 30038  | Michoacán           |
| 32895  | Morelos             |
| 33582  | Nayarit             |
| 34346  | Nuevo León          |
| 36784  | Oaxaca              |
| 39923  | Puebla              |
| 42671  | Querétaro           |
| 43682  | Quintana Roo        |
| 44188  | San Luis Potosí     |
| 45782  | Sinaloa             |
| 46961  | Sonora              |
| 48311  | Tabasco             |
| 49345  | Tamaulipas          |
| 51097  | Tlaxcala            |
| 51568  | Veracruz            |
| 54804  | Yucatán             |
| 55434  | Zacatecas           |
