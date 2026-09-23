<!-- 10-Header --> 
Entidad: VineyardMildewEvolution
=================
<!-- /10-Header -->
 
<!-- 15-License -->


<!-- /15-License -->
 
<!-- 20-Description -->
 

Descripción global: **Data model for the predictive monitoring of grapevine downy mildew (Plasmopara viticola) in the Montilla-Moriles wine-growing area (Córdoba, Spain) during the 2026 season. Each record holds the daily state of an epidemiological model linked to a SIAR agro-meteorological station: oospore maturation and germination, crop susceptibility, primary infection, Goidanich incubation, appearance of the first oil spot and secondary infections, together with the daily weather variables that drive them. It is intended to support decision-making on vineyard disease management.**. 

versión: 0.0.1 
<!-- /20-Description -->
 
<!-- 30-PropertiesList -->
 

## Lista de propiedades 

<sup><sub>[*] Si no hay un tipo en un atributo es porque puede tener varios tipos o diferentes formatos/patrones</sub></sup>. 

- `id[string]`: Unique identifier of the entity.

- `type[string]`: Property. NGSI Entity Type. It has to be VineyardMildewEvolution.

- `fechaExploracion[string]`: Property. Model:'https://schema.org/Text'. Fecha y hora de la ejecución del modelo a la que corresponde el estado diario registrado . Model: [https://schema.org/Text](https://schema.org/Text)

- `status[string]`: Property. Model:'https://schema.org/Text'. Estado fenológico del ciclo del mildiu en la fecha de exploración, expresado como texto descriptivo de la fase o regla del modelo alcanzada (p. ej. 'No se ha llegado a maduración (1ª regla)') . Model: [https://schema.org/Text](https://schema.org/Text)

- `porcentajeModelo[number]`: Property. Model:'https://schema.org/Number'. Porcentaje de avance global del modelo de mildiu en la campaña, desde el inicio hasta la aparición de la primera mancha . Model: [https://schema.org/Number](https://schema.org/Number)

- `porcentajeAcumuladoMaduracion[number]`: Property. Model:'https://schema.org/Number'. Porcentaje acumulado de maduración de las oosporas invernantes; al alcanzar el 100 % se considera que las oosporas están maduras y pueden germinar . Model: [https://schema.org/Number](https://schema.org/Number)

- `fechaMaduracion[string]`: Property. Model:'https://schema.org/Text'. Fecha en la que se alcanza la maduración de las oosporas (100 % de maduración acumulada). Nulo si aún no se ha alcanzado . Model: [https://schema.org/Text](https://schema.org/Text)

- `puedeGerminar[boolean]`: Property. Model:'https://schema.org/Boolean'. Indica si se cumplen las condiciones para la germinación de las oosporas maduras (oosporas maduras y lluvia suficiente) . Model: [https://schema.org/Boolean](https://schema.org/Boolean)

- `lluviaAcumulada48h[number]`: Property. Model:'https://schema.org/Number'. Precipitación acumulada durante las últimas 48 horas, utilizada para evaluar la condición de germinación de las oosporas . Model: [https://schema.org/Number](https://schema.org/Number)

- `fechaPrimeraGerminacion[string]`: Property. Model:'https://schema.org/Text'. Fecha en la que se detecta la primera germinación de oosporas en la campaña. Nulo si aún no se ha producido . Model: [https://schema.org/Text](https://schema.org/Text)

- `esSusceptible[boolean]`: Property. Model:'https://schema.org/Boolean'. Indica si el viñedo se encuentra en estado fenológico susceptible a la infección por mildiu . Model: [https://schema.org/Boolean](https://schema.org/Boolean)

- `fechaSusceptibilidad[string]`: Property. Model:'https://schema.org/Text'. Fecha a partir de la cual el viñedo se considera susceptible a la infección. Nulo si aún no se ha alcanzado . Model: [https://schema.org/Text](https://schema.org/Text)

- `puedeInfectar[boolean]`: Property. Model:'https://schema.org/Boolean'. Indica si se dan simultáneamente las condiciones necesarias para una infección primaria (germinación, susceptibilidad del cultivo y condiciones meteorológicas favorables) . Model: [https://schema.org/Boolean](https://schema.org/Boolean)

- `mojadoFoliar[boolean]`: Property. Model:'https://schema.org/Boolean'. Indica si se ha registrado humectación foliar suficiente para permitir la infección . Model: [https://schema.org/Boolean](https://schema.org/Boolean)

- `suma25t[number]`: Property. Model:'https://schema.org/Number'. Suma térmica acumulada durante el periodo de humectación, comparada con el umbral de 25 para evaluar la condición de infección . Model: [https://schema.org/Number](https://schema.org/Number)

- `suma50t[number]`: Property. Model:'https://schema.org/Number'. Suma térmica acumulada durante el periodo de humectación, comparada con el umbral de 50 para evaluar la condición de infección . Model: [https://schema.org/Number](https://schema.org/Number)

- `fechaInfeccion[string]`: Property. Model:'https://schema.org/Text'. Fecha en la que se produce la infección primaria. Nulo si aún no se ha producido . Model: [https://schema.org/Text](https://schema.org/Text)

- `puedeAparecer[boolean]`: Property. Model:'https://schema.org/Boolean'. Indica si, tras una infección, el periodo de incubación está suficientemente avanzado como para que puedan aparecer las primeras manchas de aceite . Model: [https://schema.org/Boolean](https://schema.org/Boolean)

- `porcentajeAcumuladoGoidanich[number]`: Property. Model:'https://schema.org/Number'. Porcentaje acumulado del periodo de incubación calculado según el modelo de Goidanich a partir de la temperatura y humedad diarias; el 100 % marca el final de la incubación . Model: [https://schema.org/Number](https://schema.org/Number)

- `fechaIncubacion70[string]`: Property. Model:'https://schema.org/Text'. Fecha en la que la incubación acumulada (Goidanich) alcanza el 70 %. Nulo si aún no se ha alcanzado . Model: [https://schema.org/Text](https://schema.org/Text)

- `fechaIncubacion100[string]`: Property. Model:'https://schema.org/Text'. Fecha en la que la incubación acumulada (Goidanich) alcanza el 100 %. Nulo si aún no se ha alcanzado . Model: [https://schema.org/Text](https://schema.org/Text)

- `puedeIncubacion[boolean]`: Property. Model:'https://schema.org/Boolean'. Indica si existe una infección en curso cuyo periodo de incubación está progresando . Model: [https://schema.org/Boolean](https://schema.org/Boolean)

- `porcentajeAcumuladoMancha[number]`: Property. Model:'https://schema.org/Number'. Porcentaje acumulado hacia la aparición de la primera mancha de aceite visible en hoja . Model: [https://schema.org/Number](https://schema.org/Number)

- `fechaMancha[string]`: Property. Model:'https://schema.org/Text'. Fecha estimada de aparición de la primera mancha de aceite. Nulo si aún no se ha alcanzado . Model: [https://schema.org/Text](https://schema.org/Text)

- `probabilidadPrimeraManchaHoy[number]`: Property. Model:'https://schema.org/Number'. Probabilidad estimada de que la primera mancha de aceite aparezca en el día de la exploración . Model: [https://schema.org/Number](https://schema.org/Number)

- `esporulacionNocturnaHoy[boolean]`: Property. Model:'https://schema.org/Boolean'. Indica si en la noche del día de exploración se han dado condiciones favorables para la esporulación (formación de esporangios sobre las manchas) . Model: [https://schema.org/Boolean](https://schema.org/Boolean)

- `sporasInviablesPorCalorHoy[boolean]`: Property. Model:'https://schema.org/Boolean'. Indica si las temperaturas elevadas del día han hecho inviables las esporas formadas, impidiendo infecciones secundarias . Model: [https://schema.org/Boolean](https://schema.org/Boolean)

- `infeccionSecundariaHoy[boolean]`: Property. Model:'https://schema.org/Boolean'. Indica si en el día de exploración se ha producido una infección secundaria a partir de esporangios de manchas existentes . Model: [https://schema.org/Boolean](https://schema.org/Boolean)

- `fechaPrimeraInfeccionSecundaria[string]`: Property. Model:'https://schema.org/Text'. Fecha de la primera infección secundaria de la campaña. Nulo si aún no se ha producido . Model: [https://schema.org/Text](https://schema.org/Text)

- `fechasFallidasSegundaInfeccion[array]`: Property. Model:'https://schema.org/Text'. Lista de fechas en las que se iniciaron condiciones de infección secundaria que finalmente no llegaron a completarse . Model: [https://schema.org/Text](https://schema.org/Text)

- `tempMediaDia[number]`: Property. Model:'https://schema.org/Number'. Temperatura media del aire del día, obtenida de la estación meteorológica asociada . Model: [https://schema.org/Number](https://schema.org/Number)

- `tempMaxDia[number]`: Property. Model:'https://schema.org/Number'. Temperatura máxima del aire del día, obtenida de la estación meteorológica asociada . Model: [https://schema.org/Number](https://schema.org/Number)

- `tempMinDia[number]`: Property. Model:'https://schema.org/Number'. Temperatura mínima del aire del día, obtenida de la estación meteorológica asociada . Model: [https://schema.org/Number](https://schema.org/Number)

- `humedadMediaDia[number]`: Property. Model:'https://schema.org/Number'. Humedad relativa media del aire del día, obtenida de la estación meteorológica asociada . Model: [https://schema.org/Number](https://schema.org/Number)

- `precipitacionDia[number]`: Property. Model:'https://schema.org/Number'. Precipitación total registrada en el día, obtenida de la estación meteorológica asociada . Model: [https://schema.org/Number](https://schema.org/Number)

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
Seguimiento Mildiu Montilla/Moriles Año 2026:   
  $schema: "http://json-schema.org/draft-07/schema#"   
  $id: "https://github.com/CitriData/dataModel.Agrifood/blob/main/VineyardMildewEvolution/schema.json"   
  title: Seguimiento Mildiu Montilla/Moriles Año 2026   
  description: Data model for the predictive monitoring of grapevine downy mildew (Plasmopara viticola) in the Montilla-Moriles wine-growing area (Córdoba, Spain) during the 2026 season. Each record holds the daily state of an epidemiological model linked to a SIAR agro-meteorological station: oospore maturation and germination, crop susceptibility, primary infection, Goidanich incubation, appearance of the first oil spot and secondary infections, together with the daily weather variables that drive them. It is intended to support decision-making on vineyard disease management.   
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
   description: Property. NGSI Entity Type. It has to be VineyardMildewEvolution.   
   enum:   
  - VineyardMildewEvolution   
 fechaExploracion:   
   type: string   
   format: date-time   
   description: "Property. Model:'https://schema.org/Text'. Fecha y hora de la ejecución del modelo a la que corresponde el estado diario registrado"   
 status:   
   type: string   
   description: "Property. Model:'https://schema.org/Text'. Estado fenológico del ciclo del mildiu en la fecha de exploración, expresado como texto descriptivo de la fase o regla del modelo alcanzada (p. ej. 'No se ha llegado a maduración (1ª regla)')"   
 porcentajeModelo:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Porcentaje de avance global del modelo de mildiu en la campaña, desde el inicio hasta la aparición de la primera mancha"   
 porcentajeAcumuladoMaduracion:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Porcentaje acumulado de maduración de las oosporas invernantes; al alcanzar el 100 % se considera que las oosporas están maduras y pueden germinar"   
 fechaMaduracion:   
   type: string   
   format: date-time   
   description: "Property. Model:'https://schema.org/Text'. Fecha en la que se alcanza la maduración de las oosporas (100 % de maduración acumulada). Nulo si aún no se ha alcanzado"   
 puedeGerminar:   
   type: boolean   
   description: "Property. Model:'https://schema.org/Boolean'. Indica si se cumplen las condiciones para la germinación de las oosporas maduras (oosporas maduras y lluvia suficiente)"   
 lluviaAcumulada48h:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Precipitación acumulada durante las últimas 48 horas, utilizada para evaluar la condición de germinación de las oosporas"   
 fechaPrimeraGerminacion:   
   type: string   
   format: date-time   
   description: "Property. Model:'https://schema.org/Text'. Fecha en la que se detecta la primera germinación de oosporas en la campaña. Nulo si aún no se ha producido"   
 esSusceptible:   
   type: boolean   
   description: "Property. Model:'https://schema.org/Boolean'. Indica si el viñedo se encuentra en estado fenológico susceptible a la infección por mildiu"   
 fechaSusceptibilidad:   
   type: string   
   format: date-time   
   description: "Property. Model:'https://schema.org/Text'. Fecha a partir de la cual el viñedo se considera susceptible a la infección. Nulo si aún no se ha alcanzado"   
 puedeInfectar:   
   type: boolean   
   description: "Property. Model:'https://schema.org/Boolean'. Indica si se dan simultáneamente las condiciones necesarias para una infección primaria (germinación, susceptibilidad del cultivo y condiciones meteorológicas favorables)"   
 mojadoFoliar:   
   type: boolean   
   description: "Property. Model:'https://schema.org/Boolean'. Indica si se ha registrado humectación foliar suficiente para permitir la infección"   
 suma25t:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Suma térmica acumulada durante el periodo de humectación, comparada con el umbral de 25 para evaluar la condición de infección"   
 suma50t:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Suma térmica acumulada durante el periodo de humectación, comparada con el umbral de 50 para evaluar la condición de infección"   
 fechaInfeccion:   
   type: string   
   format: date-time   
   description: "Property. Model:'https://schema.org/Text'. Fecha en la que se produce la infección primaria. Nulo si aún no se ha producido"   
 puedeAparecer:   
   type: boolean   
   description: "Property. Model:'https://schema.org/Boolean'. Indica si, tras una infección, el periodo de incubación está suficientemente avanzado como para que puedan aparecer las primeras manchas de aceite"   
 porcentajeAcumuladoGoidanich:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Porcentaje acumulado del periodo de incubación calculado según el modelo de Goidanich a partir de la temperatura y humedad diarias; el 100 % marca el final de la incubación"   
 fechaIncubacion70:   
   type: string   
   format: date-time   
   description: "Property. Model:'https://schema.org/Text'. Fecha en la que la incubación acumulada (Goidanich) alcanza el 70 %. Nulo si aún no se ha alcanzado"   
 fechaIncubacion100:   
   type: string   
   format: date-time   
   description: "Property. Model:'https://schema.org/Text'. Fecha en la que la incubación acumulada (Goidanich) alcanza el 100 %. Nulo si aún no se ha alcanzado"   
 puedeIncubacion:   
   type: boolean   
   description: "Property. Model:'https://schema.org/Boolean'. Indica si existe una infección en curso cuyo periodo de incubación está progresando"   
 porcentajeAcumuladoMancha:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Porcentaje acumulado hacia la aparición de la primera mancha de aceite visible en hoja"   
 fechaMancha:   
   type: string   
   format: date-time   
   description: "Property. Model:'https://schema.org/Text'. Fecha estimada de aparición de la primera mancha de aceite. Nulo si aún no se ha alcanzado"   
 probabilidadPrimeraManchaHoy:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Probabilidad estimada de que la primera mancha de aceite aparezca en el día de la exploración"   
 esporulacionNocturnaHoy:   
   type: boolean   
   description: "Property. Model:'https://schema.org/Boolean'. Indica si en la noche del día de exploración se han dado condiciones favorables para la esporulación (formación de esporangios sobre las manchas)"   
 sporasInviablesPorCalorHoy:   
   type: boolean   
   description: "Property. Model:'https://schema.org/Boolean'. Indica si las temperaturas elevadas del día han hecho inviables las esporas formadas, impidiendo infecciones secundarias"   
 infeccionSecundariaHoy:   
   type: boolean   
   description: "Property. Model:'https://schema.org/Boolean'. Indica si en el día de exploración se ha producido una infección secundaria a partir de esporangios de manchas existentes"   
 fechaPrimeraInfeccionSecundaria:   
   type: string   
   format: date-time   
   description: "Property. Model:'https://schema.org/Text'. Fecha de la primera infección secundaria de la campaña. Nulo si aún no se ha producido"   
 fechasFallidasSegundaInfeccion:   
   type: array   
   description: "Property. Model:'https://schema.org/Text'. Lista de fechas en las que se iniciaron condiciones de infección secundaria que finalmente no llegaron a completarse"   
 tempMediaDia:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Temperatura media del aire del día, obtenida de la estación meteorológica asociada"   
 tempMaxDia:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Temperatura máxima del aire del día, obtenida de la estación meteorológica asociada"   
 tempMinDia:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Temperatura mínima del aire del día, obtenida de la estación meteorológica asociada"   
 humedadMediaDia:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Humedad relativa media del aire del día, obtenida de la estación meteorológica asociada"   
 precipitacionDia:   
   type: number   
   description: "Property. Model:'https://schema.org/Number'. Precipitación total registrada en el día, obtenida de la estación meteorológica asociada"   


``` 
</details>   
<!-- /60-ModelYaml -->
 
<!-- 70-MiddleNotes -->
 
<!-- /70-MiddleNotes -->
 
<!-- 80-Examples -->
 

## Ejemplo de carga útil 

#### Seguimiento Mildiu Montilla/Moriles Año 2026 NGSI-v2 key-values Ejemplo 

Aquí hay un ejemplo básico en formato key-values. 
<details><summary><strong>show/hide example</strong></summary>   

```json  
{
  "entity_id": "urn:ngsi-ld:citri.em.siar:siar-co01",
  "type": "VineyardMildewEvolution",
  "fechaExploracion": "2026-01-01T22:00:00Z",
  "status": "No se ha llegado a maduración (1ª regla)",
  "porcentajeModelo": 0.0,
  "porcentajeAcumuladoMaduracion": 0.0,
  "fechaMaduracion": null,
  "puedeGerminar": false,
  "lluviaAcumulada48h": 0.2,
  "fechaPrimeraGerminacion": null,
  "esSusceptible": false,
  "fechaSusceptibilidad": null,
  "puedeInfectar": false,
  "mojadoFoliar": false,
  "suma25t": 0.0,
  "suma50t": 0.0,
  "fechaInfeccion": null,
  "puedeAparecer": false,
  "porcentajeAcumuladoGoidanich": 0.0,
  "fechaIncubacion70": null,
  "fechaIncubacion100": null,
  "probabilidadPrimeraManchaHoy": 0.0,
  "esporulacionNocturnaHoy": false,
  "sporasInviablesPorCalorHoy": false,
  "infeccionSecundariaHoy": false,
  "fechaPrimeraInfeccionSecundaria": null,
  "fechasFallidasSegundaInfeccion": [],
  "tempMediaDia": 5.46,
  "tempMaxDia": 10.37,
  "tempMinDia": -0.67,
  "humedadMediaDia": 89.07,
  "precipitacionDia": 0.2,
  "porcentajeAcumuladoMancha": 0.0,
  "fechaMancha": null,
  "puedeIncubacion": false
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