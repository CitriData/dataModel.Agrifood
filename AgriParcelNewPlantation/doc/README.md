<!-- 10-Header --> 
Entidad: AgriParcelNewPlantation 
=================
<!-- /10-Header -->
 
<!-- 15-License -->


<!-- /15-License -->
 
<!-- 20-Description -->
 

Descripción global: **Data model designed to geographically catalog and monitor newly established agricultural parcels in the municipality of Palma del Río, Córdoba (Spain). Load year: 2023.**. 

versión: 0.0.1 
<!-- /20-Description -->
 
<!-- 30-PropertiesList -->
 

## Lista de propiedades 

<sup><sub>[*] Si no hay un tipo en un atributo es porque puede tener varios tipos o diferentes formatos/patrones</sub></sup>. 

- `id[string]`: Unique identifier of the entity.

- `type[string]`: Property. NGSI Entity Type. It has to be AgriParcelNewPlantation.

- `dateLoad[string]`: Property. Model:'https://schema.org/Text'. Reference year for the values. . Model: [https://schema.org/Text](https://schema.org/Text)

- `idClasifica[string]`: Property. Model:'https://schema.org/Text'. Classification. . Model: [https://schema.org/Text](https://schema.org/Text)

- `idCobertura[string]`: Property. Model:'https://schema.org/Text'. Coverage. . Model: [https://schema.org/Text](https://schema.org/Text)

- `cambioUso[string]`: Property. Model:'https://schema.org/Text'. Land use change. . Model: [https://schema.org/Text](https://schema.org/Text)

- `location[object]`: Property. Model:'https://schema.org/GeoShape'. Array of longitude/latitude coordinates representing the geometry of the plot. . Model: [https://schema.org/GeoShape](https://schema.org/GeoShape)

- `dataProvider[string]`: Property. Model:'https://schema.org/Text'. Data provider. . Model: [https://schema.org/Text](https://schema.org/Text)

- `dataOwner[string]`: Property. Model:'https://schema.org/Text'. Data owner. . Model: [https://schema.org/Text](https://schema.org/Text)

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
AgriParcelNewPlantation:   
  $schema: "http://json-schema.org/draft-07/schema#"   
  $id: "https://github.com/CitriData/dataModel.Agrifood/blob/main/AgriParcelNewPlantation/schema.json"   
  title: AgriParcelNewPlantation   
  description: Data model designed to geographically catalog and monitor newly established agricultural parcels in the municipality of Palma del Río, Córdoba (Spain). Load year: 2023.   
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
   description: Property. NGSI Entity Type. It has to be AgriParcelNewPlantation.   
   enum:   
  - AgriParcelNewPlantation   
 dateLoad:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Reference year for the values."   
 idClasifica:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Classification."   
 idCobertura:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Coverage."   
 cambioUso:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Land use change."   
 location:   
   type: object   
   description: "Property. Model:'https://schema.org/GeoShape'. Array of longitude/latitude coordinates representing the geometry of the plot."   
 dataProvider:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Data provider."   
 dataOwner:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Data owner."   


``` 
</details>   
<!-- /60-ModelYaml -->
 
<!-- 70-MiddleNotes -->
 
<!-- /70-MiddleNotes -->
 
<!-- 80-Examples -->
 

## Ejemplo de carga útil 

#### AgriParcelNewPlantation NGSI-v2 key-values Ejemplo 

Aquí hay un ejemplo básico en formato key-values. 
<details><summary><strong>show/hide example</strong></summary>   

```json  
  {
    "entity_id": "ES.61.14.49.12.69.1",
    "idClasifica": "Plantacion Adulta",
    "idCobertura": "Primera",
    "cambioUso": "No",
    "dataOwner": "CitriData (c) 2025",
    "dataProvider": "Plataforma AgroFIWARE",
    "location": {
      "coordinates": [
        [
          [
            [
              -5.223562719782526,
              37.6768893598775
            ],
            [
              -5.22432996990794,
              37.67494126800111
            ],
            ...
            [
              -5.223562719782526,
              37.6768893598775
            ]
          ]
        ]
      ],
      "type": "MultiPolygon"
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