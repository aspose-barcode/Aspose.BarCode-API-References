---
title: "Clase USADriveIdCodetext.OptionalFields"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.ComplexBarcode.USADriveIdCodetextOptionalFields. Campos de elementos opcionales de la tarjeta"
type: docs
weight: 830
url: /es/net/aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
## USADriveIdCodetext.OptionalFields class

Elementos opcionales (campos) de la tarjeta

```csharp
public class OptionalFields
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/.ctor)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AddressStreet2](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/addressstreet2) { get; set; } | DAH, Segunda línea de la parte de la calle de la dirección del titular de la tarjeta, DL/ID, V35ANS |
| [AliasAKAFamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakafamilyname) { get; set; } | DBN, Otro apellido por el que se conoce al titular de la tarjeta, DL/ID, V10ANS |
| [AliasAKAGivenName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakagivenname) { get; set; } | DBG, Otro nombre de pila por el que se conoce al titular de la tarjeta, DL/ID, V15ANS |
| [AliasAKASuffixName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakasuffixname) { get; set; } | DBS, Otro sufijo por el que se conoce al titular de la tarjeta, DL/ID, V5ANS |
| [AuditInformation](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/auditinformation) { get; set; } | DCJ, Una cadena de letras y/o números que identifica cuándo, dónde y por quién se fabricó una licencia de conducir/tarjeta de identificación. Si la información de auditoría no se usa en la tarjeta o en el MRT, debe incluirse en el registro del conductor, DL/ID, V25ANS |
| [CardRevisionDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/cardrevisiondate) { get; set; } | DDB, Campo requerido por DHS que indica la fecha del cambio de versión más reciente o la modificación del formato visible del DL/ID. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N |
| [ComplianceType](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/compliancetype) { get; set; } | DDA, Campo requerido por DHS que indica el cumplimiento: “F” = conforme; y, “N” = no conforme, DL/ID, F1A |
| [EndorsementCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/endorsementcodedescription) { get; set; } | DCQ, Texto que explica el/los código(s) específico(s) de la jurisdicción que indica(n) privilegios de conducción adicionales otorgados al titular más allá de la clase de vehículo, DL, V50ANS |
| [HairColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/haircolor) { get; set; } | DAZ, Calvo, negro, rubio, castaño, gris, rojo/castaño rojizo, arena, blanco, desconocido. Si la jurisdicción emisora desea abreviar los colores, se deben usar los códigos de tres caracteres proporcionados en AAMVA D20, DL/ID, V12A |
| [HAZMATEndorsementExpDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/hazmatendorsementexpdate) { get; set; } | DDC, Fecha en la que la autorización de material peligroso otorgada por el documento deja de ser válida. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL, F8N |
| [InventoryControlNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/inventorycontrolnumber) { get; set; } | DCK, Una cadena de letras y/o números que se adhiere a los materiales crudos (papel de tarjeta, laminado, etc.) utilizados en la producción de licencias de conducir y tarjetas de identificación. (Campo recomendado por DHS), DL/ID, V25ANS |
| [LimitedDurationDocIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/limiteddurationdocindicator) { get; set; } | DDD, Campo requerido por DHS que indica que el titular de la tarjeta tiene estatus legal temporal = “1”, DL/ID, F1N |
| [NameSuffix](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/namesuffix) { get; set; } | DCU, Sufijo del nombre (Si la jurisdicción participa en sistemas que requieren sufijo de nombre (PDPS, CDLIS, etc.), el sufijo debe recopilarse y mostrarse en el DL/ID y en el MRT). JR (Junior), SR (Senior), 1ST o I (Primero), hasta 9TH o IX (Noveno), DL/ID, V5ANS |
| [OrganDonorIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/organdonorindicator) { get; set; } | DDK, Campo que indica que el titular de la tarjeta es donante de órganos = “1”, DL/ID, F1N |
| [PlaceOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/placeofbirth) { get; set; } | DCI, País y municipio y/o estado/provincia, DL/ID, V33A |
| [RaceEthnicity](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/raceethnicity) { get; set; } | DCL, Códigos de raza o etnia del titular, según lo definido en AAMVA D20, DL/ID, V3A |
| [RestrictionCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/restrictioncodedescription) { get; set; } | DCR, Texto que describe el/los código(s) de restricción específico(s) de la jurisdicción que limitan los privilegios de conducción, DL, V50ANS |
| [StandardEndorsementCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardendorsementcode) { get; set; } | DCN, Código(s) de autorización estándar para el titular. Ver códigos en D20. Este elemento de datos es un marcador de posición para futuros esfuerzos de estandarización de códigos de autorización, DL, F5AN |
| [StandardRestrictionCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardrestrictioncode) { get; set; } | DCO, Código(s) de restricción estándar para el titular de la tarjeta. Ver códigos en D20. Este elemento de datos es un marcador de posición para futuros esfuerzos de estandarizar códigos de restricción, DL, F12AN |
| [StandardVehClassification](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardvehclassification) { get; set; } | DCM, Código(s) de clasificación de vehículo estándar para el titular de la tarjeta. Este elemento de datos es un marcador de posición para futuros esfuerzos de estandarizar clasificaciones de vehículos, DL, F4AN |
| [Under18Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under18until) { get; set; } | DDH, Fecha en la que el titular de la tarjeta cumple 18 años. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N |
| [Under19Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under19until) { get; set; } | DDI, Fecha en la que el titular de la tarjeta cumple 19 años. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N |
| [Under21Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under21until) { get; set; } | DDJ, Fecha en la que el titular de la tarjeta cumple 21 años. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N |
| [VehClassDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/vehclassdescription) { get; set; } | DCP, Texto que explica los códigos específicos de la jurisdicción para las clasificaciones de vehículos que el titular de la tarjeta está autorizado a conducir, DL, V50ANS |
| [VeteranIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/veteranindicator) { get; set; } | DDL, Campo que indica que el titular de la tarjeta es un veterano = “1”, DL/ID, F1N |
| [WeightKilograms](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightkilograms) { get; set; } | DAX, Peso del titular de la tarjeta en kilogramos, Ej. 84 kg = “084”, DL/ID, F3N |
| [WeightPounds](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightpounds) { get; set; } | DAW, Peso del titular de la tarjeta en libras, Ej. 185 lb = “185”, DL/ID, F3N |
| [WeightRange](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightrange) { get; set; } | DCE, Indica el rango de peso aproximado del titular de la tarjeta: 0 = hasta 31 kg (hasta 70 lb), 1 = 32 – 45 kg (71 – 100 lb), 2 = 46 - 59 kg (101 – 130 lb), 3 = 60 - 70 kg (131 – 160 lb), 4 = 71 - 86 kg (161 – 190 lb), 5 = 87 - 100 kg (191 – 220 lb), 6 = 101 - 113 kg (221 – 250 lb), 7 = 114 - 127 kg (251 – 280 lb), 8 = 128 – 145 kg (281 – 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N |

### Ver también

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


