---
title: "USADriveIdCodetext.OptionalFields"
second_title: "Referencia de API de Aspose.BarCode para Java"
description: "Campos opcionales de elementos de la tarjeta"
type: docs
weight: 11
url: /es/java/com.aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.OptionalFields
```

Elementos opcionales (campos) de la tarjeta
## Constructores

| Constructor | Descripción |
| --- | --- |
| [OptionalFields()](#OptionalFields--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressStreet2()](#getAddressStreet2--) | DAH, Segunda línea de la porción de calle de la dirección del titular de la tarjeta, DL/ID, V35ANS |
| [getAliasAKAFamilyName()](#getAliasAKAFamilyName--) | DBN, Otro apellido por el cual se conoce al titular de la tarjeta, DL/ID, V10ANS |
| [getAliasAKAGivenName()](#getAliasAKAGivenName--) | DBG, Otro nombre de pila por el cual se conoce al titular de la tarjeta, DL/ID, V15ANS |
| [getAliasAKASuffixName()](#getAliasAKASuffixName--) | DBS, Otro sufijo por el cual se conoce al titular de la tarjeta, DL/ID, V5ANS |
| [getAuditInformation()](#getAuditInformation--) | DCJ, Una cadena de letras y/o números que identifica cuándo, dónde y por quién se fabricó una licencia de conducir/tarjeta de identificación. |
| [getCardRevisionDate()](#getCardRevisionDate--) | DDB, Campo requerido por DHS que indica la fecha del cambio de versión más reciente o modificación al formato visible del DL/ID. |
| [getClass()](#getClass--) |  |
| [getComplianceType()](#getComplianceType--) | DDA, Campo requerido por DHS que indica cumplimiento: \\u201cF\\u201d = conforme; y, \\u201cN\\u201d = no conforme, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getEndorsementCodeDescription--) | DCQ, Texto que explica el/los código(s) específico(s) de la jurisdicción que indica(n) privilegios de conducción adicionales otorgados al titular más allá de la clase de vehículo, DL, V50ANS |
| [getHAZMATEndorsementExpDate()](#getHAZMATEndorsementExpDate--) | DDC, Fecha en la que la autorización de materiales peligrosos otorgada por el documento deja de ser válida. |
| [getHairColor()](#getHairColor--) | DAZ, Calvo, negro, rubio, castaño, gris, rojo/marrón, arena, blanco, desconocido. |
| [getInventoryControlNumber()](#getInventoryControlNumber--) | DCK, Una cadena de letras y/o números que se adhiere a los materiales crudos (cartulina, laminado, etc.) utilizados en la producción de licencias de conducir y tarjetas de identificación. |
| [getLimitedDurationDocIndicator()](#getLimitedDurationDocIndicator--) | DDD, Campo requerido por DHS que indica que el titular tiene estatus legal temporal = \\u201c1\\u201d, DL/ID, F1N |
| [getNameSuffix()](#getNameSuffix--) | DCU, Sufijo de nombre (Si la jurisdicción participa en sistemas que requieren sufijo de nombre (PDPS, CDLIS, etc.), el sufijo debe recopilarse y mostrarse en el DL/ID y en el MRT). |
| [getOrganDonorIndicator()](#getOrganDonorIndicator--) | DDK, Campo que indica que el titular es donante de órganos = \\u201c1\\u201d, DL/ID, F1N |
| [getPlaceOfBirth()](#getPlaceOfBirth--) | DCI, País y municipio y/o estado/provincia, DL/ID, V33A |
| [getRaceEthnicity()](#getRaceEthnicity--) | DCL, Códigos de raza o etnia del titular, según lo definido en AAMVA D20, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getRestrictionCodeDescription--) | DCR, Texto que describe el/los código(s) de restricción específico(s) de la jurisdicción que limitan los privilegios de conducción, DL, V50ANS |
| [getStandardEndorsementCode()](#getStandardEndorsementCode--) | DCN, Código(s) de autorización estándar para el titular. |
| [getStandardRestrictionCode()](#getStandardRestrictionCode--) | DCO, Código(s) de restricción estándar para el titular. |
| [getStandardVehClassification()](#getStandardVehClassification--) | DCM, Código(s) de clasificación de vehículo estándar para el titular. |
| [getUnder18Until()](#getUnder18Until--) | DDH, Fecha en la que el titular cumple 18 años. |
| [getUnder19Until()](#getUnder19Until--) | DDI, Fecha en la que el titular cumple 19 años. |
| [getUnder21Until()](#getUnder21Until--) | DDJ, Fecha en la que el titular cumple 21 años. |
| [getVehClassDescription()](#getVehClassDescription--) | DCP, Texto que explica el/los código(s) específico(s) de la jurisdicción para las clasificaciones de vehículos que el titular está autorizado a conducir, DL, V50ANS |
| [getVeteranIndicator()](#getVeteranIndicator--) | DDL, Campo que indica que el titular es un veterano = \\u201c1\\u201d, DL/ID, F1N |
| [getWeightKilograms()](#getWeightKilograms--) | DAX, Peso del titular en kilogramos, Ej. |
| [getWeightPounds()](#getWeightPounds--) | DAW, Peso del titular en libras, Ej. |
| [getWeightRange()](#getWeightRange--) | DCE, Indica el rango de peso aproximado del titular: 0 = hasta 31 kg (hasta 70 lb), 1 = 32 \\u2013 45 kg (71 \\u2013 100 lb), 2 = 46 - 59 kg (101 \\u2013 130 lb), 3 = 60 - 70 kg (131 \\u2013 160 lb), 4 = 71 - 86 kg (161 \\u2013 190 lb), 5 = 87 - 100 kg (191 \\u2013 220 lb), 6 = 101 - 113 kg (221 \\u2013 250 lb), 7 = 114 - 127 kg (251 \\u2013 280 lb), 8 = 128 \\u2013 145 kg (281 \\u2013 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressStreet2(String value)](#setAddressStreet2-java.lang.String-) | DAH, Segunda línea de la porción de calle de la dirección del titular de la tarjeta, DL/ID, V35ANS |
| [setAliasAKAFamilyName(String value)](#setAliasAKAFamilyName-java.lang.String-) | DBN, Otro apellido por el cual se conoce al titular de la tarjeta, DL/ID, V10ANS |
| [setAliasAKAGivenName(String value)](#setAliasAKAGivenName-java.lang.String-) | DBG, Otro nombre de pila por el cual se conoce al titular de la tarjeta, DL/ID, V15ANS |
| [setAliasAKASuffixName(String value)](#setAliasAKASuffixName-java.lang.String-) | DBS, Otro sufijo por el cual se conoce al titular de la tarjeta, DL/ID, V5ANS |
| [setAuditInformation(String value)](#setAuditInformation-java.lang.String-) | DCJ, Una cadena de letras y/o números que identifica cuándo, dónde y por quién se fabricó una licencia de conducir/tarjeta de identificación. |
| [setCardRevisionDate(LocalDate value)](#setCardRevisionDate-java.time.LocalDate-) | DDB, Campo requerido por DHS que indica la fecha del cambio de versión más reciente o modificación al formato visible del DL/ID. |
| [setComplianceType(String value)](#setComplianceType-java.lang.String-) | DDA, Campo requerido por DHS que indica cumplimiento: \\u201cF\\u201d = conforme; y, \\u201cN\\u201d = no conforme, DL/ID, F1A |
| [setEndorsementCodeDescription(String value)](#setEndorsementCodeDescription-java.lang.String-) | DCQ, Texto que explica el/los código(s) específico(s) de la jurisdicción que indica(n) privilegios de conducción adicionales otorgados al titular más allá de la clase de vehículo, DL, V50ANS |
| [setHAZMATEndorsementExpDate(LocalDate value)](#setHAZMATEndorsementExpDate-java.time.LocalDate-) | DDC, Fecha en la que la autorización de materiales peligrosos otorgada por el documento deja de ser válida. |
| [setHairColor(USADriveIdHairColor value)](#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-) | DAZ, Calvo, negro, rubio, castaño, gris, rojo/marrón, arena, blanco, desconocido. |
| [setInventoryControlNumber(String value)](#setInventoryControlNumber-java.lang.String-) | DCK, Una cadena de letras y/o números que se adhiere a los materiales crudos (cartulina, laminado, etc.) utilizados en la producción de licencias de conducir y tarjetas de identificación. |
| [setLimitedDurationDocIndicator(String value)](#setLimitedDurationDocIndicator-java.lang.String-) | DDD, Campo requerido por DHS que indica que el titular tiene estatus legal temporal = \\u201c1\\u201d, DL/ID, F1N |
| [setNameSuffix(String value)](#setNameSuffix-java.lang.String-) | DCU, Sufijo de nombre (Si la jurisdicción participa en sistemas que requieren sufijo de nombre (PDPS, CDLIS, etc.), el sufijo debe recopilarse y mostrarse en el DL/ID y en el MRT). |
| [setOrganDonorIndicator(String value)](#setOrganDonorIndicator-java.lang.String-) | DDK, Campo que indica que el titular es donante de órganos = \\u201c1\\u201d, DL/ID, F1N |
| [setPlaceOfBirth(String value)](#setPlaceOfBirth-java.lang.String-) | DCI, País y municipio y/o estado/provincia, DL/ID, V33A |
| [setRaceEthnicity(String value)](#setRaceEthnicity-java.lang.String-) | DCL, Códigos de raza o etnia del titular, según lo definido en AAMVA D20, DL/ID, V3A |
| [setRestrictionCodeDescription(String value)](#setRestrictionCodeDescription-java.lang.String-) | DCR, Texto que describe el/los código(s) de restricción específico(s) de la jurisdicción que limitan los privilegios de conducción, DL, V50ANS |
| [setStandardEndorsementCode(String value)](#setStandardEndorsementCode-java.lang.String-) | DCN, Código(s) de autorización estándar para el titular. |
| [setStandardRestrictionCode(String value)](#setStandardRestrictionCode-java.lang.String-) | DCO, Código(s) de restricción estándar para el titular. |
| [setStandardVehClassification(String value)](#setStandardVehClassification-java.lang.String-) | DCM, Código(s) de clasificación de vehículo estándar para el titular. |
| [setUnder18Until(LocalDate value)](#setUnder18Until-java.time.LocalDate-) | DDH, Fecha en la que el titular cumple 18 años. |
| [setUnder19Until(LocalDate value)](#setUnder19Until-java.time.LocalDate-) | DDI, Fecha en la que el titular cumple 19 años. |
| [setUnder21Until(LocalDate value)](#setUnder21Until-java.time.LocalDate-) | DDJ, Fecha en la que el titular cumple 21 años. |
| [setVehClassDescription(String value)](#setVehClassDescription-java.lang.String-) | DCP, Texto que explica el/los código(s) específico(s) de la jurisdicción para las clasificaciones de vehículos que el titular está autorizado a conducir, DL, V50ANS |
| [setVeteranIndicator(String value)](#setVeteranIndicator-java.lang.String-) | DDL, Campo que indica que el titular es un veterano = \\u201c1\\u201d, DL/ID, F1N |
| [setWeightKilograms(int value)](#setWeightKilograms-int-) | DAX, Peso del titular en kilogramos, Ej. |
| [setWeightPounds(int value)](#setWeightPounds-int-) | DAW, Peso del titular en libras, Ej. |
| [setWeightRange(String value)](#setWeightRange-java.lang.String-) | DCE, Indica el rango de peso aproximado del titular: 0 = hasta 31 kg (hasta 70 lb), 1 = 32 \\u2013 45 kg (71 \\u2013 100 lb), 2 = 46 - 59 kg (101 \\u2013 130 lb), 3 = 60 - 70 kg (131 \\u2013 160 lb), 4 = 71 - 86 kg (161 \\u2013 190 lb), 5 = 87 - 100 kg (191 \\u2013 220 lb), 6 = 101 - 113 kg (221 \\u2013 250 lb), 7 = 114 - 127 kg (251 \\u2013 280 lb), 8 = 128 \\u2013 145 kg (281 \\u2013 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N |
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
| Parámetro | Tipo | Descripción |
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


DCJ, Una cadena de letras y/o números que identifica cuándo, dónde y por quién se fabricó una licencia de conducir/tarjeta de identificación. Si la información de auditoría no se utiliza en la tarjeta o en el MRT, debe incluirse en el registro del conductor, DL/ID, V25ANS

**Returns:**
java.lang.String
### getCardRevisionDate() {#getCardRevisionDate--}
```
public final LocalDate getCardRevisionDate()
```


DDB, campo requerido por DHS que indica la fecha del cambio de versión más reciente o la modificación del formato visible del DL/ID. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N

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


DDA, Campo requerido por DHS que indica cumplimiento: \\u201cF\\u201d = conforme; y, \\u201cN\\u201d = no conforme, DL/ID, F1A

**Returns:**
java.lang.String
### getEndorsementCodeDescription() {#getEndorsementCodeDescription--}
```
public final String getEndorsementCodeDescription()
```


DCQ, Texto que explica el/los código(s) específico(s) de la jurisdicción que indica(n) privilegios de conducción adicionales otorgados al titular más allá de la clase de vehículo, DL, V50ANS

**Returns:**
java.lang.String
### getHAZMATEndorsementExpDate() {#getHAZMATEndorsementExpDate--}
```
public final LocalDate getHAZMATEndorsementExpDate()
```


DDC, fecha en la que la autorización de material peligroso otorgada por el documento deja de ser válida. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL, F8N

**Returns:**
java.time.LocalDate
### getHairColor() {#getHairColor--}
```
public final USADriveIdHairColor getHairColor()
```


DAZ, Calvo, negro, rubio, castaño, gris, rojo/castaño rojizo, arena, blanco, desconocido. Si la jurisdicción emisora desea abreviar los colores, se deben usar los códigos de tres caracteres provistos en AAMVA D20, DL/ID, V12A

**Returns:**
[USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor)
### getInventoryControlNumber() {#getInventoryControlNumber--}
```
public final String getInventoryControlNumber()
```


DCK, una cadena de letras y/o números que se adhiere a las materias primas (papel base, laminado, etc.) utilizadas en la producción de licencias de conducir y tarjetas de identificación. (campo recomendado por DHS), DL/ID, V25ANS

**Returns:**
java.lang.String
### getLimitedDurationDocIndicator() {#getLimitedDurationDocIndicator--}
```
public final String getLimitedDurationDocIndicator()
```


DDD, Campo requerido por DHS que indica que el titular tiene estatus legal temporal = \\u201c1\\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getNameSuffix() {#getNameSuffix--}
```
public final String getNameSuffix()
```


DCU, Sufijo de nombre (Si la jurisdicción participa en sistemas que requieren sufijo de nombre (PDPS, CDLIS, etc.), el sufijo debe recopilarse y mostrarse en el DL/ID y en el MRT). JR (Junior), SR (Senior), 1ST o I (Primero), hasta 9TH o IX (Noveno), DL/ID, V5ANS

**Returns:**
java.lang.String
### getOrganDonorIndicator() {#getOrganDonorIndicator--}
```
public final String getOrganDonorIndicator()
```


DDK, Campo que indica que el titular es donante de órganos = \\u201c1\\u201d, DL/ID, F1N

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


DCL, Códigos de raza o etnia del titular, según lo definido en AAMVA D20, DL/ID, V3A

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


DCN, código(s) de autorización estándar para el titular de la tarjeta. Ver códigos en D20. Este elemento de datos es un marcador de posición para futuros esfuerzos de estandarizar los códigos de autorización, DL, F5AN

**Returns:**
java.lang.String
### getStandardRestrictionCode() {#getStandardRestrictionCode--}
```
public final String getStandardRestrictionCode()
```


DCO, código(s) de restricción estándar para el titular de la tarjeta. Ver códigos en D20. Este elemento de datos es un marcador de posición para futuros esfuerzos de estandarizar los códigos de restricción, DL, F12AN

**Returns:**
java.lang.String
### getStandardVehClassification() {#getStandardVehClassification--}
```
public final String getStandardVehClassification()
```


DCM, código(s) de clasificación de vehículos estándar para el titular de la tarjeta. Este elemento de datos es un marcador de posición para futuros esfuerzos de estandarizar las clasificaciones de vehículos, DL, F4AN

**Returns:**
java.lang.String
### getUnder18Until() {#getUnder18Until--}
```
public final LocalDate getUnder18Until()
```


DDH, fecha en la que el titular de la tarjeta cumple 18 años. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getUnder19Until() {#getUnder19Until--}
```
public final LocalDate getUnder19Until()
```


DDI, fecha en la que el titular de la tarjeta cumple 19 años. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getUnder21Until() {#getUnder21Until--}
```
public final LocalDate getUnder21Until()
```


DDJ, fecha en la que el titular de la tarjeta cumple 21 años. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getVehClassDescription() {#getVehClassDescription--}
```
public final String getVehClassDescription()
```


DCP, Texto que explica el/los código(s) específico(s) de la jurisdicción para las clasificaciones de vehículos que el titular está autorizado a conducir, DL, V50ANS

**Returns:**
java.lang.String
### getVeteranIndicator() {#getVeteranIndicator--}
```
public final String getVeteranIndicator()
```


DDL, Campo que indica que el titular es un veterano = \\u201c1\\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getWeightKilograms() {#getWeightKilograms--}
```
public final int getWeightKilograms()
```


DAX, peso del titular de la tarjeta en kilogramos, Ej. 84 kg = \\u201c084\\u201d, DL/ID, F3N

**Returns:**
int
### getWeightPounds() {#getWeightPounds--}
```
public final int getWeightPounds()
```


DAW, peso del titular de la tarjeta en libras, Ej. 185 lb = \\u201c185\\u201d, DL/ID, F3N

**Returns:**
int
### getWeightRange() {#getWeightRange--}
```
public final String getWeightRange()
```


DCE, Indica el rango de peso aproximado del titular: 0 = hasta 31 kg (hasta 70 lb), 1 = 32 \\u2013 45 kg (71 \\u2013 100 lb), 2 = 46 - 59 kg (101 \\u2013 130 lb), 3 = 60 - 70 kg (131 \\u2013 160 lb), 4 = 71 - 86 kg (161 \\u2013 190 lb), 5 = 87 - 100 kg (191 \\u2013 220 lb), 6 = 101 - 113 kg (221 \\u2013 250 lb), 7 = 114 - 127 kg (251 \\u2013 280 lb), 8 = 128 \\u2013 145 kg (281 \\u2013 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setAliasAKAFamilyName(String value) {#setAliasAKAFamilyName-java.lang.String-}
```
public final void setAliasAKAFamilyName(String value)
```


DBN, Otro apellido por el cual se conoce al titular de la tarjeta, DL/ID, V10ANS

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setAliasAKAGivenName(String value) {#setAliasAKAGivenName-java.lang.String-}
```
public final void setAliasAKAGivenName(String value)
```


DBG, Otro nombre de pila por el cual se conoce al titular de la tarjeta, DL/ID, V15ANS

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setAliasAKASuffixName(String value) {#setAliasAKASuffixName-java.lang.String-}
```
public final void setAliasAKASuffixName(String value)
```


DBS, Otro sufijo por el cual se conoce al titular de la tarjeta, DL/ID, V5ANS

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setAuditInformation(String value) {#setAuditInformation-java.lang.String-}
```
public final void setAuditInformation(String value)
```


DCJ, Una cadena de letras y/o números que identifica cuándo, dónde y por quién se fabricó una licencia de conducir/tarjeta de identificación. Si la información de auditoría no se utiliza en la tarjeta o en el MRT, debe incluirse en el registro del conductor, DL/ID, V25ANS

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setCardRevisionDate(LocalDate value) {#setCardRevisionDate-java.time.LocalDate-}
```
public final void setCardRevisionDate(LocalDate value)
```


DDB, campo requerido por DHS que indica la fecha del cambio de versión más reciente o la modificación del formato visible del DL/ID. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.time.LocalDate |  |

### setComplianceType(String value) {#setComplianceType-java.lang.String-}
```
public final void setComplianceType(String value)
```


DDA, Campo requerido por DHS que indica cumplimiento: \\u201cF\\u201d = conforme; y, \\u201cN\\u201d = no conforme, DL/ID, F1A

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setEndorsementCodeDescription(String value) {#setEndorsementCodeDescription-java.lang.String-}
```
public final void setEndorsementCodeDescription(String value)
```


DCQ, Texto que explica el/los código(s) específico(s) de la jurisdicción que indica(n) privilegios de conducción adicionales otorgados al titular más allá de la clase de vehículo, DL, V50ANS

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setHAZMATEndorsementExpDate(LocalDate value) {#setHAZMATEndorsementExpDate-java.time.LocalDate-}
```
public final void setHAZMATEndorsementExpDate(LocalDate value)
```


DDC, fecha en la que la autorización de material peligroso otorgada por el documento deja de ser válida. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL, F8N

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.time.LocalDate |  |

### setHairColor(USADriveIdHairColor value) {#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-}
```
public final void setHairColor(USADriveIdHairColor value)
```


DAZ, Calvo, negro, rubio, castaño, gris, rojo/castaño rojizo, arena, blanco, desconocido. Si la jurisdicción emisora desea abreviar los colores, se deben usar los códigos de tres caracteres provistos en AAMVA D20, DL/ID, V12A

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor) |  |

### setInventoryControlNumber(String value) {#setInventoryControlNumber-java.lang.String-}
```
public final void setInventoryControlNumber(String value)
```


DCK, una cadena de letras y/o números que se adhiere a las materias primas (papel base, laminado, etc.) utilizadas en la producción de licencias de conducir y tarjetas de identificación. (campo recomendado por DHS), DL/ID, V25ANS

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setLimitedDurationDocIndicator(String value) {#setLimitedDurationDocIndicator-java.lang.String-}
```
public final void setLimitedDurationDocIndicator(String value)
```


DDD, Campo requerido por DHS que indica que el titular tiene estatus legal temporal = \\u201c1\\u201d, DL/ID, F1N

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setNameSuffix(String value) {#setNameSuffix-java.lang.String-}
```
public final void setNameSuffix(String value)
```


DCU, Sufijo de nombre (Si la jurisdicción participa en sistemas que requieren sufijo de nombre (PDPS, CDLIS, etc.), el sufijo debe recopilarse y mostrarse en el DL/ID y en el MRT). JR (Junior), SR (Senior), 1ST o I (Primero), hasta 9TH o IX (Noveno), DL/ID, V5ANS

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setOrganDonorIndicator(String value) {#setOrganDonorIndicator-java.lang.String-}
```
public final void setOrganDonorIndicator(String value)
```


DDK, Campo que indica que el titular es donante de órganos = \\u201c1\\u201d, DL/ID, F1N

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setPlaceOfBirth(String value) {#setPlaceOfBirth-java.lang.String-}
```
public final void setPlaceOfBirth(String value)
```


DCI, País y municipio y/o estado/provincia, DL/ID, V33A

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setRaceEthnicity(String value) {#setRaceEthnicity-java.lang.String-}
```
public final void setRaceEthnicity(String value)
```


DCL, Códigos de raza o etnia del titular, según lo definido en AAMVA D20, DL/ID, V3A

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setRestrictionCodeDescription(String value) {#setRestrictionCodeDescription-java.lang.String-}
```
public final void setRestrictionCodeDescription(String value)
```


DCR, Texto que describe el/los código(s) de restricción específico(s) de la jurisdicción que limitan los privilegios de conducción, DL, V50ANS

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setStandardEndorsementCode(String value) {#setStandardEndorsementCode-java.lang.String-}
```
public final void setStandardEndorsementCode(String value)
```


DCN, código(s) de autorización estándar para el titular de la tarjeta. Ver códigos en D20. Este elemento de datos es un marcador de posición para futuros esfuerzos de estandarizar los códigos de autorización, DL, F5AN

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setStandardRestrictionCode(String value) {#setStandardRestrictionCode-java.lang.String-}
```
public final void setStandardRestrictionCode(String value)
```


DCO, código(s) de restricción estándar para el titular de la tarjeta. Ver códigos en D20. Este elemento de datos es un marcador de posición para futuros esfuerzos de estandarizar los códigos de restricción, DL, F12AN

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setStandardVehClassification(String value) {#setStandardVehClassification-java.lang.String-}
```
public final void setStandardVehClassification(String value)
```


DCM, código(s) de clasificación de vehículos estándar para el titular de la tarjeta. Este elemento de datos es un marcador de posición para futuros esfuerzos de estandarizar las clasificaciones de vehículos, DL, F4AN

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setUnder18Until(LocalDate value) {#setUnder18Until-java.time.LocalDate-}
```
public final void setUnder18Until(LocalDate value)
```


DDH, fecha en la que el titular de la tarjeta cumple 18 años. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.time.LocalDate |  |

### setUnder19Until(LocalDate value) {#setUnder19Until-java.time.LocalDate-}
```
public final void setUnder19Until(LocalDate value)
```


DDI, fecha en la que el titular de la tarjeta cumple 19 años. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.time.LocalDate |  |

### setUnder21Until(LocalDate value) {#setUnder21Until-java.time.LocalDate-}
```
public final void setUnder21Until(LocalDate value)
```


DDJ, fecha en la que el titular de la tarjeta cumple 21 años. (MMDDCCYY para EE. UU., CCYYMMDD para Canadá), DL/ID, F8N

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.time.LocalDate |  |

### setVehClassDescription(String value) {#setVehClassDescription-java.lang.String-}
```
public final void setVehClassDescription(String value)
```


DCP, Texto que explica el/los código(s) específico(s) de la jurisdicción para las clasificaciones de vehículos que el titular está autorizado a conducir, DL, V50ANS

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setVeteranIndicator(String value) {#setVeteranIndicator-java.lang.String-}
```
public final void setVeteranIndicator(String value)
```


DDL, Campo que indica que el titular es un veterano = \\u201c1\\u201d, DL/ID, F1N

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setWeightKilograms(int value) {#setWeightKilograms-int-}
```
public final void setWeightKilograms(int value)
```


DAX, peso del titular de la tarjeta en kilogramos, Ej. 84 kg = \\u201c084\\u201d, DL/ID, F3N

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setWeightPounds(int value) {#setWeightPounds-int-}
```
public final void setWeightPounds(int value)
```


DAW, peso del titular de la tarjeta en libras, Ej. 185 lb = \\u201c185\\u201d, DL/ID, F3N

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setWeightRange(String value) {#setWeightRange-java.lang.String-}
```
public final void setWeightRange(String value)
```


DCE, Indica el rango de peso aproximado del titular: 0 = hasta 31 kg (hasta 70 lb), 1 = 32 \\u2013 45 kg (71 \\u2013 100 lb), 2 = 46 - 59 kg (101 \\u2013 130 lb), 3 = 60 - 70 kg (131 \\u2013 160 lb), 4 = 71 - 86 kg (161 \\u2013 190 lb), 5 = 87 - 100 kg (191 \\u2013 220 lb), 6 = 101 - 113 kg (221 \\u2013 250 lb), 7 = 114 - 127 kg (251 \\u2013 280 lb), 8 = 128 \\u2013 145 kg (281 \\u2013 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N

**Parameters:**
| Parámetro | Tipo | Descripción |
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
public final native void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

