---
title: "Aspose.BarCode.ComplexBarcode"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "El Aspose.BarCode.ComplexBarcode contiene clases generales para la implementación de funciones de generación de códigos de barras complejos"
type: docs
weight: 40
url: /es/net/aspose.barcode.complexbarcode/
---
El **Aspose.BarCode.ComplexBarcode** contiene clases generales para la implementación de funciones complejas de generación de códigos de barras.

## Clases

| Clase | Descripción |
| --- | --- |
| [Address](./address/) | Dirección del acreedor o deudor. |
| [AlternativeScheme](./alternativescheme/) | Instrucciones del esquema de pago alternativo |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/) | ComplexBarcodeGenerator para la generación de imágenes de códigos de barras complejos en el backend (p. ej., SwissQR). |
| [ComplexCodetextReader](./complexcodetextreader/) | ComplexCodetextReader decodifica codetext al tipo de código de barras complejo especificado. |
| [GS1Codetext](./gs1codetext/) | Representa el codetext GS1 para codificar y decodificar como una secuencia ordenada de elementos Identificador de Aplicación. Se preservan el orden de origen y los Identificadores de Aplicación repetidos. La representación entre corchetes tiene la forma (AI)valor(AI)valor. Un paréntesis de apertura literal '(' dentro de un valor debe escribirse como \\(; esta es la única secuencia de escape admitida. Un paréntesis de cierre ')' dentro de un valor no requiere escape. |
| [GS1DigitalLink](./gs1digitallink/) | Representa el codetext GS1 Digital Link para codificar y decodificar como una secuencia ordenada de elementos Identificador de Aplicación. Se preservan el orden de origen y los Identificadores de Aplicación repetidos. El codetext construido es un URI GS1 Digital Link sin comprimir. Los parámetros de consulta y fragmentos de URI que no son GS1 se ignoran al analizar. |
| [HIBCLICCombinedCodetext](./hibcliccombinedcodetext/) | Clase para codificar y decodificar el texto incrustado en el código HIBC LIC que almacena datos primarios y secundarios. |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/) | Clase base para codificar y decodificar el texto incrustado en el código HIBC LIC. |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/) | Clase para codificar y decodificar el texto incrustado en el código HIBC LIC que almacena datos primarios. |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/) | Clase para codificar y decodificar el texto incrustado en el código HIBC LIC que almacena datos secundarios. |
| [HIBCPASCodetext](./hibcpascodetext/) | Clase para codificar y decodificar el texto incrustado en el código HIBC PAS. |
| [HIBCPASRecord](./hibcpasrecord/) | Clase para almacenar el registro HIBC PAS. |
| [Mailmark2DCodetext](./mailmark2dcodetext/) | Clase para codificar y decodificar el texto incrustado en el código Royal Mail 2D Mailmark. |
| [MailmarkCodetext](./mailmarkcodetext/) | Clase para codificar y decodificar el texto incrustado en el código Royal Mailmark de 4 estados. |
| [MaxiCodeCodetext](./maxicodecodetext/) | Clase base para codificar y decodificar el texto incrustado en el código MaxiCode. |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/) | Clase para codificar y decodificar el texto incrustado en el código MaxiCode para los modos 2. |
| [MaxiCodeCodetextMode3](./maxicodecodetextmode3/) | Clase para codificar y decodificar el texto incrustado en el código MaxiCode para los modos 3. |
| [MaxiCodeSecondMessage](./maxicodesecondmessage/) | Clase base para codificar y decodificar el segundo mensaje para el código de barras MaxiCode. |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/) | Clase para codificar y decodificar el texto de código MaxiCode para los modos 4, 5 y 6. |
| [MaxiCodeStandardSecondMessage](./maxicodestandardsecondmessage/) | Clase para codificar y decodificar el mensaje secundario estándar para el código de barras MaxiCode. |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/) | Clase base para codificar y decodificar el texto incrustado en el código MaxiCode para los modos 2 y 3. |
| [MaxiCodeStructuredSecondMessage](./maxicodestructuredsecondmessage/) | Clase para codificar y decodificar el segundo mensaje estructurado para el código de barras MaxiCode. |
| [PrimaryData](./primarydata/) | Clase para almacenar los datos primarios HIBC LIC. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/) | Clase para almacenar los datos secundarios y adicionales HIBC LIC. |
| [SwissQRBill](./swissqrbill/) | Datos de factura SwissQR |
| [SwissQRCodetext](./swissqrcodetext/) | Clase para codificar y decodificar el texto incrustado en el código SwissQR. |
| [USADriveIdCodetext](./usadriveidcodetext/) | Clase para codificar y decodificar el texto incrustado en el código PDF417 de la licencia de conducir de EE. UU. |
| [USADriveIdJurisdSubfile](./usadriveidjurisdsubfile/) | Clase para campos específicos de jurisdicción para la licencia de EE. UU. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IComplexCodetext](./icomplexcodetext/) | Interfaz para texto de código complejo usado con ComplexBarcodeGenerator. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [AddressType](./addresstype/) | Tipo de dirección |
| [HIBCLICDateFormat](./hibclicdateformat/) | Especifica los diferentes tipos de formatos de fecha para HIBC LIC. |
| [HIBCPASDataLocation](./hibcpasdatalocation/) | Tipos de ubicación de datos HIBC PAS. |
| [HIBCPASDataType](./hibcpasdatatype/) | Tipos de datos del registro HIBC PAS. |
| [Mailmark2DType](./mailmark2dtype/) | El tipo 2D Mailmark define el tamaño del código de barras Data Matrix. |
| [USADriveIdCountry](./usadriveidcountry/) | Enumeración para la identificación del país en la licencia de conducir de EE. UU. |
| [USADriveIdEyeColor](./usadriveideyecolor/) | Enumeración para el color de ojos en la licencia de conducir de EE. UU. |
| [USADriveIdHairColor](./usadriveidhaircolor/) | Enumeración para el color de cabello en la licencia de conducir de EE. UU. |
| [USADriveIdSex](./usadriveidsex/) | Enumeración para el campo de sexo en la licencia de conducir de EE. UU. |


