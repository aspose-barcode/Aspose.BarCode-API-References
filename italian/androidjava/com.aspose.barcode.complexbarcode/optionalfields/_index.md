---
title: USADriveIdCodetext.OptionalFields
second_title: Aspose.BarCode per Android via Java API Reference
description: Campi opzionali degli elementi della carta
type: docs
weight: 11
url: /it/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.OptionalFields
```

Elementi opzionali (campi) della carta
## Constructors

| Constructor | Descrizione |
| --- | --- |
| [OptionalFields()](#OptionalFields--) |  |
## Methods

| Method | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressStreet2()](#getAddressStreet2--) | DAH, Seconda riga della parte via dell'indirizzo del titolare della carta, DL/ID, V35ANS |
| [getAliasAKAFamilyName()](#getAliasAKAFamilyName--) | DBN, Altro cognome con cui è noto il titolare della carta, DL/ID, V10ANS |
| [getAliasAKAGivenName()](#getAliasAKAGivenName--) | DBG, Altro nome proprio con cui è noto il titolare della carta, DL/ID, V15ANS |
| [getAliasAKASuffixName()](#getAliasAKASuffixName--) | DBS, Altro suffisso con cui è noto il titolare della carta, DL/ID, V5ANS |
| [getAuditInformation()](#getAuditInformation--) | DCJ, Una stringa di lettere e/o numeri che identifica quando, dove e da chi è stata prodotta una patente di guida/carta d'identità. |
| [getCardRevisionDate()](#getCardRevisionDate--) | DDB, Campo obbligatorio DHS che indica la data dell'ultima modifica di versione o modifica del formato visibile del DL/ID. |
| [getClass()](#getClass--) |  |
| [getComplianceType()](#getComplianceType--) | DDA, Campo obbligatorio DHS che indica la conformità: \u201cF\u201d = conforme; e, \u201cN\u201d = non conforme, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getEndorsementCodeDescription--) | DCQ, Testo che spiega i codici specifici della giurisdizione che indicano privilegi di guida aggiuntivi concessi al titolare della carta oltre la classe del veicolo, DL, V50ANS |
| [getHAZMATEndorsementExpDate()](#getHAZMATEndorsementExpDate--) | DDC, Data in cui l'endoso per materiale pericoloso concesso dal documento non è più valido. |
| [getHairColor()](#getHairColor--) | DAZ, Calvo, nero, biondo, castano, grigio, rosso/marrone, sabbioso, bianco, sconosciuto. |
| [getInventoryControlNumber()](#getInventoryControlNumber--) | DCK, Una stringa di lettere e/o numeri che è applicata alle materie prime (carta, laminato, ecc.) utilizzate nella produzione di patenti di guida e carte d'identità. |
| [getLimitedDurationDocIndicator()](#getLimitedDurationDocIndicator--) | DDD, Campo obbligatorio DHS che indica che il titolare della carta ha uno stato legale temporaneo = \u201c1\u201d, DL/ID, F1N |
| [getNameSuffix()](#getNameSuffix--) | DCU, Suffisso del nome (Se la giurisdizione partecipa a sistemi che richiedono il suffisso del nome (PDPS, CDLIS, ecc.), il suffisso deve essere raccolto e visualizzato sul DL/ID e nel MRT). |
| [getOrganDonorIndicator()](#getOrganDonorIndicator--) | DDK, Campo che indica che il titolare della carta è un donatore di organi = \u201c1\u201d, DL/ID, F1N |
| [getPlaceOfBirth()](#getPlaceOfBirth--) | DCI, Paese e comune e/o stato/provincia, DL/ID, V33A |
| [getRaceEthnicity()](#getRaceEthnicity--) | DCL, Codici per razza o etnia del titolare della carta, come definiti in AAMVA D20, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getRestrictionCodeDescription--) | DCR, Testo che descrive i codici di restrizione specifici della giurisdizione che limitano i privilegi di guida, DL, V50ANS |
| [getStandardEndorsementCode()](#getStandardEndorsementCode--) | DCN, Codici di endoso standard per il titolare della carta. |
| [getStandardRestrictionCode()](#getStandardRestrictionCode--) | DCO, Codici di restrizione standard per il titolare della carta. |
| [getStandardVehClassification()](#getStandardVehClassification--) | DCM, Codici di classificazione del veicolo standard per il titolare della carta. |
| [getUnder18Until()](#getUnder18Until--) | DDH, Data in cui il titolare della carta compie 18 anni. |
| [getUnder19Until()](#getUnder19Until--) | DDI, Data in cui il titolare della carta compie 19 anni. |
| [getUnder21Until()](#getUnder21Until--) | DDJ, Data in cui il titolare della carta compie 21 anni. |
| [getVehClassDescription()](#getVehClassDescription--) | DCP, Testo che spiega i codici specifici della giurisdizione per le classificazioni dei veicoli che il titolare è autorizzato a guidare, DL, V50ANS |
| [getVeteranIndicator()](#getVeteranIndicator--) | DDL, Campo che indica che il titolare è un veterano = \\u201c1\\u201d, DL/ID, F1N |
| [getWeightKilograms()](#getWeightKilograms--) | DAX, Peso del titolare in chilogrammi, Es. |
| [getWeightPounds()](#getWeightPounds--) | DAW, Peso del titolare in libbre, Es. |
| [getWeightRange()](#getWeightRange--) | DCE, Indica la fascia di peso approssimativa del titolare: 0 = fino a 31 kg (fino a 70 libbre), 1 = 32 \\u2013 45 kg (71 \\u2013 100 libbre), 2 = 46 - 59 kg (101 \\u2013 130 libbre), 3 = 60 - 70 kg (131 \\u2013 160 libbre), 4 = 71 - 86 kg (161 \\u2013 190 libbre), 5 = 87 - 100 kg (191 \\u2013 220 libbre), 6 = 101 - 113 kg (221 \\u2013 250 libbre), 7 = 114 - 127 kg (251 \\u2013 280 libbre), 8 = 128 \\u2013 145 kg (281 \\u2013 320 libbre), 9 = 146+ kg (321+ libbre), DL/ID, F1N |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressStreet2(String value)](#setAddressStreet2-java.lang.String-) | DAH, Seconda riga della parte via dell'indirizzo del titolare della carta, DL/ID, V35ANS |
| [setAliasAKAFamilyName(String value)](#setAliasAKAFamilyName-java.lang.String-) | DBN, Altro cognome con cui è noto il titolare della carta, DL/ID, V10ANS |
| [setAliasAKAGivenName(String value)](#setAliasAKAGivenName-java.lang.String-) | DBG, Altro nome proprio con cui è noto il titolare della carta, DL/ID, V15ANS |
| [setAliasAKASuffixName(String value)](#setAliasAKASuffixName-java.lang.String-) | DBS, Altro suffisso con cui è noto il titolare della carta, DL/ID, V5ANS |
| [setAuditInformation(String value)](#setAuditInformation-java.lang.String-) | DCJ, Una stringa di lettere e/o numeri che identifica quando, dove e da chi è stata prodotta una patente di guida/carta d'identità. |
| [setCardRevisionDate(LocalDate value)](#setCardRevisionDate-java.time.LocalDate-) | DDB, Campo obbligatorio DHS che indica la data dell'ultima modifica di versione o modifica del formato visibile del DL/ID. |
| [setComplianceType(String value)](#setComplianceType-java.lang.String-) | DDA, Campo obbligatorio DHS che indica la conformità: \u201cF\u201d = conforme; e, \u201cN\u201d = non conforme, DL/ID, F1A |
| [setEndorsementCodeDescription(String value)](#setEndorsementCodeDescription-java.lang.String-) | DCQ, Testo che spiega i codici specifici della giurisdizione che indicano privilegi di guida aggiuntivi concessi al titolare della carta oltre la classe del veicolo, DL, V50ANS |
| [setHairColor(USADriveIdHairColor value)](#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-) | DAZ, Calvo, nero, biondo, castano, grigio, rosso/marrone, sabbioso, bianco, sconosciuto. |
| [setInventoryControlNumber(String value)](#setInventoryControlNumber-java.lang.String-) | DCK, Una stringa di lettere e/o numeri che è applicata alle materie prime (carta, laminato, ecc.) utilizzate nella produzione di patenti di guida e carte d'identità. |
| [setLimitedDurationDocIndicator(String value)](#setLimitedDurationDocIndicator-java.lang.String-) | DDD, Campo obbligatorio DHS che indica che il titolare della carta ha uno stato legale temporaneo = \u201c1\u201d, DL/ID, F1N |
| [setNameSuffix(String value)](#setNameSuffix-java.lang.String-) | DCU, Suffisso del nome (Se la giurisdizione partecipa a sistemi che richiedono il suffisso del nome (PDPS, CDLIS, ecc.), il suffisso deve essere raccolto e visualizzato sul DL/ID e nel MRT). |
| [setOrganDonorIndicator(String value)](#setOrganDonorIndicator-java.lang.String-) | DDK, Campo che indica che il titolare della carta è un donatore di organi = \u201c1\u201d, DL/ID, F1N |
| [setPlaceOfBirth(String value)](#setPlaceOfBirth-java.lang.String-) | DCI, Paese e comune e/o stato/provincia, DL/ID, V33A |
| [setRaceEthnicity(String value)](#setRaceEthnicity-java.lang.String-) | DCL, Codici per razza o etnia del titolare della carta, come definiti in AAMVA D20, DL/ID, V3A |
| [setRestrictionCodeDescription(String value)](#setRestrictionCodeDescription-java.lang.String-) | DCR, Testo che descrive i codici di restrizione specifici della giurisdizione che limitano i privilegi di guida, DL, V50ANS |
| [setStandardEndorsementCode(String value)](#setStandardEndorsementCode-java.lang.String-) | DCN, Codici di endoso standard per il titolare della carta. |
| [setStandardRestrictionCode(String value)](#setStandardRestrictionCode-java.lang.String-) | DCO, Codici di restrizione standard per il titolare della carta. |
| [setStandardVehClassification(String value)](#setStandardVehClassification-java.lang.String-) | DCM, Codici di classificazione del veicolo standard per il titolare della carta. |
| [setUnder18Until(LocalDate value)](#setUnder18Until-java.time.LocalDate-) | DDH, Data in cui il titolare della carta compie 18 anni. |
| [setUnder19Until(LocalDate value)](#setUnder19Until-java.time.LocalDate-) | DDI, Data in cui il titolare della carta compie 19 anni. |
| [setUnder21Until(LocalDate value)](#setUnder21Until-java.time.LocalDate-) | DDJ, Data in cui il titolare della carta compie 21 anni. |
| [setVehClassDescription(String value)](#setVehClassDescription-java.lang.String-) | DCP, Testo che spiega i codici specifici della giurisdizione per le classificazioni dei veicoli che il titolare è autorizzato a guidare, DL, V50ANS |
| [setVeteranIndicator(String value)](#setVeteranIndicator-java.lang.String-) | DDL, Campo che indica che il titolare è un veterano = \\u201c1\\u201d, DL/ID, F1N |
| [setWeightKilograms(int value)](#setWeightKilograms-int-) | DAX, Peso del titolare in chilogrammi, Es. |
| [setWeightPounds(int value)](#setWeightPounds-int-) | DAW, Peso del titolare in libbre, Es. |
| [setWeightRange(String value)](#setWeightRange-java.lang.String-) | DCE, Indica la fascia di peso approssimativa del titolare: 0 = fino a 31 kg (fino a 70 libbre), 1 = 32 \\u2013 45 kg (71 \\u2013 100 libbre), 2 = 46 - 59 kg (101 \\u2013 130 libbre), 3 = 60 - 70 kg (131 \\u2013 160 libbre), 4 = 71 - 86 kg (161 \\u2013 190 libbre), 5 = 87 - 100 kg (191 \\u2013 220 libbre), 6 = 101 - 113 kg (221 \\u2013 250 libbre), 7 = 114 - 127 kg (251 \\u2013 280 libbre), 8 = 128 \\u2013 145 kg (281 \\u2013 320 libbre), 9 = 146+ kg (321+ libbre), DL/ID, F1N |
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
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAddressStreet2() {#getAddressStreet2--}
```
public final String getAddressStreet2()
```


DAH, Seconda riga della parte via dell'indirizzo del titolare della carta, DL/ID, V35ANS

**Returns:**
java.lang.String
### getAliasAKAFamilyName() {#getAliasAKAFamilyName--}
```
public final String getAliasAKAFamilyName()
```


DBN, Altro cognome con cui è noto il titolare della carta, DL/ID, V10ANS

**Returns:**
java.lang.String
### getAliasAKAGivenName() {#getAliasAKAGivenName--}
```
public final String getAliasAKAGivenName()
```


DBG, Altro nome proprio con cui è noto il titolare della carta, DL/ID, V15ANS

**Returns:**
java.lang.String
### getAliasAKASuffixName() {#getAliasAKASuffixName--}
```
public final String getAliasAKASuffixName()
```


DBS, Altro suffisso con cui è noto il titolare della carta, DL/ID, V5ANS

**Returns:**
java.lang.String
### getAuditInformation() {#getAuditInformation--}
```
public final String getAuditInformation()
```


DCJ, Una stringa di lettere e/o numeri che identifica quando, dove e da chi è stata prodotta una patente di guida/carta d'identità. Se le informazioni di audit non sono utilizzate sulla carta o sul MRT, devono essere incluse nel record del conducente, DL/ID, V25ANS

**Returns:**
java.lang.String
### getCardRevisionDate() {#getCardRevisionDate--}
```
public final LocalDate getCardRevisionDate()
```


DDB, Campo richiesto da DHS che indica la data dell'ultima modifica o versione del formato visibile della DL/ID. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL/ID, F8N

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


DDA, Campo obbligatorio DHS che indica la conformità: \u201cF\u201d = conforme; e, \u201cN\u201d = non conforme, DL/ID, F1A

**Returns:**
java.lang.String
### getEndorsementCodeDescription() {#getEndorsementCodeDescription--}
```
public final String getEndorsementCodeDescription()
```


DCQ, Testo che spiega i codici specifici della giurisdizione che indicano privilegi di guida aggiuntivi concessi al titolare della carta oltre la classe del veicolo, DL, V50ANS

**Returns:**
java.lang.String
### getHAZMATEndorsementExpDate() {#getHAZMATEndorsementExpDate--}
```
public final LocalDate getHAZMATEndorsementExpDate()
```


DDC, Data in cui l'endoso per materiale pericoloso concesso dal documento non è più valido. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL, F8N

**Returns:**
java.time.LocalDate
### getHairColor() {#getHairColor--}
```
public final USADriveIdHairColor getHairColor()
```


DAZ, Calvo, nero, biondo, castano, grigio, rosso/marrone, sabbia, bianco, sconosciuto. Se la giurisdizione emittente desidera abbreviare i colori, devono essere usati i codici a tre caratteri forniti in AAMVA D20, DL/ID, V12A

**Returns:**
[USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor)
### getInventoryControlNumber() {#getInventoryControlNumber--}
```
public final String getInventoryControlNumber()
```


DCK, Una stringa di lettere e/o numeri che viene applicata alle materie prime (carta, laminato, ecc.) utilizzate nella produzione di patenti di guida e carte d'identità. (campo consigliato da DHS), DL/ID, V25ANS

**Returns:**
java.lang.String
### getLimitedDurationDocIndicator() {#getLimitedDurationDocIndicator--}
```
public final String getLimitedDurationDocIndicator()
```


DDD, Campo obbligatorio DHS che indica che il titolare della carta ha uno stato legale temporaneo = \u201c1\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getNameSuffix() {#getNameSuffix--}
```
public final String getNameSuffix()
```


DCU, Suffisso del nome (Se la giurisdizione partecipa a sistemi che richiedono il suffisso del nome (PDPS, CDLIS, ecc.), il suffisso deve essere raccolto e visualizzato sulla DL/ID e nel MRT). JR (Junior), SR (Senior), 1ST o I (Primo), fino a 9TH o IX (Nono), DL/ID, V5ANS

**Returns:**
java.lang.String
### getOrganDonorIndicator() {#getOrganDonorIndicator--}
```
public final String getOrganDonorIndicator()
```


DDK, Campo che indica che il titolare della carta è un donatore di organi = \u201c1\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getPlaceOfBirth() {#getPlaceOfBirth--}
```
public final String getPlaceOfBirth()
```


DCI, Paese e comune e/o stato/provincia, DL/ID, V33A

**Returns:**
java.lang.String
### getRaceEthnicity() {#getRaceEthnicity--}
```
public final String getRaceEthnicity()
```


DCL, Codici per razza o etnia del titolare della carta, come definiti in AAMVA D20, DL/ID, V3A

**Returns:**
java.lang.String
### getRestrictionCodeDescription() {#getRestrictionCodeDescription--}
```
public final String getRestrictionCodeDescription()
```


DCR, Testo che descrive i codici di restrizione specifici della giurisdizione che limitano i privilegi di guida, DL, V50ANS

**Returns:**
java.lang.String
### getStandardEndorsementCode() {#getStandardEndorsementCode--}
```
public final String getStandardEndorsementCode()
```


DCN, Codice(i) di endoso standard per il titolare. Vedi i codici in D20. Questo elemento dati è un segnaposto per futuri sforzi di standardizzazione dei codici di endoso, DL, F5AN

**Returns:**
java.lang.String
### getStandardRestrictionCode() {#getStandardRestrictionCode--}
```
public final String getStandardRestrictionCode()
```


DCO, Codice(i) di restrizione standard per il titolare. Vedi i codici in D20. Questo elemento dati è un segnaposto per futuri sforzi di standardizzazione dei codici di restrizione, DL, F12AN

**Returns:**
java.lang.String
### getStandardVehClassification() {#getStandardVehClassification--}
```
public final String getStandardVehClassification()
```


DCM, Codice(i) di classificazione veicolo standard per il titolare. Questo elemento dati è un segnaposto per futuri sforzi di standardizzazione delle classificazioni dei veicoli, DL, F4AN

**Returns:**
java.lang.String
### getUnder18Until() {#getUnder18Until--}
```
public final LocalDate getUnder18Until()
```


DDH, Data in cui il titolare compie 18 anni. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getUnder19Until() {#getUnder19Until--}
```
public final LocalDate getUnder19Until()
```


DDI, Data in cui il titolare compie 19 anni. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getUnder21Until() {#getUnder21Until--}
```
public final LocalDate getUnder21Until()
```


DDJ, Data in cui il titolare compie 21 anni. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getVehClassDescription() {#getVehClassDescription--}
```
public final String getVehClassDescription()
```


DCP, Testo che spiega i codici specifici della giurisdizione per le classificazioni dei veicoli che il titolare è autorizzato a guidare, DL, V50ANS

**Returns:**
java.lang.String
### getVeteranIndicator() {#getVeteranIndicator--}
```
public final String getVeteranIndicator()
```


DDL, Campo che indica che il titolare è un veterano = \\u201c1\\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getWeightKilograms() {#getWeightKilograms--}
```
public final int getWeightKilograms()
```


DAX, Peso del titolare in chilogrammi, Es. 84 kg = \\u201c084\\u201d, DL/ID, F3N

**Returns:**
int
### getWeightPounds() {#getWeightPounds--}
```
public final int getWeightPounds()
```


DAW, Peso del titolare in libbre, Es. 185 lb = \\u201c185\\u201d, DL/ID, F3N

**Returns:**
int
### getWeightRange() {#getWeightRange--}
```
public final String getWeightRange()
```


DCE, Indica la fascia di peso approssimativa del titolare: 0 = fino a 31 kg (fino a 70 libbre), 1 = 32 \\u2013 45 kg (71 \\u2013 100 libbre), 2 = 46 - 59 kg (101 \\u2013 130 libbre), 3 = 60 - 70 kg (131 \\u2013 160 libbre), 4 = 71 - 86 kg (161 \\u2013 190 libbre), 5 = 87 - 100 kg (191 \\u2013 220 libbre), 6 = 101 - 113 kg (221 \\u2013 250 libbre), 7 = 114 - 127 kg (251 \\u2013 280 libbre), 8 = 128 \\u2013 145 kg (281 \\u2013 320 libbre), 9 = 146+ kg (321+ libbre), DL/ID, F1N

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


DAH, Seconda riga della parte via dell'indirizzo del titolare della carta, DL/ID, V35ANS

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setAliasAKAFamilyName(String value) {#setAliasAKAFamilyName-java.lang.String-}
```
public final void setAliasAKAFamilyName(String value)
```


DBN, Altro cognome con cui è noto il titolare della carta, DL/ID, V10ANS

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setAliasAKAGivenName(String value) {#setAliasAKAGivenName-java.lang.String-}
```
public final void setAliasAKAGivenName(String value)
```


DBG, Altro nome proprio con cui è noto il titolare della carta, DL/ID, V15ANS

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setAliasAKASuffixName(String value) {#setAliasAKASuffixName-java.lang.String-}
```
public final void setAliasAKASuffixName(String value)
```


DBS, Altro suffisso con cui è noto il titolare della carta, DL/ID, V5ANS

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setAuditInformation(String value) {#setAuditInformation-java.lang.String-}
```
public final void setAuditInformation(String value)
```


DCJ, Una stringa di lettere e/o numeri che identifica quando, dove e da chi è stata prodotta una patente di guida/carta d'identità. Se le informazioni di audit non sono utilizzate sulla carta o sul MRT, devono essere incluse nel record del conducente, DL/ID, V25ANS

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setCardRevisionDate(LocalDate value) {#setCardRevisionDate-java.time.LocalDate-}
```
public final void setCardRevisionDate(LocalDate value)
```


DDB, Campo richiesto da DHS che indica la data dell'ultima modifica o versione del formato visibile della DL/ID. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL/ID, F8N

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.time.LocalDate |  |

### setComplianceType(String value) {#setComplianceType-java.lang.String-}
```
public final void setComplianceType(String value)
```


DDA, Campo obbligatorio DHS che indica la conformità: \u201cF\u201d = conforme; e, \u201cN\u201d = non conforme, DL/ID, F1A

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setEndorsementCodeDescription(String value) {#setEndorsementCodeDescription-java.lang.String-}
```
public final void setEndorsementCodeDescription(String value)
```


DCQ, Testo che spiega i codici specifici della giurisdizione che indicano privilegi di guida aggiuntivi concessi al titolare della carta oltre la classe del veicolo, DL, V50ANS

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setHairColor(USADriveIdHairColor value) {#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-}
```
public final void setHairColor(USADriveIdHairColor value)
```


DAZ, Calvo, nero, biondo, castano, grigio, rosso/marrone, sabbia, bianco, sconosciuto. Se la giurisdizione emittente desidera abbreviare i colori, devono essere usati i codici a tre caratteri forniti in AAMVA D20, DL/ID, V12A

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor) |  |

### setInventoryControlNumber(String value) {#setInventoryControlNumber-java.lang.String-}
```
public final void setInventoryControlNumber(String value)
```


DCK, Una stringa di lettere e/o numeri che viene applicata alle materie prime (carta, laminato, ecc.) utilizzate nella produzione di patenti di guida e carte d'identità. (campo consigliato da DHS), DL/ID, V25ANS

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setLimitedDurationDocIndicator(String value) {#setLimitedDurationDocIndicator-java.lang.String-}
```
public final void setLimitedDurationDocIndicator(String value)
```


DDD, Campo obbligatorio DHS che indica che il titolare della carta ha uno stato legale temporaneo = \u201c1\u201d, DL/ID, F1N

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setNameSuffix(String value) {#setNameSuffix-java.lang.String-}
```
public final void setNameSuffix(String value)
```


DCU, Suffisso del nome (Se la giurisdizione partecipa a sistemi che richiedono il suffisso del nome (PDPS, CDLIS, ecc.), il suffisso deve essere raccolto e visualizzato sulla DL/ID e nel MRT). JR (Junior), SR (Senior), 1ST o I (Primo), fino a 9TH o IX (Nono), DL/ID, V5ANS

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setOrganDonorIndicator(String value) {#setOrganDonorIndicator-java.lang.String-}
```
public final void setOrganDonorIndicator(String value)
```


DDK, Campo che indica che il titolare della carta è un donatore di organi = \u201c1\u201d, DL/ID, F1N

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setPlaceOfBirth(String value) {#setPlaceOfBirth-java.lang.String-}
```
public final void setPlaceOfBirth(String value)
```


DCI, Paese e comune e/o stato/provincia, DL/ID, V33A

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setRaceEthnicity(String value) {#setRaceEthnicity-java.lang.String-}
```
public final void setRaceEthnicity(String value)
```


DCL, Codici per razza o etnia del titolare della carta, come definiti in AAMVA D20, DL/ID, V3A

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setRestrictionCodeDescription(String value) {#setRestrictionCodeDescription-java.lang.String-}
```
public final void setRestrictionCodeDescription(String value)
```


DCR, Testo che descrive i codici di restrizione specifici della giurisdizione che limitano i privilegi di guida, DL, V50ANS

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setStandardEndorsementCode(String value) {#setStandardEndorsementCode-java.lang.String-}
```
public final void setStandardEndorsementCode(String value)
```


DCN, Codice(i) di endoso standard per il titolare. Vedi i codici in D20. Questo elemento dati è un segnaposto per futuri sforzi di standardizzazione dei codici di endoso, DL, F5AN

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setStandardRestrictionCode(String value) {#setStandardRestrictionCode-java.lang.String-}
```
public final void setStandardRestrictionCode(String value)
```


DCO, Codice(i) di restrizione standard per il titolare. Vedi i codici in D20. Questo elemento dati è un segnaposto per futuri sforzi di standardizzazione dei codici di restrizione, DL, F12AN

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setStandardVehClassification(String value) {#setStandardVehClassification-java.lang.String-}
```
public final void setStandardVehClassification(String value)
```


DCM, Codice(i) di classificazione veicolo standard per il titolare. Questo elemento dati è un segnaposto per futuri sforzi di standardizzazione delle classificazioni dei veicoli, DL, F4AN

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setUnder18Until(LocalDate value) {#setUnder18Until-java.time.LocalDate-}
```
public final void setUnder18Until(LocalDate value)
```


DDH, Data in cui il titolare compie 18 anni. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL/ID, F8N

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.time.LocalDate |  |

### setUnder19Until(LocalDate value) {#setUnder19Until-java.time.LocalDate-}
```
public final void setUnder19Until(LocalDate value)
```


DDI, Data in cui il titolare compie 19 anni. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL/ID, F8N

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.time.LocalDate |  |

### setUnder21Until(LocalDate value) {#setUnder21Until-java.time.LocalDate-}
```
public final void setUnder21Until(LocalDate value)
```


DDJ, Data in cui il titolare compie 21 anni. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL/ID, F8N

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.time.LocalDate |  |

### setVehClassDescription(String value) {#setVehClassDescription-java.lang.String-}
```
public final void setVehClassDescription(String value)
```


DCP, Testo che spiega i codici specifici della giurisdizione per le classificazioni dei veicoli che il titolare è autorizzato a guidare, DL, V50ANS

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setVeteranIndicator(String value) {#setVeteranIndicator-java.lang.String-}
```
public final void setVeteranIndicator(String value)
```


DDL, Campo che indica che il titolare è un veterano = \\u201c1\\u201d, DL/ID, F1N

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setWeightKilograms(int value) {#setWeightKilograms-int-}
```
public final void setWeightKilograms(int value)
```


DAX, Peso del titolare in chilogrammi, Es. 84 kg = \\u201c084\\u201d, DL/ID, F3N

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setWeightPounds(int value) {#setWeightPounds-int-}
```
public final void setWeightPounds(int value)
```


DAW, Peso del titolare in libbre, Es. 185 lb = \\u201c185\\u201d, DL/ID, F3N

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setWeightRange(String value) {#setWeightRange-java.lang.String-}
```
public final void setWeightRange(String value)
```


DCE, Indica la fascia di peso approssimativa del titolare: 0 = fino a 31 kg (fino a 70 libbre), 1 = 32 \\u2013 45 kg (71 \\u2013 100 libbre), 2 = 46 - 59 kg (101 \\u2013 130 libbre), 3 = 60 - 70 kg (131 \\u2013 160 libbre), 4 = 71 - 86 kg (161 \\u2013 190 libbre), 5 = 87 - 100 kg (191 \\u2013 220 libbre), 6 = 101 - 113 kg (221 \\u2013 250 libbre), 7 = 114 - 127 kg (251 \\u2013 280 libbre), 8 = 128 \\u2013 145 kg (281 \\u2013 320 libbre), 9 = 146+ kg (321+ libbre), DL/ID, F1N

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

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
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

