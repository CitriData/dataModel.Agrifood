<!-- 10-Header --> 
Entidad: WholesaleMarket 
=================
<!-- /10-Header -->
 
<!-- 15-License -->

<!-- /15-License -->
 
<!-- 20-Description -->
 

Descripción global: **Data model designed to represent the activity, trading price ranges (minimum and maximum) and infrastructure of wholesale food markets (Mercas network). It allows recording the volume of incoming/outgoing goods, maximum, minimum and modal prices by product variety, and the operational management of food logistics platforms. Covering data from 2020 to 2024.This offering is restricted to citrus product varieties.**. 

versión: 0.0.1 
<!-- /20-Description -->
 
<!-- 30-PropertiesList -->
 

## Lista de propiedades 

<sup><sub>[*] Si no hay un tipo en un atributo es porque puede tener varios tipos o diferentes formatos/patrones</sub></sup>. 

- `type[string]`: Property. NGSI Entity Type. It has to be WholesaleMarket.

- `startPrice[number]`: Property. Model:'https://schema.org/Number'. Units: '€'. Start Period Price of the week.

- `endPrice[number]`: Property. Model:'https://schema.org/Number'. Units: '€'. End Period Price of the week.

- `market[string]`: Property. Model:'https://schema.org/Text'. Market.

- `product[string]`: Property. Model:'https://schema.org/Text'. Product.

- `period[string]`: Property. Model:'https://schema.org/Text'. Survey Period.

- `year[number]`: Property. Model:'https://schema.org/Number'. Year.

- `week[number]`: Property. Model:'https://schema.org/Number'. Week.

- `dataOwner[string]`: Property. Model:'https://schema.org/Text'. Data Owner.

- `dataProvider[string]`: Property. Model:'https://schema.org/Text'. Data Provider.

<!-- /30-PropertiesList -->
 
<!-- 35-RequiredProperties -->
 

Propiedades requeridas 

- `product`  

- `type`  

<!-- /35-RequiredProperties -->
 
 
<!-- 50-DataModelHeader -->
 

## Descripción de las propiedades del modelo de datos 

Ordenados alfabéticamente (pulse para más detalles) 
<!-- /50-DataModelHeader -->
 
<!-- 60-ModelYaml -->
 
<details><summary><strong>full yaml details</strong></summary>   

```yaml 
WholesaleMarket:   
  $schema: "http://json-schema.org/draft-07/schema#"   
  $id: "https://github.com/CitriData/dataModel.Agrifood/blob/main/WholesaleMarket/schema.json"   
  title: WholesaleMarket   
  description: Data model designed to represent the activity, trading price ranges (minimum and maximum) and infrastructure of wholesale food markets (Mercas network). It allows recording the volume of incoming/outgoing goods, maximum, minimum and modal prices by product variety, and the operational management of food logistics platforms. Covering data from 2020 to 2024.This offering is restricted to citrus product varieties.   
  type: object   
  required:   
 - id   
 - type   
  properties:   
 type:   
   type: string   
   description: Property. NGSI Entity Type. It has to be WholesaleMarket.   
   enum:   
  - WholesaleMarket   
 startPrice:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: '€'. Start Period Price of the week."   
 endPrice:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: '€'. End Period Price of the week."   
 market:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Market."   
 product:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Product."   
 period:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Survey Period."   
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

#### WholesaleMarket NGSI-v2 key-values Ejemplo 

Aquí hay un ejemplo básico en formato key-values. 
<details><summary><strong>show/hide example</strong></summary>   

```json  

{
  "type": "WholesaleMarket",
  "market": "Mercamadrid",
  "product": "Naranja Navel",
  "period": "202410",
  "year": 2024,
  "week": 10,
  "startPrice": 0.45,
  "endPrice": 0.52,
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
