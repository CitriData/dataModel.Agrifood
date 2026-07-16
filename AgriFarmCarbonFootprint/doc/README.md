<!-- 10-Header --> 
Entidad: AgriFarmCarbonFootprint 
=================
<!-- /10-Header -->
 
<!-- 15-License -->



<!-- /15-License -->
 
<!-- 20-Description -->
 


Descripción global: **This data model is designed to store geospatial and agronomic attributes of citrus farm plots in Andalusia, including soil characteristics, land use, irrigation, erosion indicators, and organic carbon metrics.**. 


versión: 0.0.1 
<!-- /20-Description -->
 
<!-- 30-PropertiesList -->
 


## Lista de propiedades 


<sup><sub>[*] Si no hay un tipo en un atributo es porque puede tener varios tipos o diferentes formatos/patrones</sub></sup>. 


- `id[string]`: Unique identifier of the entity.


- `type[string]`: Property. NGSI Entity Type. It has to be AgriFarmCarbonFootprint.


- `area[number]`: Property. Model:'https://schema.org/Number'. Area.


- `regadio[number]`: Property. Model:'https://schema.org/Number'. Irrigated land.


- `pdtMedia[number]`: Property. Model:'https://schema.org/Number'. Average slope.


- `densidad[number]`: Property. Model:'https://schema.org/Number'. Density.


- `cob[string]`: Property. Model:'https://schema.org/Text'. Coverage (Yes/No).


- `cobType[string]`: Property. Model:'https://schema.org/Text'. Coverage Type.


- `eroCau[number]`: Property. Model:'https://schema.org/Number'. Gully erosion code.


- `eroEol[number]`: Property. Model:'https://schema.org/Number'. Wind erosion code.


- `eroLam[number]`: Property. Model:'https://schema.org/Number'. Sheet erosion code.


- `eroPot[number]`: Property. Model:'https://schema.org/Number'. Potential erosion code.


- `movMasas[number]`: Property. Model:'https://schema.org/Number'. Mass movement code.


- `codPais[string]`: Property. Model:'https://schema.org/Text'. Country code.


- `nomPais[string]`: Property. Model:'https://schema.org/Text'. Country name.


- `codComunidad[number]`: Property. Model:'https://schema.org/Number'. Autonomous community code.


- `nomComunidad[string]`: Property. Model:'https://schema.org/Text'. Autonomous community name.


- `codProvincia[number]`: Property. Model:'https://schema.org/Number'. Province code.


- `nomProvincia[string]`: Property. Model:'https://schema.org/Text'. Province name.


- `codMunicipio[number]`: Property. Model:'https://schema.org/Number'. Municipality code.


- `nomMunicipio[string]`: Property. Model:'https://schema.org/Text'. Municipality name.


- `codZona[number]`: Property. Model:'https://schema.org/Number'. Zone code.


- `codPoligono[number]`: Property. Model:'https://schema.org/Number'. Polygon code.


- `codParcela[number]`: Property. Model:'https://schema.org/Number'. Parcel code.


- `dateLoad[string]`: Property. Model:'https://schema.org/Text'. Reference year for values.


- `co30mean[number]`: Property. Model:'https://schema.org/Number'. Organic Carbon Mean (30).


- `co60mean[number]`: Property. Model:'https://schema.org/Number'. Organic Carbon Mean (60).


- `dataOwner[string]`: Property. Model:'https://schema.org/Text'. Data owner.


- `dataProvider[string]`: Property. Model:'https://schema.org/Text'. Data provider.


- `lat[number]`: Property. Model:'https://schema.org/Number'. Latitude.


- `lon[number]`: Property. Model:'https://schema.org/Number'. Longitude.


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
AgriFarmCarbonFootprint:   
  $schema: "http://json-schema.org/draft-07/schema#"   
  $id: "https://github.com/CitriData/dataModel.Agrifood/blob/main/AgriFarmCarbonFootprint/schema.json"   
  title: AgriFarmCarbonFootprint   
  description: This data model is designed to store geospatial and agronomic attributes of citrus farm plots in Andalusia, including soil characteristics, land use, irrigation, erosion indicators, and organic carbon metrics.   
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
   description: Property. NGSI Entity Type. It has to be AgriFarmCarbonFootprint.   
   enum:   
  - AgriFarmCarbonFootprint   
 area:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Area."   
 regadio:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Irrigated land."   
 pdtMedia:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Average slope."   
 densidad:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Density."   
 cob:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Coverage (Yes/No)."   
 cobType:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Coverage Type."   
 eroCau:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Gully erosion code."   
 eroEol:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Wind erosion code."   
 eroLam:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Sheet erosion code."   
 eroPot:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Potential erosion code."   
 movMasas:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Mass movement code."   
 codPais:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Country code."   
 nomPais:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Country name."   
 codComunidad:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Autonomous community code."   
 nomComunidad:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Autonomous community name."   
 codProvincia:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Province code."   
 nomProvincia:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Province name."   
 codMunicipio:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Municipality code."   
 nomMunicipio:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Municipality name."   
 codZona:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Zone code."   
 codPoligono:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Polygon code."   
 codParcela:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Parcel code."   
 dateLoad:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Reference year for values."   
 co30mean:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Organic Carbon Mean (30)."   
 co60mean:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Organic Carbon Mean (60)."   
 dataOwner:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Data owner."   
 dataProvider:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Data provider."   
 lat:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Latitude."   
 lon:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Longitude."   


``` 
</details>   
<!-- /60-ModelYaml -->
 
<!-- 70-MiddleNotes -->
 
<!-- /70-MiddleNotes -->
 
<!-- 80-Examples -->
 


## Ejemplo de carga útil 


#### AgriFarmCarbonFootprint NGSI-v2 key-values Ejemplo 


Aquí hay un ejemplo básico en formato key-values. 
<details><summary><strong>show/hide example</strong></summary>   


```json  
{
  "entity_id": "ES.61.14.49.12.69.1",
  "type": "AgriFarmCarbonFootprint",
  "area": 292.739990234375,
  "regadio": 100,
  "pdtMedia": 9.5,
  "densidad": 0.9460978507995604,
  "cob": "Desconocido",
  "cobType": "Desconocido",
  "eroCau": 2,
  "eroEol": 2,
  "eroLam": 3,
  "eroPot": 4,
  "movMasas": 3,
  "codPais": "ES",
  "nomPais": "España",
  "codComunidad": 61,
  "nomComunidad": "Andalucía",
  "codProvincia": 4,
  "nomProvincia": "Almería",
  "codMunicipio": 16,
  "nomMunicipio": "Antas",
  "codZona": 8,
  "codPoligono": 276,
  "codParcela": 1,
  "dateLoad": "2022",
  "co30mean": 1.0139645338058472,
  "co60mean": 0.6436573266983032,
  "dataOwner": "CitriData (c) 2025",
  "dataProvider": "Plataforma AgroFIWARE",
  "lat": 37.24485397338867,
  "lon": -1.9314427375793457
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