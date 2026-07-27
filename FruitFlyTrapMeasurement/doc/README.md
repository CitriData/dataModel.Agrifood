<!-- 10-Header --> 
Entidad: FruitFlyTrapMeasurement 
=================
<!-- /10-Header -->
 
<!-- 15-License -->

<!-- /15-License -->
 
<!-- 20-Description -->
 

Descripción global: **Monitoring of Ceratitis capitata in Andalusian citrus polygons from 2023 and 2024. Weekly data**. 

versión: 0.0.1 
<!-- /20-Description -->
 
<!-- 30-PropertiesList -->
 

## Lista de propiedades 

<sup><sub>[*] Si no hay un tipo en un atributo es porque puede tener varios tipos o diferentes formatos/patrones</sub></sup>. 

- `id[string]`: Unique identifier of the entity.

- `type[string]`: Property. NGSI Entity Type. It has to be FruitFlyTrapMeasurement.

- `datecreate[string]`: Property. Model:'https://schema.org/Text'. Creation Date.

- `dataOwner[string]`: Property. Model:'https://schema.org/Text'. Data Owner.

- `dataProvider[string]`: Property. Model:'https://schema.org/Text'. Data Provider.

- `dateLoad[string]`: Property. Model:'https://schema.org/Text'. Reference year of values.

- `deraAltim[string]`: Property. Model:'https://schema.org/Text'. Altimetry Value Code.

- `deraArea[string]`: Property. Model:'https://schema.org/Text'. Landscape Areas Code.

- `deraDomin[string]`: Property. Model:'https://schema.org/Text'. Physiographic Domain Code.

- `deraFisio[string]`: Property. Model:'https://schema.org/Text'. Unique Physiographic Value Code.

- `deraNombre[string]`: Property. Model:'https://schema.org/Text'. Landscape Name Code.

- `deraPaisaje[string]`: Property. Model:'https://schema.org/Text'. Landscape Type Code.

- `deraRango[string]`: Property. Model:'https://schema.org/Text'. Altimetric range.

- `deraSist[string]`: Property. Model:'https://schema.org/Text'. Terrestrial Physiographic System Code.

- `deraTipo[string]`: Property. Model:'https://schema.org/Text'. Climate Type Code.

- `deraUnidad[string]`: Property. Model:'https://schema.org/Text'. Terrestrial Physiographic Unit Code.

- `flyCapture[number]`: Property. Model:'https://schema.org/Number'. Total captures.

- `flyTraps[number]`: Property. Model:'https://schema.org/Number'. Traps per polygon.

- `lat[number]`: Property. Model:'https://schema.org/Number'. Centroid latitude of the polygon.

- `location[string]`: Property. Model:'https://schema.org/Text'. Latitude/Longitude.

- `lon[number]`: Property. Model:'https://schema.org/Number'. Centroid longitude of the polygon.

- `mtd[number]`: Property. Model:'https://schema.org/Number'. Fly Trap Day.

- `nWeek[number]`: Property. Model:'https://schema.org/Number'. Week Number.

- `nuArea[number]`: Property. Model:'https://schema.org/Number'. Units: 'm²'. Total area of citrus parcels in the Polygon.

- `pdteAvg[number]`: Property. Model:'https://schema.org/Number'. Units: '%'. Average slope of the Polygon.

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
FruitFlyTrapMeasurement:   
  $schema: "http://json-schema.org/draft-07/schema#"   
  $id: "https://github.com/CitriData/dataModel.Agrifood/blob/main/FruitFlyTrapMeasurement/schema.json"   
  title: FruitFlyTrapMeasurement   
  description: Monitoring of Ceratitis capitata in Andalusian citrus polygons from 2023 and 2024. Weekly data.   
  type: object   
  required:   
 - id   
 - type   
  properties:   
 id:   
   type: string   
   format: uri   
   description: Unique identifier of the entity.   
 type:   
   type: string   
   description: Property. NGSI Entity Type. It has to be FruitFlyTrapMeasurement.   
   enum:   
  - FruitFlyTrapMeasurement   
 datecreate:   
   type: string   
   format: date-time   
   description: "Property. Model:'https://schema.org/Text'. Creation Date."   
 dataOwner:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Data Owner."   
 dataProvider:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Data Provider."   
 dateLoad:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Reference year of values."   
 deraAltim:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Altimetry Value Code."   
 deraArea:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Landscape Areas Code."   
 deraDomin:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Physiographic Domain Code."   
 deraFisio:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Unique Physiographic Value Code."   
 deraNombre:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Landscape Name Code."   
 deraPaisaje:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Landscape Type Code."   
 deraRango:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Altimetric range."   
 deraSist:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Terrestrial Physiographic System Code."   
 deraTipo:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Climate Type Code."   
 deraUnidad:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Terrestrial Physiographic Unit Code."   
 flyCapture:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Total captures."   
 flyTraps:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Traps per polygon."   
 lat:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Centroid latitude of the polygon."   
 location:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Latitude/Longitude."   
 lon:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Centroid longitude of the polygon."   
 mtd:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Fly Trap Day."   
 nWeek:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Week Number."   
 nuArea:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: 'm²'. Total area of citrus parcels in the Polygon."   
 pdteAvg:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: '%'. Average slope of the Polygon."   

``` 
</details>   
<!-- /60-ModelYaml -->
 
<!-- 70-MiddleNotes -->
 
<!-- /70-MiddleNotes -->
 
<!-- 80-Examples -->
 

## Ejemplo de carga útil 

#### FruitFlyTrapMeasurement NGSI-v2 key-values Ejemplo 

Aquí hay un ejemplo básico en formato key-values. 
<details><summary><strong>show/hide example</strong></summary>   

```json  

{
  "id": "ES.61.11.13.2.26.5",
  "type": "FruitFlyTrapMeasurement",
  "dateLoad": "2023",
  "nWeek": 24,
  "flyCapture": 8,
  "flyTraps": 2,
  "mtd": 0.57,
  "nuArea": 742026.625,
  "pdteAvg": 7.2,
  "deraAltim": "0105.1.001",
  "deraArea": "0602.3.004",
  "deraDomin": "0413.5.001",
  "deraFisio": "0413.4.004",
  "deraNombre": "0602.1.008",
  "deraPaisaje": "0602.2.002",
  "deraRango": "0105.2.001",
  "deraSist": "0413.3.002",
  "deraTipo": "0405.2.005",
  "deraUnidad": "0413.2.002",
  "lat": 36.282081604003906,
  "lon": -5.411695957183838,
  "dataOwner": "CitriData (c) 2025",
  "dataProvider": "Plataforma AgroFIWARE"
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
