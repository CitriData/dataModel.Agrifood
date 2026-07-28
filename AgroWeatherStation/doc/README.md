<!-- 10-Header --> 
Entidad: AgroWeatherStation 
=================
<!-- /10-Header -->
 
<!-- 15-License -->

<!-- /15-License -->
 
<!-- 20-Description -->
 

Descripción global: **Standard Smart Data Model proposed for datasets from agricultural weather stations, including both physical and virtual stations based on prediction models and high-resolution meteorological reanalysis.**. 

versión: 0.0.1 
<!-- /20-Description -->
 
<!-- 30-PropertiesList -->
 

## Lista de propiedades 

<sup><sub>[*] Si no hay un tipo en un atributo es porque puede tener varios tipos o diferentes formatos/patrones</sub></sup>. 

- `type[string]`: Property. NGSI Entity Type. It has to be AgroWeatherStation.

- `temperature[number]`: Property. Model:'https://schema.org/Number'.Units: 'ºC'. Temperature.

- `humidity[number]`: Property. Model:'https://schema.org/Number'.Units: '%'. Humidity.

- `radiacion[number]`: Property. Model:'https://schema.org/Number'.Units: 'W/m2'. Radiation.

- `windDir[number]`: Property. Model:'https://schema.org/Number'.Units: 'º from North'. Wind Direction.

- `windVel[number]`: Property. Model:'https://schema.org/Number'.Units: 'm/s'. Wind Speed.

- `pluviometer[number]`: Property. Model:'https://schema.org/Number'.Units: 'mm'. Precipitation.

- `dataOwner[string]`: Property. Model:'https://schema.org/Text'. Data Owner.

- `dataProvider[string]`: Property. Model:'https://schema.org/Text'. Data Provider.

- `location[string]`: Property. Model:'https://schema.org/GeoCoordinates'. Latitude/Longitude.

- `datecreate[string]`: Property. Model:'https://schema.org/Text'. Update.

<!-- /30-PropertiesList -->
 
<!-- 35-RequiredProperties -->
 

Propiedades requeridas 

- `id`  

- `type`  

<!-- /35-RequiredProperties -->
 
 
<!-- 50-DataModelHeader -->
 

## Descripción de las propiedades del modelo de datos 

Ordenados alfabéticamente (pulse para más detalles) 
<!-- /50-DataModelHeader -->
 
<!-- 60-ModelYaml -->
 
<details><summary><strong>full yaml details</strong></summary>   

```yaml 
AgroWeatherStation:   
  $schema: "http://json-schema.org/draft-07/schema#"   
  $id: "https://github.com/CitriData/dataModel.Agrifood/blob/main/AgroWeatherStation/schema.json"   
  title: AgroWeatherStation   
  description: Standard Smart Data Model proposed for datasets from agricultural weather stations, including both physical and virtual stations based on prediction models and high-resolution meteorological reanalysis.   
  type: object   
  required:   
 - id   
 - type   
  properties:   
 type:   
   type: string   
   description: Property. NGSI Entity Type. It has to be AgroWeatherStation.   
   enum:   
  - AgroWeatherStation     
 temperature:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'.Units: 'ºC'. Temperature."   
 humidity:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'.Units: '%'. Humidity."   
 radiacion:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'.Units: 'W/m2'. Radiation."   
 windDir:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'.Units: 'º from North'. Wind Direction."   
 windVel:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'.Units: 'm/s'. Wind Speed."   
 pluviometer:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'.Units: 'mm'. Precipitation."   
 dataOwner:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Data Owner."   
 dataProvider:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Data Provider."   
 location:   
   type: string   
   description: "Property. Model:'https://schema.org/GeoCoordinates'. Latitude/Longitude."   
 datecreate:   
   type: string   
   format: date-time   
   description: "Property. Model:'https://schema.org/Text'. Update."   

``` 
</details>   
<!-- /60-ModelYaml -->
 
<!-- 70-MiddleNotes -->
 
<!-- /70-MiddleNotes -->
 
<!-- 80-Examples -->
 

## Ejemplo de carga útil 

#### AgroWeatherStation NGSI-v2 key-values Ejemplo 

Aquí hay un ejemplo básico en formato key-values. 
<details><summary><strong>show/hide example</strong></summary>   

```json  

{
  "type": "AgroWeatherStation",
  "id": "urn:ngsi-ld:citri.em.siar:siar-co01",
  "datecreate": "2026-07-28T00:00:00.000Z",
  "temperature": 22.889999389648438,
  "humidity": 36.29999923706055,
  "pluviometer": 0,
  "radiacion": 0,
  "windDir": 57.93000030517578,
  "windVel": 0.0860000029206276,
  "dataOwner": "Red de estaciones SIAR",
  "dataProvider": "Plataforma AgroFIWARE",
  "location": {
    "type": "Point",
    "coordinates": [
      -5.20956346230389,
      38.25439453383958
    ]
  }
}

```  
</details> 
<!-- /80-Examples -->
 
<!-- 90-FooterNotes -->
 
<!-- /90-FooterNotes -->
 
<!-- 95-Units -->
 

Consulte [FAQ 10](https://smartdatamodels.org/index.php/faqs/) para obtener una respuesta sobre cómo tratar las unidades de magnitud. 
<!-- /95-Units -->
 
<!-- 97-LastFooter -->
 
--- 

[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->
