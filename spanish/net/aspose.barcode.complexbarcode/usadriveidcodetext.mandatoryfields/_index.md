---
title: "Clase USADriveIdCodetext.MandatoryFields"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.ComplexBarcode.USADriveIdCodetextMandatoryFields. Campos obligatorios de la tarjeta"
type: docs
weight: 820
url: /es/net/aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
## USADriveIdCodetext.MandatoryFields class

Elementos obligatorios (campos) de la tarjeta

```csharp
public class MandatoryFields
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/.ctor)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AddressCity](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresscity) { get; set; } | DAI, Porción de ciudad de la dirección del titular de la tarjeta, DL/ID, V20ANS |
| [AddressPostalCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresspostalcode) { get; set; } | DAK, Porción del código postal de la dirección del titular de la tarjeta en EE. UU. y Canadá. Si la porción final del código postal en EE. UU. no se conoce, se usarán ceros para completar el conjunto final de números hasta 9 dígitos, DL/ID, F11ANS |
| [AddressState](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstate) { get; set; } | DAJ, Porción del estado de la dirección del titular de la tarjeta, DL/ID, F2A |
| [AddressStreet1](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstreet1) { get; set; } | DAG, Porción de la calle de la dirección del titular de la tarjeta, DL/ID, V35ANS |
| [CountryIdentification](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/countryidentification) { get; set; } | DCG, País en el que se emite DL/ID. EE. UU. = USA, Canadá = CAN, DL/ID, F3A |
| [CustomerIDNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/customeridnumber) { get; set; } | DAQ, El número asignado o calculado por la autoridad emisora, DL/ID, V25ANS |
| [DateOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/dateofbirth) { get; set; } | DBB, Fecha en que se emitió el documento, MMDDCCYY para EE. UU., CCYYMMDD para Canadá, DL/ID, F8N |
| [DocumentDiscriminator](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/documentdiscriminator) { get; set; } | DCF, El número debe identificar de forma única un documento específico emitido a ese cliente respecto a otros que puedan haberse emitido en el pasado. Este número puede servir para múltiples propósitos de discriminación de documentos, número de información de auditoría y/o control de inventario, DL/ID, V25ANS |
| [EndorsementCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/endorsementcodes) { get; set; } | DCD, Códigos de endoso específicos de la jurisdicción, DL, V5ANS |
| [ExpirationDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/expirationdate) { get; set; } | DBA, Fecha de vencimiento del documento, MMDDCCYY para EE. UU., CCYYMMDD para Canadá, DL/ID, F8N |
| [EyeColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/eyecolor) { get; set; } | DAY, Color de los ojos del titular de la tarjeta. (códigos ANSI D-20). DL/ID, F3A |
| [FamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familyname) { get; set; } | DCS, Apellido del titular de la tarjeta, DL/ID, V40ANS |
| [FamilyNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familynametruncation) { get; set; } | DDE, Un código que indica si un campo ha sido truncado (T), no ha sido truncado (N), o se desconoce si está truncado (U), DL/ID, F1A |
| [FirstName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstname) { get; set; } | DAC, Nombre del titular de la tarjeta, DL/ID, V40ANS |
| [FirstNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstnametruncation) { get; set; } | DDF, Un código que indica si un campo ha sido truncado (T), no ha sido truncado (N), o se desconoce si está truncado (U), DL/ID, F1A |
| [Height](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/height) { get; set; } | DAU, Altura del titular de la tarjeta. Pulgadas (in): número de pulgadas seguido de " in" ej. 6'1'' = "073 in" Centímetros (cm): número de centímetros seguido de " cm" ej. 181 centímetros = "181 cm", DL/ID, F6ANS |
| [IssueDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/issuedate) { get; set; } | DBD, Fecha en que se emitió el documento, MMDDCCYY para EE. UU., CCYYMMDD para Canadá, DL/ID, F8N |
| [MiddleName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlename) { get; set; } | DAD, Segundo(s) nombre(s) del titular de la tarjeta. En caso de varios segundos nombres, deberán separarse con una coma ",". , DL/ID, V40ANS |
| [MiddleNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlenametruncation) { get; set; } | DDG, Un código que indica si un campo ha sido truncado (T), no ha sido truncado (N), o se desconoce si está truncado (U), DL/ID, F1A |
| [RestrictionCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/restrictioncodes) { get; set; } | DCB, Códigos de restricciones específicos de la jurisdicción, DL, V12ANS |
| [Sex](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/sex) { get; set; } | DBC, Género del titular de la tarjeta. 1 = masculino, 2 = femenino, 9 = no especificado, DL/ID, F1N |
| [VehicleClass](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/vehicleclass) { get; set; } | DCA, Código de clase / grupo de vehículo específico de la jurisdicción, DL, V6ANS |

### Ver también

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


