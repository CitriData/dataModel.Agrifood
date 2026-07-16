<!-- 10-Header --> 
Entidad: CitrusPackhouseOperation 
=================
<!-- /10-Header -->
 
<!-- 15-License -->


<!-- /15-License -->
 
<!-- 20-Description -->
 

Descripción global: **Data model designed for operational management and traceability in the citrus transformation and packing industry. It records raw-material batch intake, quality parameters (calibers, ripeness, etc.), control of processing/packing operations, and finished-product inventory ready for distribution. It combines industry-supplied data on suppliers' parcels with parcel attributes extracted from SIGPAC. Sensitive identifiers are anonymized by hashing.**. 

versión: 0.0.1 
<!-- /20-Description -->
 
<!-- 30-PropertiesList -->
 

## Lista de propiedades 

<sup><sub>[*] Si no hay un tipo en un atributo es porque puede tener varios tipos o diferentes formatos/patrones</sub></sup>. 

- `id[string]`: Property. Unique identifier of the entity.

- `type[string]`: Property. NGSI Entity Type. It has to be CitrusPackhouseOperation.

- `nomIndustriaHash[string]`: Property. Model:'https://schema.org/Text'. Hashed identifier of the agri-food industry (packhouse). . Model: [https://schema.org/Text](https://schema.org/Text)

- `nCampana[number]`: Property. Model:'https://schema.org/Number'. Campaign number. . Model: [https://schema.org/Number](https://schema.org/Number)

- `campana[string]`: Property. Model:'https://schema.org/Text'. Campaign period (season). . Model: [https://schema.org/Text](https://schema.org/Text)

- `proveedorHash[string]`: Property. Model:'https://schema.org/Text'. Hashed identifier of the product supplier. . Model: [https://schema.org/Text](https://schema.org/Text)

- `fecha[string]`: Property. Model:'https://schema.org/DateTime'. Product delivery date. . Model: [https://schema.org/DateTime](https://schema.org/DateTime)

- `nPartida[number]`: Property. Model:'https://schema.org/Number'. Batch (lot) number within the crop and campaign. . Model: [https://schema.org/Number](https://schema.org/Number)

- `codCultivo[number]`: Property. Model:'https://schema.org/Number'. Crop type code. . Model: [https://schema.org/Number](https://schema.org/Number)

- `nomVariedad[string]`: Property. Model:'https://schema.org/Text'. Variety name. . Model: [https://schema.org/Text](https://schema.org/Text)

- `typeVariedad[number]`: Property. Model:'https://schema.org/Number'. Variety type. . Model: [https://schema.org/Number](https://schema.org/Number)

- `nomCultivoHash[string]`: Property. Model:'https://schema.org/Text'. Hashed identifier of the crop and estate. . Model: [https://schema.org/Text](https://schema.org/Text)

- `fincaHash[string]`: Property. Model:'https://schema.org/Text'. Hashed identifier of the estate (finca). . Model: [https://schema.org/Text](https://schema.org/Text)

- `usoSig[string]`: Property. Model:'https://schema.org/Text'. Agronomic land use of the plot according to SIGPAC. . Model: [https://schema.org/Text](https://schema.org/Text)

- `supData[number]`: Property. Model:'https://schema.org/Number'. Units: 'ha'. Parcel area according to supplied data. . Model: [https://schema.org/Number](https://schema.org/Number)

- `supSig[number]`: Property. Model:'https://schema.org/Number'. Units: 'ha'. Parcel area according to SIGPAC. . Model: [https://schema.org/Number](https://schema.org/Number)

- `sigParcelasHash[string]`: Property. Model:'https://schema.org/Text'. Hashed cadastral references of the parcels (SIGPAC). . Model: [https://schema.org/Text](https://schema.org/Text)

- `perimParc[number]`: Property. Model:'https://schema.org/Number'. Units: 'm'. Parcels perimeter according to SIGPAC. . Model: [https://schema.org/Number](https://schema.org/Number)

- `pesoCamion[number]`: Property. Model:'https://schema.org/Number'. Units: 'kg'. Truck weight. . Model: [https://schema.org/Number](https://schema.org/Number)

- `pesoTotal[number]`: Property. Model:'https://schema.org/Number'. Units: 't'. Total weight. . Model: [https://schema.org/Number](https://schema.org/Number)

- `rendData[number]`: Property. Model:'https://schema.org/Number'. Units: 't/ha'. Yield according to supplied data. . Model: [https://schema.org/Number](https://schema.org/Number)

- `rendSig[number]`: Property. Model:'https://schema.org/Number'. Units: 't/ha'. Yield calculated with SIGPAC data. . Model: [https://schema.org/Number](https://schema.org/Number)

- `prodData[number]`: Property. Model:'https://schema.org/Number'. Units: 't'. Production according to supplied data. . Model: [https://schema.org/Number](https://schema.org/Number)

- `prodSig[number]`: Property. Model:'https://schema.org/Number'. Units: 't'. Production calculated with SIGPAC data. . Model: [https://schema.org/Number](https://schema.org/Number)

- `nomCalidad[string]`: Property. Model:'https://schema.org/Text'. Quality category name. . Model: [https://schema.org/Text](https://schema.org/Text)

- `nCalidad[number]`: Property. Model:'https://schema.org/Number'. Quality category number. . Model: [https://schema.org/Number](https://schema.org/Number)

- `nomCalibre[string]`: Property. Model:'https://schema.org/Text'. Caliber (size) category name. . Model: [https://schema.org/Text](https://schema.org/Text)

- `nCalibre[number]`: Property. Model:'https://schema.org/Number'. Caliber category number. . Model: [https://schema.org/Number](https://schema.org/Number)

- `peso[number]`: Property. Model:'https://schema.org/Number'. Units: 'kg'. Weight associated with each quality category. . Model: [https://schema.org/Number](https://schema.org/Number)

- `giqc[number]`: Property. Model:'https://schema.org/Number'. GIQC index (global internal quality coefficient). . Model: [https://schema.org/Number](https://schema.org/Number)

- `porcentaje[number]`: Property. Model:'https://schema.org/Number'. Units: '%'. Percentage that this category represents of the batch total. . Model: [https://schema.org/Number](https://schema.org/Number)

- `iqc[number]`: Property. Model:'https://schema.org/Number'. IQC index (internal quality coefficient). . Model: [https://schema.org/Number](https://schema.org/Number)

- `filter[string]`: Property. Model:'https://schema.org/Text'. Technical filtering field. . Model: [https://schema.org/Text](https://schema.org/Text)

- `fechaPlan[string]`: Property. Model:'https://schema.org/Text'. Year associated with the plantation. . Model: [https://schema.org/Text](https://schema.org/Text)

- `coefRegad[number]`: Property. Model:'https://schema.org/Number'. Units: '%'. Irrigation coefficient. . Model: [https://schema.org/Number](https://schema.org/Number)

- `nFila[number]`: Property. Model:'https://schema.org/Number'. Row number. . Model: [https://schema.org/Number](https://schema.org/Number)

- `oriDom[string]`: Property. Model:'https://schema.org/Text'. Dominant orientation of the parcel. . Model: [https://schema.org/Text](https://schema.org/Text)

- `oriE[number]`: Property. Model:'https://schema.org/Number'. Units: '%'. Percentage of surface with East orientation. . Model: [https://schema.org/Number](https://schema.org/Number)

- `oriN[number]`: Property. Model:'https://schema.org/Number'. Units: '%'. Percentage of surface with North orientation. . Model: [https://schema.org/Number](https://schema.org/Number)

- `oriS[number]`: Property. Model:'https://schema.org/Number'. Units: '%'. Percentage of surface with South orientation. . Model: [https://schema.org/Number](https://schema.org/Number)

- `oriW[number]`: Property. Model:'https://schema.org/Number'. Units: '%'. Percentage of surface with West orientation. . Model: [https://schema.org/Number](https://schema.org/Number)

- `pdteMedia[number]`: Property. Model:'https://schema.org/Number'. Units: '%'. Mean slope of the parcel. . Model: [https://schema.org/Number](https://schema.org/Number)

- `pdte05[number]`: Property. Model:'https://schema.org/Number'. Units: '%'. Percentage of surface with slope 0-5%. . Model: [https://schema.org/Number](https://schema.org/Number)

- `pdte510[number]`: Property. Model:'https://schema.org/Number'. Units: '%'. Percentage of surface with slope 5-10%. . Model: [https://schema.org/Number](https://schema.org/Number)

- `pdte1030[number]`: Property. Model:'https://schema.org/Number'. Units: '%'. Percentage of surface with slope 10-30%. . Model: [https://schema.org/Number](https://schema.org/Number)

- `pdte30Max[number]`: Property. Model:'https://schema.org/Number'. Units: '%'. Percentage of surface with slope greater than 30%. . Model: [https://schema.org/Number](https://schema.org/Number)

- `dataOwner[string]`: Property. Model:'https://schema.org/Text'. Owner of the data. . Model: [https://schema.org/Text](https://schema.org/Text)

- `dataProvider[string]`: Property. Model:'https://schema.org/Text'. Provider of the data. . Model: [https://schema.org/Text](https://schema.org/Text)

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
CitrusPackhouseOperation:   
  $schema: "http://json-schema.org/draft-07/schema#"   
  $id: "https://github.com/CitriData/dataModel.Agrifood/blob/main/CitrusPackhouseOperation/schema.json"   
  title: CitrusPackhouseOperation   
  description: Data model designed for operational management and traceability in the citrus transformation and packing industry. It records raw-material batch intake, quality parameters (calibers, ripeness, etc.), control of processing/packing operations, and finished-product inventory ready for distribution. It combines industry-supplied data on suppliers' parcels with parcel attributes extracted from SIGPAC. Sensitive identifiers are anonymized by hashing.   
  type: object   
  required:   
 - id   
 - type   
  properties:   
 id:   
   type: string   
   description: Property. Unique identifier of the entity.   
 type:   
   type: string   
   description: Property. NGSI Entity Type. It has to be CitrusPackhouseOperation.   
   enum:   
  - CitrusPackhouseOperation   
 nomIndustriaHash:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Hashed identifier of the agri-food industry (packhouse)."   
 nCampana:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Campaign number."   
 campana:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Campaign period (season)."   
 proveedorHash:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Hashed identifier of the product supplier."   
 fecha:   
   type: string   
   format: date-time   
   description: "Property. Model:'https://schema.org/DateTime'. Product delivery date."   
 nPartida:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Batch (lot) number within the crop and campaign."   
 codCultivo:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Crop type code."   
 nomVariedad:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Variety name."   
 typeVariedad:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Variety type."   
 nomCultivoHash:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Hashed identifier of the crop and estate."   
 fincaHash:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Hashed identifier of the estate (finca)."   
 usoSig:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Agronomic land use of the plot according to SIGPAC."   
 supData:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: 'ha'. Parcel area according to supplied data."   
 supSig:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: 'ha'. Parcel area according to SIGPAC."   
 sigParcelasHash:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Hashed cadastral references of the parcels (SIGPAC)."   
 perimParc:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: 'm'. Parcels perimeter according to SIGPAC."   
 pesoCamion:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: 'kg'. Truck weight."   
 pesoTotal:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: 't'. Total weight."   
 rendData:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: 't/ha'. Yield according to supplied data."   
 rendSig:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: 't/ha'. Yield calculated with SIGPAC data."   
 prodData:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: 't'. Production according to supplied data."   
 prodSig:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: 't'. Production calculated with SIGPAC data."   
 nomCalidad:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Quality category name."   
 nCalidad:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Quality category number."   
 nomCalibre:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Caliber (size) category name."   
 nCalibre:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Caliber category number."   
 peso:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: 'kg'. Weight associated with each quality category."   
 giqc:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. GIQC index (global internal quality coefficient)."   
 porcentaje:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: '%'. Percentage that this category represents of the batch total."   
 iqc:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. IQC index (internal quality coefficient)."   
 filter:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Technical filtering field."   
 fechaPlan:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Year associated with the plantation."   
 coefRegad:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: '%'. Irrigation coefficient."   
 nFila:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Row number."   
 oriDom:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Dominant orientation of the parcel."   
 oriE:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: '%'. Percentage of surface with East orientation."   
 oriN:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: '%'. Percentage of surface with North orientation."   
 oriS:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: '%'. Percentage of surface with South orientation."   
 oriW:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: '%'. Percentage of surface with West orientation."   
 pdteMedia:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: '%'. Mean slope of the parcel."   
 pdte05:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: '%'. Percentage of surface with slope 0-5%."   
 pdte510:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: '%'. Percentage of surface with slope 5-10%."   
 pdte1030:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: '%'. Percentage of surface with slope 10-30%."   
 pdte30Max:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Units: '%'. Percentage of surface with slope greater than 30%."   
 dataOwner:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Owner of the data."   
 dataProvider:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Provider of the data."   


``` 
</details>   
<!-- /60-ModelYaml -->
 
<!-- 70-MiddleNotes -->
 
<!-- /70-MiddleNotes -->
 
<!-- 80-Examples -->
 

## Ejemplo de carga útil 

#### CitrusPackhouseOperation NGSI-v2 key-values Ejemplo 

Aquí hay un ejemplo básico en formato key-values. 
<details><summary><strong>show/hide example</strong></summary>   

```json  
{
  "entity_id": "0001",
  "type": "CitrusPackhouseOperation",
  "nomIndustriaHash": "9b52a09d37cfab8568f163d4816ddea8",
  "nCampana": 1,
  "campana": "2016/2017",
  "proveedorHash": "9bfef8cc26ee26aa7ceaafe3391b9d18",
  "fecha": "2016-11-02T23:00:00.000Z",
  "nPartida": 99,
  "codCultivo": 246,
  "nomVariedad": "NAVELINA",
  "typeVariedad": 2,
  "nomCultivoHash": "373ce2761e3e171c1d3c63c5f392a3ec",
  "fincaHash": "bc219c12e98c4e99e6758ae118726f2d",
  "usoSig": "CI",
  "supData": 10.199999809265137,
  "supSig": 29.393959045410156,
  "sigParcelasHash": "dabfde383102117d6b045cbf69411be3",
  "perimParc": 2729.814208984375,
  "pesoCamion": 21200,
  "pesoTotal": 21.200000762939453,
  "rendData": 25.860000610351562,
  "rendSig": 46.2599983215332,
  "prodData": 760.02001953125,
  "prodSig": 1359.489990234375,
  "nomCalidad": "PODRIDO",
  "nCalidad": -3,
  "nomCalibre": "Calibre 5",
  "nCalibre": 5,
  "peso": 61,
  "giqc": 3.4375,
  "porcentaje": 0.28773584961891174,
  "iqc": -0.8700000047683716,
  "filter": "0",
  "fechaPlan": "1999",
  "coefRegad": 100,
  "nFila": 775,
  "oriDom": "NORTE",
  "oriE": 31.568822860717773,
  "oriN": 56.25941848754883,
  "oriS": 6.376452922821045,
  "oriW": 5.795307636260986,
  "pdte05": 31.439680099487305,
  "pdte1030": 4.085503578186035,
  "pdte30Max": 0.05919070169329643,
  "pdte510": 64.4156265258789,
  "pdteMedia": 6.952395915985107,
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

[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)
<!-- /97-LastFooter -->