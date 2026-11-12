---
title: "OptionalFields"
linktitle: "OptionalFields"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Elementos opcionales (campos) de la tarjeta"
type: docs
weight: 730
url: /es/nodejs/aspose.barcode/optionalfields/
---

## OptionalFields class

Elementos opcionales (campos) de la tarjeta

```js
new OptionalFields()
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getAliasAKAFamilyName()](#getaliasakafamilyname) | DBN, Otro apellido por el cual se conoce al titular de la tarjeta, DL/ID, V10ANS |
| [getAliasAKAGivenName()](#getaliasakagivenname) | DBG, Otro nombre de pila por el cual se conoce al titular de la tarjeta, DL/ID, V15ANS |
| [getAliasAKASuffixName()](#getaliasakasuffixname) | DBS, Otro sufijo por el cual se conoce al titular de la tarjeta, DL/ID, V5ANS |
| [getAuditInformation()](#getauditinformation) | DCJ, Una cadena de letras y/o números que identifica cuándo, dónde y por quién se emitió una licencia de conducir/tarjeta de identificación. Si un |
| [getCardRevisionDate()](#getcardrevisiondate) | DDB, campo requerido por DHS que indica la fecha del cambio de versión más reciente o modificación al formato visible de t |
| [getComplianceType()](#getcompliancetype) | DDA, campo requerido por DHS que indica cumplimiento: “F” = conforme; y, “N” = no conforme, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getendorsementcodedescription) | DCQ, Texto que explica el/los código(s) específico(s) de la jurisdicción que indica(n) privilegios de conducción adicionales otorgados al ca |
| [getHairColor()](#gethaircolor) | DAZ, Calvo, negro, rubio, castaño, gris, rojo/castaño rojizo, arena, blanco, desconocido. Si la jurisdicción emisora desea abreviar |
| [getHAZMATEndorsementExpDate()](#gethazmatendorsementexpdate) | DDC, Fecha en la que la autorización de material peligroso otorgada por el documento deja de ser válida. (MMDDCCYY para EE. UU., CC |
| [getInventoryControlNumber()](#getinventorycontrolnumber) | DCK, Una cadena de letras y/o números que se adhiere a las materias primas (cartulina, laminado, etc.) utilizadas en la produc |
| [getLimitedDurationDocIndicator()](#getlimiteddurationdocindicator) | DDD, campo requerido por DHS que indica que el titular de la tarjeta tiene estatus legal temporal = “1”, DL/ID, F1N |
| [getNameSuffix()](#getnamesuffix) | DCU, Sufijo de nombre (Si la jurisdicción participa en sistemas que requieren sufijo de nombre (PDPS, CDLIS, etc.), el sufijo debe ser |
| [getOrganDonorIndicator()](#getorgandonorindicator) | DDK, Campo que indica que el titular de la tarjeta es donante de órganos = “1”, DL/ID, F1N |
| [getPlaceOfBirth()](#getplaceofbirth) | DCI, País y municipio y/o estado/provincia, DL/ID, V33A |
| [getRaceEthnicity()](#getraceethnicity) | DCL, Códigos de raza o etnia del titular de la tarjeta, según lo definido en AAMVA D20, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getrestrictioncodedescription) | DCR, Texto que describe el/los código(s) de restricción específico(s) de la jurisdicción que limitan los privilegios de conducción, DL, V50ANS |
| [getStandardEndorsementCode()](#getstandardendorsementcode) | DCN, Código(s) de autorización estándar para el titular de la tarjeta. Ver códigos en D20. Este elemento de datos es un marcador de posición para esfuerzos futuros |
| [getStandardRestrictionCode()](#getstandardrestrictioncode) | DCO, Código(s) de restricción estándar para el titular de la tarjeta. Ver códigos en D20. Este elemento de datos es un marcador de posición para esfuerzos futuros |
| [getStandardVehClassification()](#getstandardvehclassification) | DCM, Código(s) de clasificación de vehículo estándar para el titular de la tarjeta. Este elemento de datos es un marcador de posición para futuros esfuerzos de st |
| [getUnder18Until()](#getunder18until) | DDH, Fecha en la que el titular de la tarjeta cumple 18 años. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N |
| [getUnder21Until()](#getunder21until) | DDJ, Fecha en la que el titular de la tarjeta cumple 21 años. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N |
| [getVehClassDescription()](#getvehclassdescription) | DCP, Texto que explica el/los código(s) específico(s) de la jurisdicción para clasificaciones de vehículos que el titular de la tarjeta está autorizado a condu |
| [getVeteranIndicator()](#getveteranindicator) | DDL, Campo que indica que el titular de la tarjeta es veterano = “1”, DL/ID, F1N |
| [getWeightKilograms()](#getweightkilograms) | DAX, Peso del titular de la tarjeta en kilogramos, Ej. 84 kg = “084”, DL/ID, F3N |
| [getWeightPounds()](#getweightpounds) | DAW, Peso del titular de la tarjeta en libras, Ej. 185 lb = “185”, DL/ID, F3N |
| [getWeightRange()](#getweightrange) | DCE, Indica el rango de peso aproximado del titular de la tarjeta: 0 = hasta 31 kg (hasta 70 lb), 1 = 32 – 45 kg (71 – 100 lb |
| [setAddressStreet2()](#setaddressstreet2) | DAH, Segunda línea de la parte calle de la dirección del titular de la tarjeta, DL/ID, V35ANS |
| [setAliasAKAFamilyName()](#setaliasakafamilyname) | DBN, Otro apellido por el cual se conoce al titular de la tarjeta, DL/ID, V10ANS |
| [setAliasAKAGivenName()](#setaliasakagivenname) | DBG, Otro nombre de pila por el cual se conoce al titular de la tarjeta, DL/ID, V15ANS |
| [setAliasAKASuffixName()](#setaliasakasuffixname) | DBS, Otro sufijo por el cual se conoce al titular de la tarjeta, DL/ID, V5ANS |
| [setAuditInformation()](#setauditinformation) | DCJ, Una cadena de letras y/o números que identifica cuándo, dónde y por quién se emitió una licencia de conducir/tarjeta de identificación. Si un |
| [setCardRevisionDate()](#setcardrevisiondate) | DDB, campo requerido por DHS que indica la fecha del cambio de versión más reciente o modificación al formato visible de t |
| [setComplianceType()](#setcompliancetype) | DDA, campo requerido por DHS que indica cumplimiento: “F” = conforme; y, “N” = no conforme, DL/ID, F1A |
| [setEndorsementCodeDescription()](#setendorsementcodedescription) | DCQ, Texto que explica el/los código(s) específico(s) de la jurisdicción que indica(n) privilegios de conducción adicionales otorgados al ca |
| [setHairColor()](#sethaircolor) | DAZ, Calvo, negro, rubio, castaño, gris, rojo/castaño rojizo, arena, blanco, desconocido. Si la jurisdicción emisora desea abreviar |
| [setInventoryControlNumber()](#setinventorycontrolnumber) | DCK, Una cadena de letras y/o números que se adhiere a las materias primas (cartulina, laminado, etc.) utilizadas en la produc |
| [setLimitedDurationDocIndicator()](#setlimiteddurationdocindicator) | DDD, campo requerido por DHS que indica que el titular de la tarjeta tiene estatus legal temporal = “1”, DL/ID, F1N |
| [setNameSuffix()](#setnamesuffix) | DCU, Sufijo de nombre (Si la jurisdicción participa en sistemas que requieren sufijo de nombre (PDPS, CDLIS, etc.), el sufijo debe ser |
| [setOrganDonorIndicator()](#setorgandonorindicator) | DDK, Campo que indica que el titular de la tarjeta es donante de órganos = “1”, DL/ID, F1N |
| [setPlaceOfBirth()](#setplaceofbirth) | DCI, País y municipio y/o estado/provincia, DL/ID, V33A |
| [setRaceEthnicity()](#setraceethnicity) | DCL, Códigos de raza o etnia del titular de la tarjeta, según lo definido en AAMVA D20, DL/ID, V3A |
| [setRestrictionCodeDescription()](#setrestrictioncodedescription) | DCR, Texto que describe el/los código(s) de restricción específico(s) de la jurisdicción que limitan los privilegios de conducción, DL, V50ANS |
| [setStandardEndorsementCode()](#setstandardendorsementcode) | DCN, Código(s) de autorización estándar para el titular de la tarjeta. Ver códigos en D20. Este elemento de datos es un marcador de posición para esfuerzos futuros |
| [setStandardRestrictionCode()](#setstandardrestrictioncode) | DCO, Código(s) de restricción estándar para el titular de la tarjeta. Ver códigos en D20. Este elemento de datos es un marcador de posición para esfuerzos futuros |
| [setStandardVehClassification()](#setstandardvehclassification) | DCM, Código(s) de clasificación de vehículo estándar para el titular de la tarjeta. Este elemento de datos es un marcador de posición para futuros esfuerzos de st |
| [setUnder18Until()](#setunder18until) | DDI, Fecha en la que el titular de la tarjeta cumple 19 años. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N |
| [setUnder19Until()](#setunder19until) | DDI, Fecha en la que el titular de la tarjeta cumple 19 años. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N |
| [setUnder21Until()](#setunder21until) | DDJ, Fecha en la que el titular de la tarjeta cumple 21 años. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N |
| [setVehClassDescription()](#setvehclassdescription) | DCP, Texto que explica el/los código(s) específico(s) de la jurisdicción para clasificaciones de vehículos que el titular de la tarjeta está autorizado a condu |
| [setVeteranIndicator()](#setveteranindicator) | DDL, Campo que indica que el titular de la tarjeta es veterano = “1”, DL/ID, F1N |
| [setWeightKilograms()](#setweightkilograms) | DAX, Peso del titular de la tarjeta en kilogramos, Ej. 84 kg = “084”, DL/ID, F3N |
| [setWeightPounds()](#setweightpounds) | DAW, Peso del titular de la tarjeta en libras, Ej. 185 lb = “185”, DL/ID, F3N |
| [setWeightRange()](#setweightrange) | DCE, Indica el rango de peso aproximado del titular de la tarjeta: 0 = hasta 31 kg (hasta 70 lb), 1 = 32 – 45 kg (71 – 100 lb |

### getAliasAKAFamilyName() {#getaliasakafamilyname}

DBN, Otro apellido por el cual se conoce al titular de la tarjeta, DL/ID, V10ANS

### getAliasAKAGivenName() {#getaliasakagivenname}

DBG, Otro nombre de pila por el cual se conoce al titular de la tarjeta, DL/ID, V15ANS

### getAliasAKASuffixName() {#getaliasakasuffixname}

DBS, Otro sufijo por el cual se conoce al titular de la tarjeta, DL/ID, V5ANS

### getAuditInformation() {#getauditinformation}

DCJ, Una cadena de letras y/o números que identifica cuándo, dónde y por quién se fabricó una licencia de conducir/tarjeta de identificación. Si la información de auditoría no se utiliza en la tarjeta o el MRT, debe incluirse en el registro del conductor, DL/ID, V25ANS

### getCardRevisionDate() {#getcardrevisiondate}

DDB, campo requerido por DHS que indica la fecha del cambio de versión más reciente o la modificación del formato visible del DL/ID. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N

### getComplianceType() {#getcompliancetype}

DDA, campo requerido por DHS que indica cumplimiento: “F” = conforme; y, “N” = no conforme, DL/ID, F1A

### getEndorsementCodeDescription() {#getendorsementcodedescription}

DCQ, Texto que explica el/los código(s) específico(s) de la jurisdicción que indica(n) privilegios de conducción adicionales otorgados al titular más allá de la clase de vehículo, DL, V50ANS

### getHairColor() {#gethaircolor}

DAZ, Calvo, negro, rubio, castaño, gris, rojo/castaño rojizo, arena, blanco, desconocido. Si la jurisdicción emisora desea abreviar los colores, se deben usar los códigos de tres caracteres provistos en AAMVA D20, DL/ID, V12A

### getHAZMATEndorsementExpDate() {#gethazmatendorsementexpdate}

DDC, Fecha en la que la autorización de material peligroso otorgada por el documento deja de ser válida. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL, F8N

### getInventoryControlNumber() {#getinventorycontrolnumber}

DCK, Una cadena de letras y/o números que se adhiere a los materiales crudos (papel base, laminado, etc.) utilizados en la producción de licencias de conducir y tarjetas de identificación. (campo recomendado por DHS), DL/ID, V25ANS

### getLimitedDurationDocIndicator() {#getlimiteddurationdocindicator}

DDD, campo requerido por DHS que indica que el titular de la tarjeta tiene estatus legal temporal = “1”, DL/ID, F1N

### getNameSuffix() {#getnamesuffix}

DCU, Sufijo de nombre (Si la jurisdicción participa en sistemas que requieren sufijo de nombre (PDPS, CDLIS, etc.), el sufijo debe recopilarse y mostrarse en el DL/ID y en el MRT). JR (Junior), SR (Senior), 1ST o I (Primero), hasta 9TH o IX (Noveno), DL/ID, V5ANS

### getOrganDonorIndicator() {#getorgandonorindicator}

DDK, Campo que indica que el titular de la tarjeta es donante de órganos = “1”, DL/ID, F1N

### getPlaceOfBirth() {#getplaceofbirth}

DCI, País y municipio y/o estado/provincia, DL/ID, V33A

### getRaceEthnicity() {#getraceethnicity}

DCL, Códigos de raza o etnia del titular de la tarjeta, según lo definido en AAMVA D20, DL/ID, V3A

### getRestrictionCodeDescription() {#getrestrictioncodedescription}

DCR, Texto que describe el/los código(s) de restricción específico(s) de la jurisdicción que limitan los privilegios de conducción, DL, V50ANS

### getStandardEndorsementCode() {#getstandardendorsementcode}

DCN, Código(s) de autorización estándar para el titular. Ver códigos en D20. Este elemento de datos es un marcador de posición para futuros esfuerzos de estandarización de códigos de autorización, DL, F5AN

### getStandardRestrictionCode() {#getstandardrestrictioncode}

DCO, Código(s) de restricción estándar para el titular. Ver códigos en D20. Este elemento de datos es un marcador de posición para futuros esfuerzos de estandarización de códigos de restricción, DL, F12AN

### getStandardVehClassification() {#getstandardvehclassification}

DCM, Código(s) de clasificación de vehículo estándar para el titular. Este elemento de datos es un marcador de posición para futuros esfuerzos de estandarización de clasificaciones de vehículos, DL, F4AN

### getUnder18Until() {#getunder18until}

DDH, Fecha en la que el titular de la tarjeta cumple 18 años. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N

### getUnder21Until() {#getunder21until}

DDJ, Fecha en la que el titular de la tarjeta cumple 21 años. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N

### getVehClassDescription() {#getvehclassdescription}

DCP, Texto que explica el/los código(s) específico(s) de la jurisdicción para las clasificaciones de vehículos que el titular está autorizado a conducir, DL, V50ANS

### getVeteranIndicator() {#getveteranindicator}

DDL, Campo que indica que el titular de la tarjeta es veterano = “1”, DL/ID, F1N

### getWeightKilograms() {#getweightkilograms}

DAX, Peso del titular de la tarjeta en kilogramos, Ej. 84 kg = “084”, DL/ID, F3N

### getWeightPounds() {#getweightpounds}

DAW, Peso del titular de la tarjeta en libras, Ej. 185 lb = “185”, DL/ID, F3N

### getWeightRange() {#getweightrange}

DCE, Indica el rango de peso aproximado del titular: 0 = hasta 31 kg (hasta 70 lb), 1 = 32 – 45 kg (71 – 100 lb), 2 = 46 - 59 kg (101 – 130 lb), 3 = 60 - 70 kg (131 – 160 lb), 4 = 71 - 86 kg (161 – 190 lb), 5 = 87 - 100 kg (191 – 220 lb), 6 = 101 - 113 kg (221 – 250 lb), 7 = 114 - 127 kg (251 – 280 lb), 8 = 128 – 145 kg (281 – 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N

### setAddressStreet2() {#setaddressstreet2}

DAH, Segunda línea de la parte calle de la dirección del titular de la tarjeta, DL/ID, V35ANS

### setAliasAKAFamilyName() {#setaliasakafamilyname}

DBN, Otro apellido por el cual se conoce al titular de la tarjeta, DL/ID, V10ANS

### setAliasAKAGivenName() {#setaliasakagivenname}

DBG, Otro nombre de pila por el cual se conoce al titular de la tarjeta, DL/ID, V15ANS

### setAliasAKASuffixName() {#setaliasakasuffixname}

DBS, Otro sufijo por el cual se conoce al titular de la tarjeta, DL/ID, V5ANS

### setAuditInformation() {#setauditinformation}

DCJ, Una cadena de letras y/o números que identifica cuándo, dónde y por quién se fabricó una licencia de conducir/tarjeta de identificación. Si la información de auditoría no se utiliza en la tarjeta o el MRT, debe incluirse en el registro del conductor, DL/ID, V25ANS

### setCardRevisionDate() {#setcardrevisiondate}

DDB, campo requerido por DHS que indica la fecha del cambio de versión más reciente o la modificación del formato visible del DL/ID. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N

### setComplianceType() {#setcompliancetype}

DDA, campo requerido por DHS que indica cumplimiento: “F” = conforme; y, “N” = no conforme, DL/ID, F1A

### setEndorsementCodeDescription() {#setendorsementcodedescription}

DCQ, Texto que explica el/los código(s) específico(s) de la jurisdicción que indica(n) privilegios de conducción adicionales otorgados al titular más allá de la clase de vehículo, DL, V50ANS

### setHairColor() {#sethaircolor}

DAZ, Calvo, negro, rubio, castaño, gris, rojo/castaño rojizo, arena, blanco, desconocido. Si la jurisdicción emisora desea abreviar los colores, se deben usar los códigos de tres caracteres provistos en AAMVA D20, DL/ID, V12A

### setInventoryControlNumber() {#setinventorycontrolnumber}

DCK, Una cadena de letras y/o números que se adhiere a los materiales crudos (papel base, laminado, etc.) utilizados en la producción de licencias de conducir y tarjetas de identificación. (campo recomendado por DHS), DL/ID, V25ANS

### setLimitedDurationDocIndicator() {#setlimiteddurationdocindicator}

DDD, campo requerido por DHS que indica que el titular de la tarjeta tiene estatus legal temporal = “1”, DL/ID, F1N

### setNameSuffix() {#setnamesuffix}

DCU, Sufijo de nombre (Si la jurisdicción participa en sistemas que requieren sufijo de nombre (PDPS, CDLIS, etc.), el sufijo debe recopilarse y mostrarse en el DL/ID y en el MRT). JR (Junior), SR (Senior), 1ST o I (Primero), hasta 9TH o IX (Noveno), DL/ID, V5ANS

### setOrganDonorIndicator() {#setorgandonorindicator}

DDK, Campo que indica que el titular de la tarjeta es donante de órganos = “1”, DL/ID, F1N

### setPlaceOfBirth() {#setplaceofbirth}

DCI, País y municipio y/o estado/provincia, DL/ID, V33A

### setRaceEthnicity() {#setraceethnicity}

DCL, Códigos de raza o etnia del titular de la tarjeta, según lo definido en AAMVA D20, DL/ID, V3A

### setRestrictionCodeDescription() {#setrestrictioncodedescription}

DCR, Texto que describe el/los código(s) de restricción específico(s) de la jurisdicción que limitan los privilegios de conducción, DL, V50ANS

### setStandardEndorsementCode() {#setstandardendorsementcode}

DCN, Código(s) de autorización estándar para el titular. Ver códigos en D20. Este elemento de datos es un marcador de posición para futuros esfuerzos de estandarización de códigos de autorización, DL, F5AN

### setStandardRestrictionCode() {#setstandardrestrictioncode}

DCO, Código(s) de restricción estándar para el titular. Ver códigos en D20. Este elemento de datos es un marcador de posición para futuros esfuerzos de estandarización de códigos de restricción, DL, F12AN

### setStandardVehClassification() {#setstandardvehclassification}

DCM, Código(s) de clasificación de vehículo estándar para el titular. Este elemento de datos es un marcador de posición para futuros esfuerzos de estandarización de clasificaciones de vehículos, DL, F4AN

### setUnder18Until() {#setunder18until}

DDI, Fecha en la que el titular de la tarjeta cumple 19 años. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N

### setUnder19Until() {#setunder19until}

DDI, Fecha en la que el titular de la tarjeta cumple 19 años. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N

### setUnder21Until() {#setunder21until}

DDJ, Fecha en la que el titular de la tarjeta cumple 21 años. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N

### setVehClassDescription() {#setvehclassdescription}

DCP, Texto que explica el/los código(s) específico(s) de la jurisdicción para las clasificaciones de vehículos que el titular está autorizado a conducir, DL, V50ANS

### setVeteranIndicator() {#setveteranindicator}

DDL, Campo que indica que el titular de la tarjeta es veterano = “1”, DL/ID, F1N

### setWeightKilograms() {#setweightkilograms}

DAX, Peso del titular de la tarjeta en kilogramos, Ej. 84 kg = “084”, DL/ID, F3N

### setWeightPounds() {#setweightpounds}

DAW, Peso del titular de la tarjeta en libras, Ej. 185 lb = “185”, DL/ID, F3N

### setWeightRange() {#setweightrange}

DCE, Indica el rango de peso aproximado del titular: 0 = hasta 31 kg (hasta 70 lb), 1 = 32 – 45 kg (71 – 100 lb), 2 = 46 - 59 kg (101 – 130 lb), 3 = 60 - 70 kg (131 – 160 lb), 4 = 71 - 86 kg (161 – 190 lb), 5 = 87 - 100 kg (191 – 220 lb), 6 = 101 - 113 kg (221 – 250 lb), 7 = 114 - 127 kg (251 – 280 lb), 8 = 128 – 145 kg (281 – 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N
