<!-- 10-Header --> 
Entidad: CitrusPriceObservatory 
=================
<!-- /10-Header -->
 
<!-- 15-License -->

<!-- /15-License -->
 
<!-- 20-Description -->
 

Descripción global: **This data model is designed to record, analyze and standardize the economic quotations and market prices of the citrus sector (oranges, mandarins, lemons, grapefruits, among others) in Andalusia from 2010 to 2025**. 

versión: 0.0.1 
<!-- /20-Description -->
 
<!-- 30-PropertiesList -->
 

## Lista de propiedades 

<sup><sub>[*] Si no hay un tipo en un atributo es porque puede tener varios tipos o diferentes formatos/patrones</sub></sup>. 

- `type[string]`: Property. NGSI Entity Type. It has to be CitrusPriceObservatory.

- `startWeek[string]`: Property. Model:'https://schema.org/Text'. Start Date.

- `endWeek[string]`: Property. Model:'https://schema.org/Text'. End Date.

- `group[string]`: Property. Model:'https://schema.org/Text'. Group.

- `sector[string]`: Property. Model:'https://schema.org/Text'. Sector.

- `subSector[string]`: Property. Model:'https://schema.org/Text'. Sub Sector.

- `product[string]`: Property. Model:'https://schema.org/Text'. Product.

- `typeProduct[string]`: Property. Model:'https://schema.org/Text'. Product Type.

- `subtypeProduct[string]`: Property. Model:'https://schema.org/Text'. Product Subtype.

- `position[string]`: Property. Model:'https://schema.org/Text'. Position.

- `category[string]`: Property. Model:'https://schema.org/Text'. Category.

- `format[string]`: Property. Model:'https://schema.org/Text'. Format.

- `channel[string]`: Property. Model:'https://schema.org/Text'. Channel.

- `price[number]`: Property. Model:'https://schema.org/Number'. Price.

- `unit[string]`: Property. Model:'https://schema.org/Text'. Unit.

- `year[number]`: Property. Model:'https://schema.org/Number'. Year.

- `week[number]`: Property. Model:'https://schema.org/Number'. Week.

- `dataOwner[string]`: Property. Model:'https://schema.org/Text'. Data Owner.

- `dataProvider[string]`: Property. Model:'https://schema.org/Text'. Data Provider.

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
CitrusPriceObservatory:   
  $schema: "http://json-schema.org/draft-07/schema#"   
  $id: "https://github.com/CitriData/dataModel.Agrifood/blob/main/CitrusPriceObservatory/schema.json"   
  title: CitrusPriceObservatory   
  description: This data model is designed to record, analyze and standardize the economic quotations and market prices of the citrus sector (oranges, mandarins, lemons, grapefruits, among others) in Andalusia from 2010 to 2025.   
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
   description: Property. NGSI Entity Type. It has to be CitrusPriceObservatory.   
   enum:   
  - CitrusPriceObservatory   
 startWeek:   
   type: string   
   format: date-time   
   description: "Property. Model:'https://schema.org/Text'. Start Date."   
 endWeek:   
   type: string   
   format: date-time   
   description: "Property. Model:'https://schema.org/Text'. End Date."   
 group:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Group."   
 sector:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Sector."   
 subSector:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Sub Sector."   
 product:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Product."   
 typeProduct:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Product Type."   
 subtypeProduct:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Product Subtype."   
 position:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Position."   
 category:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Category."   
 format:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Format."   
 channel:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Channel."   
 price:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Price."   
 unit:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Unit."   
 year:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Year."   
 week:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Week."   
 dataOwner:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Data Owner."   
 dataProvider:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Data Provider."   

``` 
</details>   
<!-- /60-ModelYaml -->
 
<!-- 70-MiddleNotes -->
 
<!-- /70-MiddleNotes -->
 
<!-- 80-Examples -->
 

## Ejemplo de carga útil 

#### CitrusPriceObservatory NGSI-v2 key-values Ejemplo 

Aquí hay un ejemplo básico en formato key-values. 
<details><summary><strong>show/hide example</strong></summary>   

```json  

{
  "type": "CitrusPriceObservatory",
  "startWeek": "2010-10-04T00:00:00.000Z",
  "endWeek": "2010-10-10T00:00:00.000Z",
  "group": "Agrícola",
  "sector": "Frutales",
  "subSector": "Cítricos",
  "product": "Limón",
  "typeProduct": "Fino O Mesero",
  "subtypeProduct": "Sin Especificar",
  "position": "Árbol",
  "category": "Sin Especificar",
  "price": 0.3400000035762787,
  "unit": "Euros/Kg",
  "week": 40,
  "year": 2010
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
