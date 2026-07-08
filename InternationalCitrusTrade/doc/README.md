<!-- 10-Header --> 
[ 

Entidad: InternationalCitrusTrade 
=================
<!-- /10-Header -->
 
<!-- 15-License -->

<!-- /15-License -->
 
<!-- 20-Description -->
 

Descripción global: **Data model for international trade statistics of citrus products, based on sources such as UN Comtrade and aligned with global trade data standards. It captures key variables including origin/destination countries, HS codes, trade values, volumes, and time periods. Designed to support consistent analysis, comparison, and integration with economic data systems.**. 

versión: 0.0.1 
<!-- /20-Description -->
 
<!-- 30-PropertiesList -->
 

## Lista de propiedades 

<sup><sub>[*] Si no hay un tipo en un atributo es porque puede tener varios tipos o diferentes formatos/patrones</sub></sup>. 

- `id[string]`: Unique identifier of the entity.

- `aggrLevel[number]`: Property. Model:'https://schema.org/Number'. Units: 'Code'. Level of data aggregation. . Model: [https://schema.org/Number](https://schema.org/Number)

- `altQty[number]`: Property. Model:'https://schema.org/Number'. Units: 'altQtyUnitAbbr'. Alternative trade quantity if applicable. . Model: [https://schema.org/Number](https://schema.org/Number)

- `altQtyUnitAbbr[string]`: Property. Model:'https://schema.org/Text'. Units: 'Alternative units'. Abbreviation of the alternative quantity unit. . Model: [https://schema.org/Text](https://schema.org/Text)

- `altQtyUnitCode[number]`: Property. Model:'https://schema.org/Number'. Units: 'Code'. Code for the alternative quantity unit. . Model: [https://schema.org/Number](https://schema.org/Number)

- `cifvalue[number]`: Property. Model:'https://schema.org/Number'. Units: 'USD ($)'. Cost, Insurance, and Freight (CIF) value. . Model: [https://schema.org/Number](https://schema.org/Number)

- `classificationCode[string]`: Property. Model:'https://schema.org/Text'. Units: 'Code'. Product classification code. . Model: [https://schema.org/Text](https://schema.org/Text)

- `classificationSearchCode[string]`: Property. Model:'https://schema.org/Text'. Units: 'Code'. Search code used for the classification. . Model: [https://schema.org/Text](https://schema.org/Text)

- `cmdDesc[string]`: Property. Model:'https://schema.org/Text'. Units: 'Products'. Commodity description . Model: [https://schema.org/Text](https://schema.org/Text)

- `customsCode[string]`: Property. Model:'https://schema.org/Text'. Units: 'Code'. Customs procedure code. . Model: [https://schema.org/Text](https://schema.org/Text)

- `customsDesc[string]`: Property. Model:'https://schema.org/Text'. Units: 'Customs Procedure'. Description of the customs procedure. . Model: [https://schema.org/Text](https://schema.org/Text)

- `flowCode[string]`: Property. Model:'https://schema.org/Text'. Units: 'Code'. Code identifying the trade flow type. . Model: [https://schema.org/Text](https://schema.org/Text)

- `flowDesc[string]`: Property. Model:'https://schema.org/Text'. Units: 'Flow'. Description of the trade flow . Model: [https://schema.org/Text](https://schema.org/Text)

- `fobvalue[number]`: Property. Model:'https://schema.org/Number'. Units: 'USD ($)'. Free on Board (FOB) value. . Model: [https://schema.org/Number](https://schema.org/Number)

- `freqCode[string]`: Property. Model:'https://schema.org/Text'. Units: 'Monthly'. Frequency code. . Model: [https://schema.org/Text](https://schema.org/Text)

- `grossWgt[number]`: Property. Model:'https://schema.org/Number'. Units: 'kg'. Gross weight. . Model: [https://schema.org/Number](https://schema.org/Number)


- `isAggregate[boolean]`: Property. Model:'https://schema.org/Boolean'. Units: 'true/false'. Flag indicating if the data is aggregated. . Model: [https://schema.org/Boolean](https://schema.org/Boolean)

- `isAltQtyEstimated[boolean]`: Property. Model:'https://schema.org/Boolean'. Units: 'true/false'. Flag indicating if the alternative quantity is estimated. . Model: [https://schema.org/Boolean](https://schema.org/Boolean)

- `isGrossWgtEstimated[boolean]`: Property. Model:'https://schema.org/Boolean'. Units: 'true/false'. Flag indicating if the gross weight is estimated. . Model: [https://schema.org/Boolean](https://schema.org/Boolean)

- `isLeaf[boolean]`: Property. Model:'https://schema.org/Boolean'. Units: 'true/false'. Flag indicating if this is the lowest level of the product classification tree. . Model: [https://schema.org/Boolean](https://schema.org/Boolean)

- `isNetWgtEstimated[boolean]`: Property. Model:'https://schema.org/Boolean'. Units: 'true/false'. Flag indicating if the net weight is estimated. . Model: [https://schema.org/Boolean](https://schema.org/Boolean)

- `isOriginalClassification[boolean]`: Property. Model:'https://schema.org/Boolean'. Units: 'true/false'. Flag indicating if original classification was used. . Model: [https://schema.org/Boolean](https://schema.org/Boolean)

- `isQtyEstimated[boolean]`: Property. Model:'https://schema.org/Boolean'. Units: 'true/false'. Flag indicating if the quantity is estimated. . Model: [https://schema.org/Boolean](https://schema.org/Boolean)

- `isReported[boolean]`: Property. Model:'https://schema.org/Boolean'. Units: 'true/false'. Flag indicating if the data was explicitly reported by the country. . Model: [https://schema.org/Boolean](https://schema.org/Boolean)

- `legacyEstimationFlag[string]`: Property. Model:'https://schema.org/Text'. Units: 'Code'. Legacy system flag for estimations. . Model: [https://schema.org/Text](https://schema.org/Text)

- `mosCode[string]`: Property. Model:'https://schema.org/Text'. Units: 'Code'. Mode of Supply code. . Model: [https://schema.org/Text](https://schema.org/Text)

- `motCode[string]`: Property. Model:'https://schema.org/Text'. Units: 'Code'. Mode of Transport code. . Model: [https://schema.org/Text](https://schema.org/Text)

- `motDesc[string]`: Property. Model:'https://schema.org/Text'. Units: 'Mode of Transport'. Mode of Transport description. . Model: [https://schema.org/Text](https://schema.org/Text)

- `netWgt[number]`: Property. Model:'https://schema.org/Number'. Units: 'kg'. Net weight. . Model: [https://schema.org/Number](https://schema.org/Number)

- `partner2Code[string]`: Property. Model:'https://schema.org/Text'. Units: 'Code'. Code of the secondary partner country. . Model: [https://schema.org/Text](https://schema.org/Text)

- `partner2Desc[string]`: Property. Model:'https://schema.org/Text'. Units: 'Country'. Description of the second partner country. . Model: [https://schema.org/Text](https://schema.org/Text)

- `partner2ISO[string]`: Property. Model:'https://schema.org/Text'. Units: 'ISO Code'. ISO Code of the secondary partner country. . Model: [https://schema.org/Text](https://schema.org/Text)

- `partnerCode[string]`: Property. Model:'https://schema.org/Text'. Units: 'Code'. Code of the primary partner country. . Model: [https://schema.org/Text](https://schema.org/Text)

- `partnerDesc[string]`: Property. Model:'https://schema.org/Text'. Units: 'Country'. Primary trading partner country or region. . Model: [https://schema.org/Text](https://schema.org/Text)

- `partnerISO[string]`: Property. Model:'https://schema.org/Text'. Units: 'ISO Code'. ISO code of the primary partner country. . Model: [https://schema.org/Text](https://schema.org/Text)

- `period[string]`: Property. Model:'https://schema.org/Text'. Units: 'YYYYMM'. The period of the trade data. . Model: [https://schema.org/Text](https://schema.org/Text)

- `primaryValue[number]`: Property. Model:'https://schema.org/Number'. Units: 'USD ($)'. The primary statistical value recorded. . Model: [https://schema.org/Number](https://schema.org/Number)

- `qty[number]`: Property. Model:'https://schema.org/Number'. Units: 'qtyUnitAbbr'. Trade quantity . Model: [https://schema.org/Number](https://schema.org/Number)

- `qtyUnitAbbr[string]`: Property. Model:'https://schema.org/Text'. Units: 'SI Units'. Abbreviation of the quantity unit. . Model: [https://schema.org/Text](https://schema.org/Text)

- `qtyUnitCode[number]`: Property. Model:'https://schema.org/Number'. Units: 'Code'. Code for the quantity unit. . Model: [https://schema.org/Number](https://schema.org/Number)

- `refMonth[number]`: Property. Model:'https://schema.org/Number'. Units: 'MM'. Reference month of the trade record. . Model: [https://schema.org/Number](https://schema.org/Number)

- `refPeriodId[string]`: Property. Model:'https://schema.org/Text'. Units: 'YYYYMM00'. Internal reference period identifier. . Model: [https://schema.org/Text](https://schema.org/Text)

- `refYear[number]`: Property. Model:'https://schema.org/Number'. Units: 'YYYY'. Reference year of the trade record. . Model: [https://schema.org/Number](https://schema.org/Number)

- `reporterCode[string]`: Property. Model:'https://schema.org/Text'. Units: 'Code'. Code of the reporting country. . Model: [https://schema.org/Text](https://schema.org/Text)

- `reporterDesc[string]`: Property. Model:'https://schema.org/Text'. Units: 'Country'. Country or region reporting the trade. . Model: [https://schema.org/Text](https://schema.org/Text)

- `reporterISO[string]`: Property. Model:'https://schema.org/Text'. Units: 'ISO Code'. ISO code of the reporting country. . Model: [https://schema.org/Text](https://schema.org/Text)

- `type[string]`: Property. NGSI Entity Type. It has to be InternationalCitrusTrade.

- `typeCode[string]`: Property. Model:'https://schema.org/Text'. Units: 'Code'. Type code of the trade record. . Model: [https://schema.org/Text](https://schema.org/Text)

<!-- /30-PropertiesList -->
 
<!-- 35-RequiredProperties -->
 

Propiedades requeridas 

- `id`  

- `type`  

- `period`  

- `reporterCode`  

- `partnerCode`  

- `flowCode`  

<!-- /35-RequiredProperties -->
 
 
<!-- 50-DataModelHeader -->
 

## Descripción de las propiedades del modelo de datos 

Ordenados alfabéticamente (pulse para más detalles) 
<!-- /50-DataModelHeader -->
 
<!-- 60-ModelYaml -->
 
<details><summary><strong>full yaml details</strong></summary>   

```yaml 
InternationalCitrusTrade:   
  $schema: "http://json-schema.org/draft-07/schema#"   
  $id: "https://github.com/CitriData/dataModel.Agrifood/blob/main/InternationalCitrusTrade/schema.json"   
  title: InternationalCitrusTrade   
  description: Data model for international trade statistics of citrus products, based on sources such as UN Comtrade and aligned with global trade data standards. It captures key variables including origin/destination countries, HS codes, trade values, volumes, and time periods. Designed to support consistent analysis, comparison, and integration with economic data systems.   
  type: object   
  required:   
 - id   
 - type   
 - period   
 - reporterCode   
 - partnerCode   
 - flowCode   
  properties:   
 id:   
   type: string   
   format: uri   
   description: Unique identifier of the entity.   
 type:   
   type: string   
   description: Property. NGSI Entity Type. It has to be InternationalCitrusTrade.   
   enum:   
  - InternationalCitrusTrade   
 cmdDesc:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'Products'. Commodity description"   
 flowDesc:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'Flow'. Description of the trade flow"   
 reporterDesc:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'Country'. Country or region reporting the trade."   
 partnerDesc:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'Country'. Primary trading partner country or region."   
 qty:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: 'qtyUnitAbbr'. Trade quantity"   
 qtyUnitAbbr:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'SI Units'. Abbreviation of the quantity unit."   
 altQty:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: 'altQtyUnitAbbr'. Alternative trade quantity if applicable."   
 altQtyUnitAbbr:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'Alternative units'. Abbreviation of the alternative quantity unit."   
 refYear:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: 'YYYY'. Reference year of the trade record."   
 refMonth:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: 'MM'. Reference month of the trade record."   
 motDesc:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'Mode of Transport'. Mode of Transport description."   
 cifvalue:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: 'USD ($)'. Cost, Insurance, and Freight (CIF) value."   
 classificationCode:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'Code'. Product classification code."   
 classificationSearchCode:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'Code'. Search code used for the classification."   
 customsCode:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'Code'. Customs procedure code."   
 customsDesc:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'Customs Procedure'. Description of the customs procedure."   
 flowCode:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'Code'. Code identifying the trade flow type."   
 fobvalue:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: 'USD ($)'. Free on Board (FOB) value."   
 freqCode:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'Monthly'. Frequency code."   
 grossWgt:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: 'kg'. Gross weight."   
 isAggregate:   
   type: boolean   
   description: "Property. Model:'https://schema.org/Boolean'. Units: 'true/false'. Flag indicating if the data is aggregated."   
 aggrLevel:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: 'Code'. Level of data aggregation."   
 isAltQtyEstimated:   
   type: boolean   
   description: "Property. Model:'https://schema.org/Boolean'. Units: 'true/false'. Flag indicating if the alternative quantity is estimated."   
 isGrossWgtEstimated:   
   type: boolean   
   description: "Property. Model:'https://schema.org/Boolean'. Units: 'true/false'. Flag indicating if the gross weight is estimated."   
 isLeaf:   
   type: boolean   
   description: "Property. Model:'https://schema.org/Boolean'. Units: 'true/false'. Flag indicating if this is the lowest level of the product classification tree."   
 isNetWgtEstimated:   
   type: boolean   
   description: "Property. Model:'https://schema.org/Boolean'. Units: 'true/false'. Flag indicating if the net weight is estimated."   
 isOriginalClassification:   
   type: boolean   
   description: "Property. Model:'https://schema.org/Boolean'. Units: 'true/false'. Flag indicating if original classification was used."   
 isQtyEstimated:   
   type: boolean   
   description: "Property. Model:'https://schema.org/Boolean'. Units: 'true/false'. Flag indicating if the quantity is estimated."   
 isReported:   
   type: boolean   
   description: "Property. Model:'https://schema.org/Boolean'. Units: 'true/false'. Flag indicating if the data was explicitly reported by the country."   
 legacyEstimationFlag:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'Code'. Legacy system flag for estimations."   
 mosCode:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'Code'. Mode of Supply code."   
 motCode:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'Code'. Mode of Transport code."   
 netWgt:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: 'kg'. Net weight."   
 partner2Code:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'Code'. Code of the secondary partner country."   
 partner2Desc:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'Country'. Description of the second partner country."   
 partner2ISO:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'ISO Code'. ISO Code of the secondary partner country."   
 partnerCode:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'Code'. Code of the primary partner country."   
 partnerISO:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'ISO Code'. ISO code of the primary partner country."   
 period:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'YYYYMM'. The period of the trade data."   
 primaryValue:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: 'USD ($)'. The primary statistical value recorded."   
 qtyUnitCode:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: 'Code'. Code for the quantity unit."   
 altQtyUnitCode:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: 'Code'. Code for the alternative quantity unit."   
 refPeriodId:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'YYYYMM00'. Internal reference period identifier."   
 reporterCode:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'Code'. Code of the reporting country."   
 reporterISO:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'ISO Code'. ISO code of the reporting country."   
 typeCode:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Units: 'Code'. Type code of the trade record."   

``` 
</details>   
<!-- /60-ModelYaml -->
 
<!-- 70-MiddleNotes -->
 
<!-- /70-MiddleNotes -->
 
<!-- 80-Examples -->
 

## Ejemplo de carga útil 

#### InternationalCitrusTrade NGSI-v2 key-values Ejemplo 

Aquí hay un ejemplo básico en formato key-values. 
<details><summary><strong>show/hide example</strong></summary>   

```json  

{  
  "id": "urn:ngsi-ld:InternationalCitrusTrade:example-001",  
  "type": "InternationalCitrusTrade",  
  "period": "exampleValue",  
  "reporterCode": "exampleValue",  
  "partnerCode": "exampleValue",  
  "flowCode": "exampleValue",  
  "cmdDesc": "example",  
  "flowDesc": "example",  
  "reporterDesc": "example",  
  "partnerDesc": "example",  
  "qty": 0,  
  "qtyUnitAbbr": "example"  
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
