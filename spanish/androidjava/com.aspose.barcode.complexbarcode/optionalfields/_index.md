---
title: USADriveIdCodetext.OptionalFields
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Campos opcionales de los elementos de la tarjeta.
type: docs
weight: 11
url: /es/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.OptionalFields
```

Elementos opcionales (campos) de la tarjeta
## Constructors

| Constructor | Descripción |
| --- | --- |
| [OptionalFields()](#OptionalFields--) |  |
## Methods

| Method | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressStreet2()](#getAddressStreet2--) | DAH, Segunda línea de la porción de calle de la dirección del titular de la tarjeta, DL/ID, V35ANS |
| [getAliasAKAFamilyName()](#getAliasAKAFamilyName--) | DBN, Otro apellido por el cual se conoce al titular de la tarjeta, DL/ID, V10ANS |
| [getAliasAKAGivenName()](#getAliasAKAGivenName--) | DBG, Otro nombre de pila por el cual se conoce al titular de la tarjeta, DL/ID, V15ANS |
| [getAliasAKASuffixName()](#getAliasAKASuffixName--) | DBS, Otro sufijo por el cual se conoce al titular de la tarjeta, DL/ID, V5ANS |
| [getAuditInformation()](#getAuditInformation--) | DCJ, Una cadena de letras y/o números que identifica cuándo, dónde y por quién se fabricó una licencia de conducir/tarjeta de identificación. |
| [getCardRevisionDate()](#getCardRevisionDate--) | DDB, Campo requerido por DHS que indica la fecha del cambio de versión más reciente o la modificación del formato visible del DL/ID. |
| [getClass()](#getClass--) |  |
| [getComplianceType()](#getComplianceType--) | DDA, Campo requerido por DHS que indica cumplimiento: \u201cF\u201d = conforme; y, \u201cN\u201d = no conforme, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getEndorsementCodeDescription--) | DCQ, Texto que explica el/los código(s) específico(s) de la jurisdicción que indica(n) privilegios de conducción adicionales otorgados al titular de la tarjeta más allá de la clase de vehículo, DL, V50ANS |
| [getHAZMATEndorsementExpDate()](#getHAZMATEndorsementExpDate--) | DDC, Fecha en la que la autorización de material peligroso otorgada por el documento deja de ser válida. |
| [getHairColor()](#getHairColor--) | DAZ, Calvo, negro, rubio, castaño, gris, rojo/marrón, arena, blanco, desconocido. |
| [getInventoryControlNumber()](#getInventoryControlNumber--) | DCK, Una cadena de letras y/o números que se adhiere a los materiales crudos (papel de tarjeta, laminado, etc.) utilizados en la producción de licencias de conducir y tarjetas de identificación. |
| [getLimitedDurationDocIndicator()](#getLimitedDurationDocIndicator--) | DDD, Campo requerido por DHS que indica que el titular de la tarjeta tiene estatus legal temporal = \u201c1\u201d, DL/ID, F1N |
| [getNameSuffix()](#getNameSuffix--) | DCU, Sufijo de nombre (Si la jurisdicción participa en sistemas que requieren sufijo de nombre (PDPS, CDLIS, etc.), el sufijo debe recopilarse y mostrarse en el DL/ID y en el MRT). |
| [getOrganDonorIndicator()](#getOrganDonorIndicator--) | DDK, Campo que indica que el titular de la tarjeta es donante de órganos = \u201c1\u201d, DL/ID, F1N |
| [getPlaceOfBirth()](#getPlaceOfBirth--) | DCI, País y municipio y/o estado/provincia, DL/ID, V33A |
| [getRaceEthnicity()](#getRaceEthnicity--) | DCL, Códigos de raza o etnia del titular de la tarjeta, según lo definido en AAMVA D20, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getRestrictionCodeDescription--) | DCR, Texto que describe el/los código(s) de restricción específico(s) de la jurisdicción que limitan los privilegios de conducción, DL, V50ANS |
| [getStandardEndorsementCode()](#getStandardEndorsementCode--) | DCN, Código(s) de autorización estándar para el titular de la tarjeta. |
| [getStandardRestrictionCode()](#getStandardRestrictionCode--) | DCO, Código(s) de restricción estándar para el titular de la tarjeta. |
| [getStandardVehClassification()](#getStandardVehClassification--) | DCM, Código(s) de clasificación de vehículo estándar para el titular de la tarjeta. |
| [getUnder18Until()](#getUnder18Until--) | DDH, Date on which the cardholder turns 18 years old. |
| [getUnder19Until()](#getUnder19Until--) | DDI, Date on which the cardholder turns 19 years old. |
| [getUnder21Until()](#getUnder21Until--) | DDJ, Date on which the cardholder turns 21 years old. |
| [getVehClassDescription()](#getVehClassDescription--) | DCP, Text that explains the jurisdiction-specific code(s) for classifications of vehicles cardholder is authorized to drive, DL, V50ANS |
| [getVeteranIndicator()](#getVeteranIndicator--) | DDL, Field that indicates that the cardholder is a veteran = \\u201c1\\u201d, DL/ID, F1N |
| [getWeightKilograms()](#getWeightKilograms--) | DAX, Cardholder weight in kilograms, Ex. |
| [getWeightPounds()](#getWeightPounds--) | DAW, Cardholder weight in pounds, Ex. |
| [getWeightRange()](#getWeightRange--) | DCE, Indicates the approximate weight range of the cardholder: 0 = up to 31 kg(up to 70 lbs), 1 = 32 \\u2013 45 kg(71 \\u2013 100 lbs), 2 = 46 - 59 kg(101 \\u2013 130 lbs), 3 = 60 - 70 kg(131 \\u2013 160 lbs), 4 = 71 - 86 kg(161 \\u2013 190 lbs), 5 = 87 - 100 kg(191 \\u2013 220 lbs), 6 = 101 - 113 kg(221 \\u2013 250 lbs), 7 = 114 - 127 kg(251 \\u2013 280 lbs), 8 = 128 \\u2013 145 kg(281 \\u2013 320 lbs), 9 = 146+ kg(321+ lbs), DL/ID, F1N |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressStreet2(String value)](#setAddressStreet2-java.lang.String-) | DAH, Segunda línea de la porción de calle de la dirección del titular de la tarjeta, DL/ID, V35ANS |
| [setAliasAKAFamilyName(String value)](#setAliasAKAFamilyName-java.lang.String-) | DBN, Otro apellido por el cual se conoce al titular de la tarjeta, DL/ID, V10ANS |
| [setAliasAKAGivenName(String value)](#setAliasAKAGivenName-java.lang.String-) | DBG, Otro nombre de pila por el cual se conoce al titular de la tarjeta, DL/ID, V15ANS |
| [setAliasAKASuffixName(String value)](#setAliasAKASuffixName-java.lang.String-) | DBS, Otro sufijo por el cual se conoce al titular de la tarjeta, DL/ID, V5ANS |
| [setAuditInformation(String value)](#setAuditInformation-java.lang.String-) | DCJ, Una cadena de letras y/o números que identifica cuándo, dónde y por quién se fabricó una licencia de conducir/tarjeta de identificación. |
| [setCardRevisionDate(LocalDate value)](#setCardRevisionDate-java.time.LocalDate-) | DDB, Campo requerido por DHS que indica la fecha del cambio de versión más reciente o la modificación del formato visible del DL/ID. |
| [setComplianceType(String value)](#setComplianceType-java.lang.String-) | DDA, Campo requerido por DHS que indica cumplimiento: \u201cF\u201d = conforme; y, \u201cN\u201d = no conforme, DL/ID, F1A |
| [setEndorsementCodeDescription(String value)](#setEndorsementCodeDescription-java.lang.String-) | DCQ, Texto que explica el/los código(s) específico(s) de la jurisdicción que indica(n) privilegios de conducción adicionales otorgados al titular de la tarjeta más allá de la clase de vehículo, DL, V50ANS |
| [setHairColor(USADriveIdHairColor value)](#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-) | DAZ, Calvo, negro, rubio, castaño, gris, rojo/marrón, arena, blanco, desconocido. |
| [setInventoryControlNumber(String value)](#setInventoryControlNumber-java.lang.String-) | DCK, Una cadena de letras y/o números que se adhiere a los materiales crudos (papel de tarjeta, laminado, etc.) utilizados en la producción de licencias de conducir y tarjetas de identificación. |
| [setLimitedDurationDocIndicator(String value)](#setLimitedDurationDocIndicator-java.lang.String-) | DDD, Campo requerido por DHS que indica que el titular de la tarjeta tiene estatus legal temporal = \u201c1\u201d, DL/ID, F1N |
| [setNameSuffix(String value)](#setNameSuffix-java.lang.String-) | DCU, Sufijo de nombre (Si la jurisdicción participa en sistemas que requieren sufijo de nombre (PDPS, CDLIS, etc.), el sufijo debe recopilarse y mostrarse en el DL/ID y en el MRT). |
| [setOrganDonorIndicator(String value)](#setOrganDonorIndicator-java.lang.String-) | DDK, Campo que indica que el titular de la tarjeta es donante de órganos = \u201c1\u201d, DL/ID, F1N |
| [setPlaceOfBirth(String value)](#setPlaceOfBirth-java.lang.String-) | DCI, País y municipio y/o estado/provincia, DL/ID, V33A |
| [setRaceEthnicity(String value)](#setRaceEthnicity-java.lang.String-) | DCL, Códigos de raza o etnia del titular de la tarjeta, según lo definido en AAMVA D20, DL/ID, V3A |
| [setRestrictionCodeDescription(String value)](#setRestrictionCodeDescription-java.lang.String-) | DCR, Texto que describe el/los código(s) de restricción específico(s) de la jurisdicción que limitan los privilegios de conducción, DL, V50ANS |
| [setStandardEndorsementCode(String value)](#setStandardEndorsementCode-java.lang.String-) | DCN, Código(s) de autorización estándar para el titular de la tarjeta. |
| [setStandardRestrictionCode(String value)](#setStandardRestrictionCode-java.lang.String-) | DCO, Código(s) de restricción estándar para el titular de la tarjeta. |
| [setStandardVehClassification(String value)](#setStandardVehClassification-java.lang.String-) | DCM, Código(s) de clasificación de vehículo estándar para el titular de la tarjeta. |
| [setUnder18Until(LocalDate value)](#setUnder18Until-java.time.LocalDate-) | DDH, Date on which the cardholder turns 18 years old. |
| [setUnder19Until(LocalDate value)](#setUnder19Until-java.time.LocalDate-) | DDI, Date on which the cardholder turns 19 years old. |
| [setUnder21Until(LocalDate value)](#setUnder21Until-java.time.LocalDate-) | DDJ, Date on which the cardholder turns 21 years old. |
| [setVehClassDescription(String value)](#setVehClassDescription-java.lang.String-) | DCP, Text that explains the jurisdiction-specific code(s) for classifications of vehicles cardholder is authorized to drive, DL, V50ANS |
| [setVeteranIndicator(String value)](#setVeteranIndicator-java.lang.String-) | DDL, Field that indicates that the cardholder is a veteran = \\u201c1\\u201d, DL/ID, F1N |
| [setWeightKilograms(int value)](#setWeightKilograms-int-) | DAX, Cardholder weight in kilograms, Ex. |
| [setWeightPounds(int value)](#setWeightPounds-int-) | DAW, Cardholder weight in pounds, Ex. |
| [setWeightRange(String value)](#setWeightRange-java.lang.String-) | DCE, Indicates the approximate weight range of the cardholder: 0 = up to 31 kg(up to 70 lbs), 1 = 32 \\u2013 45 kg(71 \\u2013 100 lbs), 2 = 46 - 59 kg(101 \\u2013 130 lbs), 3 = 60 - 70 kg(131 \\u2013 160 lbs), 4 = 71 - 86 kg(161 \\u2013 190 lbs), 5 = 87 - 100 kg(191 \\u2013 220 lbs), 6 = 101 - 113 kg(221 \\u2013 250 lbs), 7 = 114 - 127 kg(251 \\u2013 280 lbs), 8 = 128 \\u2013 145 kg(281 \\u2013 320 lbs), 9 = 146+ kg(321+ lbs), DL/ID, F1N |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OptionalFields() {#OptionalFields--}
```
public OptionalFields()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAddressStreet2() {#getAddressStreet2--}
```
public final String getAddressStreet2()
```


DAH, Segunda línea de la porción de calle de la dirección del titular de la tarjeta, DL/ID, V35ANS

**Returns:**
java.lang.String
### getAliasAKAFamilyName() {#getAliasAKAFamilyName--}
```
public final String getAliasAKAFamilyName()
```


DBN, Otro apellido por el cual se conoce al titular de la tarjeta, DL/ID, V10ANS

**Returns:**
java.lang.String
### getAliasAKAGivenName() {#getAliasAKAGivenName--}
```
public final String getAliasAKAGivenName()
```


DBG, Otro nombre de pila por el cual se conoce al titular de la tarjeta, DL/ID, V15ANS

**Returns:**
java.lang.String
### getAliasAKASuffixName() {#getAliasAKASuffixName--}
```
public final String getAliasAKASuffixName()
```


DBS, Otro sufijo por el cual se conoce al titular de la tarjeta, DL/ID, V5ANS

**Returns:**
java.lang.String
### getAuditInformation() {#getAuditInformation--}
```
public final String getAuditInformation()
```


DCJ, A string of letters and/or numbers that identifies when, where, and by whom a driver license/ID card was made. If audit information is not used on the card or the MRT, it must be included in the driver record, DL/ID, V25ANS

**Returns:**
java.lang.String
### getCardRevisionDate() {#getCardRevisionDate--}
```
public final LocalDate getCardRevisionDate()
```


DDB, DHS required field that indicates date of the most recent version change or modification to the visible format of the DL/ID. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComplianceType() {#getComplianceType--}
```
public final String getComplianceType()
```


DDA, Campo requerido por DHS que indica cumplimiento: \u201cF\u201d = conforme; y, \u201cN\u201d = no conforme, DL/ID, F1A

**Returns:**
java.lang.String
### getEndorsementCodeDescription() {#getEndorsementCodeDescription--}
```
public final String getEndorsementCodeDescription()
```


DCQ, Texto que explica el/los código(s) específico(s) de la jurisdicción que indica(n) privilegios de conducción adicionales otorgados al titular de la tarjeta más allá de la clase de vehículo, DL, V50ANS

**Returns:**
java.lang.String
### getHAZMATEndorsementExpDate() {#getHAZMATEndorsementExpDate--}
```
public final LocalDate getHAZMATEndorsementExpDate()
```


DDC, Date on which the hazardous material endorsement granted by the document is no longer valid. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL, F8N

**Returns:**
java.time.LocalDate
### getHairColor() {#getHairColor--}
```
public final USADriveIdHairColor getHairColor()
```


DAZ, Bald, black, blonde, brown, gray, red/auburn, sandy, white, unknown. If the issuing jurisdiction wishes to abbreviate colors, the three-character codes provided in AAMVA D20 must be used, DL/ID, V12A

**Returns:**
[USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor)
### getInventoryControlNumber() {#getInventoryControlNumber--}
```
public final String getInventoryControlNumber()
```


DCK, A string of letters and/or numbers that is affixed to the raw materials(card stock, laminate, etc.) used in producing driver licenses and ID cards. (DHS recommended field), DL/ID, V25ANS

**Returns:**
java.lang.String
### getLimitedDurationDocIndicator() {#getLimitedDurationDocIndicator--}
```
public final String getLimitedDurationDocIndicator()
```


DDD, Campo requerido por DHS que indica que el titular de la tarjeta tiene estatus legal temporal = \u201c1\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getNameSuffix() {#getNameSuffix--}
```
public final String getNameSuffix()
```


DCU, Name Suffix (If jurisdiction participates in systems requiring name suffix (PDPS, CDLIS, etc.), the suffix must be collected and displayed on the DL/ID and in the MRT). JR(Junior), SR(Senior), 1ST or I(First), up to 9TH or IX (Ninth), DL/ID, V5ANS

**Returns:**
java.lang.String
### getOrganDonorIndicator() {#getOrganDonorIndicator--}
```
public final String getOrganDonorIndicator()
```


DDK, Campo que indica que el titular de la tarjeta es donante de órganos = \u201c1\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getPlaceOfBirth() {#getPlaceOfBirth--}
```
public final String getPlaceOfBirth()
```


DCI, País y municipio y/o estado/provincia, DL/ID, V33A

**Returns:**
java.lang.String
### getRaceEthnicity() {#getRaceEthnicity--}
```
public final String getRaceEthnicity()
```


DCL, Códigos de raza o etnia del titular de la tarjeta, según lo definido en AAMVA D20, DL/ID, V3A

**Returns:**
java.lang.String
### getRestrictionCodeDescription() {#getRestrictionCodeDescription--}
```
public final String getRestrictionCodeDescription()
```


DCR, Texto que describe el/los código(s) de restricción específico(s) de la jurisdicción que limitan los privilegios de conducción, DL, V50ANS

**Returns:**
java.lang.String
### getStandardEndorsementCode() {#getStandardEndorsementCode--}
```
public final String getStandardEndorsementCode()
```


DCN, Standard endorsement code(s) for cardholder. See codes in D20.This data element is a placeholder for future efforts to standardize endorsement codes, DL, F5AN

**Returns:**
java.lang.String
### getStandardRestrictionCode() {#getStandardRestrictionCode--}
```
public final String getStandardRestrictionCode()
```


DCO, Standard restriction code(s) for cardholder. See codes in D20.This data element is a placeholder for future efforts to standardize restriction codes, DL, F12AN

**Returns:**
java.lang.String
### getStandardVehClassification() {#getStandardVehClassification--}
```
public final String getStandardVehClassification()
```


DCM, Standard vehicle classification code(s) for cardholder. This data element is a placeholder for future efforts to standardize vehicle classifications, DL, F4AN

**Returns:**
java.lang.String
### getUnder18Until() {#getUnder18Until--}
```
public final LocalDate getUnder18Until()
```


DDH, Date on which the cardholder turns 18 years old. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getUnder19Until() {#getUnder19Until--}
```
public final LocalDate getUnder19Until()
```


DDI, Date on which the cardholder turns 19 years old. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getUnder21Until() {#getUnder21Until--}
```
public final LocalDate getUnder21Until()
```


DDJ, Date on which the cardholder turns 21 years old. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getVehClassDescription() {#getVehClassDescription--}
```
public final String getVehClassDescription()
```


DCP, Text that explains the jurisdiction-specific code(s) for classifications of vehicles cardholder is authorized to drive, DL, V50ANS

**Returns:**
java.lang.String
### getVeteranIndicator() {#getVeteranIndicator--}
```
public final String getVeteranIndicator()
```


DDL, Field that indicates that the cardholder is a veteran = \\u201c1\\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getWeightKilograms() {#getWeightKilograms--}
```
public final int getWeightKilograms()
```


DAX, Cardholder weight in kilograms, Ex. 84 kg = \\u201c084\\u201d, DL/ID, F3N

**Returns:**
int
### getWeightPounds() {#getWeightPounds--}
```
public final int getWeightPounds()
```


DAW, Cardholder weight in pounds, Ex. 185 lb = \\u201c185\\u201d, DL/ID, F3N

**Returns:**
int
### getWeightRange() {#getWeightRange--}
```
public final String getWeightRange()
```


DCE, Indicates the approximate weight range of the cardholder: 0 = up to 31 kg(up to 70 lbs), 1 = 32 \\u2013 45 kg(71 \\u2013 100 lbs), 2 = 46 - 59 kg(101 \\u2013 130 lbs), 3 = 60 - 70 kg(131 \\u2013 160 lbs), 4 = 71 - 86 kg(161 \\u2013 190 lbs), 5 = 87 - 100 kg(191 \\u2013 220 lbs), 6 = 101 - 113 kg(221 \\u2013 250 lbs), 7 = 114 - 127 kg(251 \\u2013 280 lbs), 8 = 128 \\u2013 145 kg(281 \\u2013 320 lbs), 9 = 146+ kg(321+ lbs), DL/ID, F1N

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAddressStreet2(String value) {#setAddressStreet2-java.lang.String-}
```
public final void setAddressStreet2(String value)
```


DAH, Segunda línea de la porción de calle de la dirección del titular de la tarjeta, DL/ID, V35ANS

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setAliasAKAFamilyName(String value) {#setAliasAKAFamilyName-java.lang.String-}
```
public final void setAliasAKAFamilyName(String value)
```


DBN, Otro apellido por el cual se conoce al titular de la tarjeta, DL/ID, V10ANS

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setAliasAKAGivenName(String value) {#setAliasAKAGivenName-java.lang.String-}
```
public final void setAliasAKAGivenName(String value)
```


DBG, Otro nombre de pila por el cual se conoce al titular de la tarjeta, DL/ID, V15ANS

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setAliasAKASuffixName(String value) {#setAliasAKASuffixName-java.lang.String-}
```
public final void setAliasAKASuffixName(String value)
```


DBS, Otro sufijo por el cual se conoce al titular de la tarjeta, DL/ID, V5ANS

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setAuditInformation(String value) {#setAuditInformation-java.lang.String-}
```
public final void setAuditInformation(String value)
```


DCJ, A string of letters and/or numbers that identifies when, where, and by whom a driver license/ID card was made. If audit information is not used on the card or the MRT, it must be included in the driver record, DL/ID, V25ANS

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setCardRevisionDate(LocalDate value) {#setCardRevisionDate-java.time.LocalDate-}
```
public final void setCardRevisionDate(LocalDate value)
```


DDB, DHS required field that indicates date of the most recent version change or modification to the visible format of the DL/ID. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL/ID, F8N

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.time.LocalDate |  |

### setComplianceType(String value) {#setComplianceType-java.lang.String-}
```
public final void setComplianceType(String value)
```


DDA, Campo requerido por DHS que indica cumplimiento: \u201cF\u201d = conforme; y, \u201cN\u201d = no conforme, DL/ID, F1A

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setEndorsementCodeDescription(String value) {#setEndorsementCodeDescription-java.lang.String-}
```
public final void setEndorsementCodeDescription(String value)
```


DCQ, Texto que explica el/los código(s) específico(s) de la jurisdicción que indica(n) privilegios de conducción adicionales otorgados al titular de la tarjeta más allá de la clase de vehículo, DL, V50ANS

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setHairColor(USADriveIdHairColor value) {#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-}
```
public final void setHairColor(USADriveIdHairColor value)
```


DAZ, Bald, black, blonde, brown, gray, red/auburn, sandy, white, unknown. If the issuing jurisdiction wishes to abbreviate colors, the three-character codes provided in AAMVA D20 must be used, DL/ID, V12A

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor) |  |

### setInventoryControlNumber(String value) {#setInventoryControlNumber-java.lang.String-}
```
public final void setInventoryControlNumber(String value)
```


DCK, A string of letters and/or numbers that is affixed to the raw materials(card stock, laminate, etc.) used in producing driver licenses and ID cards. (DHS recommended field), DL/ID, V25ANS

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setLimitedDurationDocIndicator(String value) {#setLimitedDurationDocIndicator-java.lang.String-}
```
public final void setLimitedDurationDocIndicator(String value)
```


DDD, Campo requerido por DHS que indica que el titular de la tarjeta tiene estatus legal temporal = \u201c1\u201d, DL/ID, F1N

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setNameSuffix(String value) {#setNameSuffix-java.lang.String-}
```
public final void setNameSuffix(String value)
```


DCU, Name Suffix (If jurisdiction participates in systems requiring name suffix (PDPS, CDLIS, etc.), the suffix must be collected and displayed on the DL/ID and in the MRT). JR(Junior), SR(Senior), 1ST or I(First), up to 9TH or IX (Ninth), DL/ID, V5ANS

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setOrganDonorIndicator(String value) {#setOrganDonorIndicator-java.lang.String-}
```
public final void setOrganDonorIndicator(String value)
```


DDK, Campo que indica que el titular de la tarjeta es donante de órganos = \u201c1\u201d, DL/ID, F1N

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setPlaceOfBirth(String value) {#setPlaceOfBirth-java.lang.String-}
```
public final void setPlaceOfBirth(String value)
```


DCI, País y municipio y/o estado/provincia, DL/ID, V33A

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setRaceEthnicity(String value) {#setRaceEthnicity-java.lang.String-}
```
public final void setRaceEthnicity(String value)
```


DCL, Códigos de raza o etnia del titular de la tarjeta, según lo definido en AAMVA D20, DL/ID, V3A

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setRestrictionCodeDescription(String value) {#setRestrictionCodeDescription-java.lang.String-}
```
public final void setRestrictionCodeDescription(String value)
```


DCR, Texto que describe el/los código(s) de restricción específico(s) de la jurisdicción que limitan los privilegios de conducción, DL, V50ANS

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setStandardEndorsementCode(String value) {#setStandardEndorsementCode-java.lang.String-}
```
public final void setStandardEndorsementCode(String value)
```


DCN, Standard endorsement code(s) for cardholder. See codes in D20.This data element is a placeholder for future efforts to standardize endorsement codes, DL, F5AN

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setStandardRestrictionCode(String value) {#setStandardRestrictionCode-java.lang.String-}
```
public final void setStandardRestrictionCode(String value)
```


DCO, Standard restriction code(s) for cardholder. See codes in D20.This data element is a placeholder for future efforts to standardize restriction codes, DL, F12AN

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setStandardVehClassification(String value) {#setStandardVehClassification-java.lang.String-}
```
public final void setStandardVehClassification(String value)
```


DCM, Standard vehicle classification code(s) for cardholder. This data element is a placeholder for future efforts to standardize vehicle classifications, DL, F4AN

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setUnder18Until(LocalDate value) {#setUnder18Until-java.time.LocalDate-}
```
public final void setUnder18Until(LocalDate value)
```


DDH, Date on which the cardholder turns 18 years old. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL/ID, F8N

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.time.LocalDate |  |

### setUnder19Until(LocalDate value) {#setUnder19Until-java.time.LocalDate-}
```
public final void setUnder19Until(LocalDate value)
```


DDI, Date on which the cardholder turns 19 years old. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL/ID, F8N

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.time.LocalDate |  |

### setUnder21Until(LocalDate value) {#setUnder21Until-java.time.LocalDate-}
```
public final void setUnder21Until(LocalDate value)
```


DDJ, Date on which the cardholder turns 21 years old. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL/ID, F8N

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.time.LocalDate |  |

### setVehClassDescription(String value) {#setVehClassDescription-java.lang.String-}
```
public final void setVehClassDescription(String value)
```


DCP, Text that explains the jurisdiction-specific code(s) for classifications of vehicles cardholder is authorized to drive, DL, V50ANS

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setVeteranIndicator(String value) {#setVeteranIndicator-java.lang.String-}
```
public final void setVeteranIndicator(String value)
```


DDL, Field that indicates that the cardholder is a veteran = \\u201c1\\u201d, DL/ID, F1N

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setWeightKilograms(int value) {#setWeightKilograms-int-}
```
public final void setWeightKilograms(int value)
```


DAX, Cardholder weight in kilograms, Ex. 84 kg = \\u201c084\\u201d, DL/ID, F3N

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setWeightPounds(int value) {#setWeightPounds-int-}
```
public final void setWeightPounds(int value)
```


DAW, Cardholder weight in pounds, Ex. 185 lb = \\u201c185\\u201d, DL/ID, F3N

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setWeightRange(String value) {#setWeightRange-java.lang.String-}
```
public final void setWeightRange(String value)
```


DCE, Indicates the approximate weight range of the cardholder: 0 = up to 31 kg(up to 70 lbs), 1 = 32 \\u2013 45 kg(71 \\u2013 100 lbs), 2 = 46 - 59 kg(101 \\u2013 130 lbs), 3 = 60 - 70 kg(131 \\u2013 160 lbs), 4 = 71 - 86 kg(161 \\u2013 190 lbs), 5 = 87 - 100 kg(191 \\u2013 220 lbs), 6 = 101 - 113 kg(221 \\u2013 250 lbs), 7 = 114 - 127 kg(251 \\u2013 280 lbs), 8 = 128 \\u2013 145 kg(281 \\u2013 320 lbs), 9 = 146+ kg(321+ lbs), DL/ID, F1N

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |
| arg1 | int |  |

