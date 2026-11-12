---
title: "OptionalFields"
linktitle: "OptionalFields"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Elementi opzionali (campi) della carta"
type: docs
weight: 730
url: /it/nodejs/aspose.barcode/optionalfields/
---

## OptionalFields class

Elementi opzionali (campi) della carta

```js
new OptionalFields()
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getAliasAKAFamilyName()](#getaliasakafamilyname) | DBN, Altro cognome con cui il titolare della carta è noto, DL/ID, V10ANS |
| [getAliasAKAGivenName()](#getaliasakagivenname) | DBG, Altro nome proprio con cui il titolare della carta è noto, DL/ID, V15ANS |
| [getAliasAKASuffixName()](#getaliasakasuffixname) | DBS, Altro suffisso con cui il titolare della carta è noto, DL/ID, V5ANS |
| [getAuditInformation()](#getauditinformation) | DCJ, Una stringa di lettere e/o numeri che identifica quando, dove e da chi è stata prodotta una patente di guida/carta d'identità. Se un |
| [getCardRevisionDate()](#getcardrevisiondate) | DDB, campo obbligatorio DHS che indica la data dell'ultima modifica della versione o della modifica al formato visibile di t |
| [getComplianceType()](#getcompliancetype) | DDA, campo obbligatorio DHS che indica la conformità: “F” = conforme; e, “N” = non conforme, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getendorsementcodedescription) | DCQ, Testo che spiega i codici specifici della giurisdizione che indicano privilegi di guida aggiuntivi concessi al ca |
| [getHairColor()](#gethaircolor) | DAZ, Calvo, nero, biondo, castano, grigio, rosso/marrone, sabbia, bianco, sconosciuto. Se la giurisdizione emittente desidera abbrevia |
| [getHAZMATEndorsementExpDate()](#gethazmatendorsementexpdate) | DDC, Data in cui l'endoso per materiale pericoloso concesso dal documento non è più valido. (MMDDCCYY per gli USA, CC |
| [getInventoryControlNumber()](#getinventorycontrolnumber) | DCK, Una stringa di lettere e/o numeri che è applicata alle materie prime (carta, laminato, ecc.) utilizzate nella produci |
| [getLimitedDurationDocIndicator()](#getlimiteddurationdocindicator) | DDD, campo obbligatorio DHS che indica che il titolare della carta ha uno stato legale temporaneo = “1”, DL/ID, F1N |
| [getNameSuffix()](#getnamesuffix) | DCU, Suffisso del nome (Se la giurisdizione partecipa a sistemi che richiedono il suffisso del nome (PDPS, CDLIS, ecc.), il suffisso deve essere |
| [getOrganDonorIndicator()](#getorgandonorindicator) | DDK, Campo che indica che il titolare della carta è un donatore di organi = “1”, DL/ID, F1N |
| [getPlaceOfBirth()](#getplaceofbirth) | DCI, Paese e municipalità e/o stato/provincia, DL/ID, V33A |
| [getRaceEthnicity()](#getraceethnicity) | DCL, Codici per razza o etnia del titolare della carta, come definito in AAMVA D20, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getrestrictioncodedescription) | DCR, Testo che descrive i codici di restrizione specifici della giurisdizione che limitano i privilegi di guida, DL, V50ANS |
| [getStandardEndorsementCode()](#getstandardendorsementcode) | DCN, Codice(i) di endoso standard per il titolare della carta. Vedi i codici in D20. Questo elemento dati è un segnaposto per futuri sforzi |
| [getStandardRestrictionCode()](#getstandardrestrictioncode) | DCO, Codice(i) di restrizione standard per il titolare della carta. Vedi i codici in D20. Questo elemento dati è un segnaposto per futuri sforzi |
| [getStandardVehClassification()](#getstandardvehclassification) | DCM, Codice(i) di classificazione del veicolo standard per il titolare della carta. Questo elemento dati è un segnaposto per futuri sforzi di st |
| [getUnder18Until()](#getunder18until) | DDH, Data in cui il titolare della carta compie 18 anni. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL/ID, F8N |
| [getUnder21Until()](#getunder21until) | DDJ, Data in cui il titolare della carta compie 21 anni. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL/ID, F8N |
| [getVehClassDescription()](#getvehclassdescription) | DCP, Testo che spiega i codici specifici della giurisdizione per le classificazioni dei veicoli a cui il titolare della carta è autorizzato a guidare |
| [getVeteranIndicator()](#getveteranindicator) | DDL, Campo che indica che il titolare della carta è un veterano = “1”, DL/ID, F1N |
| [getWeightKilograms()](#getweightkilograms) | DAX, Peso del titolare della carta in chilogrammi, Es. 84 kg = “084”, DL/ID, F3N |
| [getWeightPounds()](#getweightpounds) | DAW, Peso del titolare della carta in libbre, Es. 185 lb = “185”, DL/ID, F3N |
| [getWeightRange()](#getweightrange) | DCE, Indica la fascia di peso approssimativa del titolare della carta: 0 = fino a 31 kg (fino a 70 libbre), 1 = 32 – 45 kg (71 – 100 libbre |
| [setAddressStreet2()](#setaddressstreet2) | DAH, Seconda riga della parte via dell'indirizzo del titolare della carta, DL/ID, V35ANS |
| [setAliasAKAFamilyName()](#setaliasakafamilyname) | DBN, Altro cognome con cui il titolare della carta è noto, DL/ID, V10ANS |
| [setAliasAKAGivenName()](#setaliasakagivenname) | DBG, Altro nome proprio con cui il titolare della carta è noto, DL/ID, V15ANS |
| [setAliasAKASuffixName()](#setaliasakasuffixname) | DBS, Altro suffisso con cui il titolare della carta è noto, DL/ID, V5ANS |
| [setAuditInformation()](#setauditinformation) | DCJ, Una stringa di lettere e/o numeri che identifica quando, dove e da chi è stata prodotta una patente di guida/carta d'identità. Se un |
| [setCardRevisionDate()](#setcardrevisiondate) | DDB, campo obbligatorio DHS che indica la data dell'ultima modifica della versione o della modifica al formato visibile di t |
| [setComplianceType()](#setcompliancetype) | DDA, campo obbligatorio DHS che indica la conformità: “F” = conforme; e, “N” = non conforme, DL/ID, F1A |
| [setEndorsementCodeDescription()](#setendorsementcodedescription) | DCQ, Testo che spiega i codici specifici della giurisdizione che indicano privilegi di guida aggiuntivi concessi al ca |
| [setHairColor()](#sethaircolor) | DAZ, Calvo, nero, biondo, castano, grigio, rosso/marrone, sabbia, bianco, sconosciuto. Se la giurisdizione emittente desidera abbrevia |
| [setInventoryControlNumber()](#setinventorycontrolnumber) | DCK, Una stringa di lettere e/o numeri che è applicata alle materie prime (carta, laminato, ecc.) utilizzate nella produci |
| [setLimitedDurationDocIndicator()](#setlimiteddurationdocindicator) | DDD, campo obbligatorio DHS che indica che il titolare della carta ha uno stato legale temporaneo = “1”, DL/ID, F1N |
| [setNameSuffix()](#setnamesuffix) | DCU, Suffisso del nome (Se la giurisdizione partecipa a sistemi che richiedono il suffisso del nome (PDPS, CDLIS, ecc.), il suffisso deve essere |
| [setOrganDonorIndicator()](#setorgandonorindicator) | DDK, Campo che indica che il titolare della carta è un donatore di organi = “1”, DL/ID, F1N |
| [setPlaceOfBirth()](#setplaceofbirth) | DCI, Paese e municipalità e/o stato/provincia, DL/ID, V33A |
| [setRaceEthnicity()](#setraceethnicity) | DCL, Codici per razza o etnia del titolare della carta, come definito in AAMVA D20, DL/ID, V3A |
| [setRestrictionCodeDescription()](#setrestrictioncodedescription) | DCR, Testo che descrive i codici di restrizione specifici della giurisdizione che limitano i privilegi di guida, DL, V50ANS |
| [setStandardEndorsementCode()](#setstandardendorsementcode) | DCN, Codice(i) di endoso standard per il titolare della carta. Vedi i codici in D20. Questo elemento dati è un segnaposto per futuri sforzi |
| [setStandardRestrictionCode()](#setstandardrestrictioncode) | DCO, Codice(i) di restrizione standard per il titolare della carta. Vedi i codici in D20. Questo elemento dati è un segnaposto per futuri sforzi |
| [setStandardVehClassification()](#setstandardvehclassification) | DCM, Codice(i) di classificazione del veicolo standard per il titolare della carta. Questo elemento dati è un segnaposto per futuri sforzi di st |
| [setUnder18Until()](#setunder18until) | DDI, Data in cui il titolare della carta compie 19 anni. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL/ID, F8N |
| [setUnder19Until()](#setunder19until) | DDI, Data in cui il titolare della carta compie 19 anni. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL/ID, F8N |
| [setUnder21Until()](#setunder21until) | DDJ, Data in cui il titolare della carta compie 21 anni. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL/ID, F8N |
| [setVehClassDescription()](#setvehclassdescription) | DCP, Testo che spiega i codici specifici della giurisdizione per le classificazioni dei veicoli a cui il titolare della carta è autorizzato a guidare |
| [setVeteranIndicator()](#setveteranindicator) | DDL, Campo che indica che il titolare della carta è un veterano = “1”, DL/ID, F1N |
| [setWeightKilograms()](#setweightkilograms) | DAX, Peso del titolare della carta in chilogrammi, Es. 84 kg = “084”, DL/ID, F3N |
| [setWeightPounds()](#setweightpounds) | DAW, Peso del titolare della carta in libbre, Es. 185 lb = “185”, DL/ID, F3N |
| [setWeightRange()](#setweightrange) | DCE, Indica la fascia di peso approssimativa del titolare della carta: 0 = fino a 31 kg (fino a 70 libbre), 1 = 32 – 45 kg (71 – 100 libbre |

### getAliasAKAFamilyName() {#getaliasakafamilyname}

DBN, Altro cognome con cui il titolare della carta è noto, DL/ID, V10ANS

### getAliasAKAGivenName() {#getaliasakagivenname}

DBG, Altro nome proprio con cui il titolare della carta è noto, DL/ID, V15ANS

### getAliasAKASuffixName() {#getaliasakasuffixname}

DBS, Altro suffisso con cui il titolare della carta è noto, DL/ID, V5ANS

### getAuditInformation() {#getauditinformation}

DCJ, Una stringa di lettere e/o numeri che identifica quando, dove e da chi è stata prodotta una patente di guida/carta d'identità. Se le informazioni di audit non sono utilizzate sulla carta o sul MRT, devono essere incluse nel record del conducente, DL/ID, V25ANS

### getCardRevisionDate() {#getcardrevisiondate}

DDB, campo obbligatorio DHS che indica la data dell'ultima modifica della versione o della modifica del formato visibile del DL/ID. (MMDDCCYY per gli Stati Uniti, CCYYMMDD per il Canada), DL/ID, F8N

### getComplianceType() {#getcompliancetype}

DDA, campo obbligatorio DHS che indica la conformità: “F” = conforme; e, “N” = non conforme, DL/ID, F1A

### getEndorsementCodeDescription() {#getendorsementcodedescription}

DCQ, Testo che spiega i codici specifici della giurisdizione che indicano i privilegi di guida aggiuntivi concessi al titolare della carta oltre la classe del veicolo, DL, V50ANS

### getHairColor() {#gethaircolor}

DAZ, Calvo, nero, biondo, castano, grigio, rosso/marrone, sabbia, bianco, sconosciuto. Se la giurisdizione emittente desidera abbreviare i colori, devono essere utilizzati i codici a tre caratteri forniti in AAMVA D20, DL/ID, V12A

### getHAZMATEndorsementExpDate() {#gethazmatendorsementexpdate}

DDC, Data in cui l'endoso per materiale pericoloso concesso dal documento non è più valido. (MMDDCCYY per gli Stati Uniti, CCYYMMDD per il Canada), DL, F8N

### getInventoryControlNumber() {#getinventorycontrolnumber}

DCK, Una stringa di lettere e/o numeri che viene applicata alle materie prime (carta, laminato, ecc.) utilizzate nella produzione di patenti di guida e carte d'identità. (campo consigliato da DHS), DL/ID, V25ANS

### getLimitedDurationDocIndicator() {#getlimiteddurationdocindicator}

DDD, campo obbligatorio DHS che indica che il titolare della carta ha uno stato legale temporaneo = “1”, DL/ID, F1N

### getNameSuffix() {#getnamesuffix}

DCU, Suffisso del nome (Se la giurisdizione partecipa a sistemi che richiedono il suffisso del nome (PDPS, CDLIS, ecc.), il suffisso deve essere raccolto e visualizzato sul DL/ID e nel MRT). JR (Junior), SR (Senior), 1ST o I (Primo), fino a 9TH o IX (Nono), DL/ID, V5ANS

### getOrganDonorIndicator() {#getorgandonorindicator}

DDK, Campo che indica che il titolare della carta è un donatore di organi = “1”, DL/ID, F1N

### getPlaceOfBirth() {#getplaceofbirth}

DCI, Paese e municipalità e/o stato/provincia, DL/ID, V33A

### getRaceEthnicity() {#getraceethnicity}

DCL, Codici per razza o etnia del titolare della carta, come definito in AAMVA D20, DL/ID, V3A

### getRestrictionCodeDescription() {#getrestrictioncodedescription}

DCR, Testo che descrive i codici di restrizione specifici della giurisdizione che limitano i privilegi di guida, DL, V50ANS

### getStandardEndorsementCode() {#getstandardendorsementcode}

DCN, Codice(i) di endoso standard per il titolare della carta. Vedere i codici in D20. Questo elemento dati è un segnaposto per futuri sforzi di standardizzazione dei codici di endoso, DL, F5AN

### getStandardRestrictionCode() {#getstandardrestrictioncode}

DCO, Codice(i) di restrizione standard per il titolare della carta. Vedere i codici in D20. Questo elemento dati è un segnaposto per futuri sforzi di standardizzazione dei codici di restrizione, DL, F12AN

### getStandardVehClassification() {#getstandardvehclassification}

DCM, Codice(i) di classificazione del veicolo standard per il titolare della carta. Questo elemento dati è un segnaposto per futuri sforzi di standardizzazione delle classificazioni dei veicoli, DL, F4AN

### getUnder18Until() {#getunder18until}

DDH, Data in cui il titolare della carta compie 18 anni. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL/ID, F8N

### getUnder21Until() {#getunder21until}

DDJ, Data in cui il titolare della carta compie 21 anni. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL/ID, F8N

### getVehClassDescription() {#getvehclassdescription}

DCP, Testo che spiega i codici specifici della giurisdizione per le classificazioni dei veicoli che il titolare della carta è autorizzato a guidare, DL, V50ANS

### getVeteranIndicator() {#getveteranindicator}

DDL, Campo che indica che il titolare della carta è un veterano = “1”, DL/ID, F1N

### getWeightKilograms() {#getweightkilograms}

DAX, Peso del titolare della carta in chilogrammi, Es. 84 kg = “084”, DL/ID, F3N

### getWeightPounds() {#getweightpounds}

DAW, Peso del titolare della carta in libbre, Es. 185 lb = “185”, DL/ID, F3N

### getWeightRange() {#getweightrange}

DCE, Indica la fascia di peso approssimativa del titolare della carta: 0 = fino a 31 kg (fino a 70 libbre), 1 = 32 – 45 kg (71 – 100 libbre), 2 = 46 - 59 kg (101 – 130 libbre), 3 = 60 - 70 kg (131 – 160 libbre), 4 = 71 - 86 kg (161 – 190 libbre), 5 = 87 - 100 kg (191 – 220 libbre), 6 = 101 - 113 kg (221 – 250 libbre), 7 = 114 - 127 kg (251 – 280 libbre), 8 = 128 – 145 kg (281 – 320 libbre), 9 = 146+ kg (321+ libbre), DL/ID, F1N

### setAddressStreet2() {#setaddressstreet2}

DAH, Seconda riga della parte via dell'indirizzo del titolare della carta, DL/ID, V35ANS

### setAliasAKAFamilyName() {#setaliasakafamilyname}

DBN, Altro cognome con cui il titolare della carta è noto, DL/ID, V10ANS

### setAliasAKAGivenName() {#setaliasakagivenname}

DBG, Altro nome proprio con cui il titolare della carta è noto, DL/ID, V15ANS

### setAliasAKASuffixName() {#setaliasakasuffixname}

DBS, Altro suffisso con cui il titolare della carta è noto, DL/ID, V5ANS

### setAuditInformation() {#setauditinformation}

DCJ, Una stringa di lettere e/o numeri che identifica quando, dove e da chi è stata prodotta una patente di guida/carta d'identità. Se le informazioni di audit non sono utilizzate sulla carta o sul MRT, devono essere incluse nel record del conducente, DL/ID, V25ANS

### setCardRevisionDate() {#setcardrevisiondate}

DDB, campo obbligatorio DHS che indica la data dell'ultima modifica della versione o della modifica del formato visibile del DL/ID. (MMDDCCYY per gli Stati Uniti, CCYYMMDD per il Canada), DL/ID, F8N

### setComplianceType() {#setcompliancetype}

DDA, campo obbligatorio DHS che indica la conformità: “F” = conforme; e, “N” = non conforme, DL/ID, F1A

### setEndorsementCodeDescription() {#setendorsementcodedescription}

DCQ, Testo che spiega i codici specifici della giurisdizione che indicano i privilegi di guida aggiuntivi concessi al titolare della carta oltre la classe del veicolo, DL, V50ANS

### setHairColor() {#sethaircolor}

DAZ, Calvo, nero, biondo, castano, grigio, rosso/marrone, sabbia, bianco, sconosciuto. Se la giurisdizione emittente desidera abbreviare i colori, devono essere utilizzati i codici a tre caratteri forniti in AAMVA D20, DL/ID, V12A

### setInventoryControlNumber() {#setinventorycontrolnumber}

DCK, Una stringa di lettere e/o numeri che viene applicata alle materie prime (carta, laminato, ecc.) utilizzate nella produzione di patenti di guida e carte d'identità. (campo consigliato da DHS), DL/ID, V25ANS

### setLimitedDurationDocIndicator() {#setlimiteddurationdocindicator}

DDD, campo obbligatorio DHS che indica che il titolare della carta ha uno stato legale temporaneo = “1”, DL/ID, F1N

### setNameSuffix() {#setnamesuffix}

DCU, Suffisso del nome (Se la giurisdizione partecipa a sistemi che richiedono il suffisso del nome (PDPS, CDLIS, ecc.), il suffisso deve essere raccolto e visualizzato sul DL/ID e nel MRT). JR (Junior), SR (Senior), 1ST o I (Primo), fino a 9TH o IX (Nono), DL/ID, V5ANS

### setOrganDonorIndicator() {#setorgandonorindicator}

DDK, Campo che indica che il titolare della carta è un donatore di organi = “1”, DL/ID, F1N

### setPlaceOfBirth() {#setplaceofbirth}

DCI, Paese e municipalità e/o stato/provincia, DL/ID, V33A

### setRaceEthnicity() {#setraceethnicity}

DCL, Codici per razza o etnia del titolare della carta, come definito in AAMVA D20, DL/ID, V3A

### setRestrictionCodeDescription() {#setrestrictioncodedescription}

DCR, Testo che descrive i codici di restrizione specifici della giurisdizione che limitano i privilegi di guida, DL, V50ANS

### setStandardEndorsementCode() {#setstandardendorsementcode}

DCN, Codice(i) di endoso standard per il titolare della carta. Vedere i codici in D20. Questo elemento dati è un segnaposto per futuri sforzi di standardizzazione dei codici di endoso, DL, F5AN

### setStandardRestrictionCode() {#setstandardrestrictioncode}

DCO, Codice(i) di restrizione standard per il titolare della carta. Vedere i codici in D20. Questo elemento dati è un segnaposto per futuri sforzi di standardizzazione dei codici di restrizione, DL, F12AN

### setStandardVehClassification() {#setstandardvehclassification}

DCM, Codice(i) di classificazione del veicolo standard per il titolare della carta. Questo elemento dati è un segnaposto per futuri sforzi di standardizzazione delle classificazioni dei veicoli, DL, F4AN

### setUnder18Until() {#setunder18until}

DDI, Data in cui il titolare della carta compie 19 anni. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL/ID, F8N

### setUnder19Until() {#setunder19until}

DDI, Data in cui il titolare della carta compie 19 anni. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL/ID, F8N

### setUnder21Until() {#setunder21until}

DDJ, Data in cui il titolare della carta compie 21 anni. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL/ID, F8N

### setVehClassDescription() {#setvehclassdescription}

DCP, Testo che spiega i codici specifici della giurisdizione per le classificazioni dei veicoli che il titolare della carta è autorizzato a guidare, DL, V50ANS

### setVeteranIndicator() {#setveteranindicator}

DDL, Campo che indica che il titolare della carta è un veterano = “1”, DL/ID, F1N

### setWeightKilograms() {#setweightkilograms}

DAX, Peso del titolare della carta in chilogrammi, Es. 84 kg = “084”, DL/ID, F3N

### setWeightPounds() {#setweightpounds}

DAW, Peso del titolare della carta in libbre, Es. 185 lb = “185”, DL/ID, F3N

### setWeightRange() {#setweightrange}

DCE, Indica la fascia di peso approssimativa del titolare della carta: 0 = fino a 31 kg (fino a 70 libbre), 1 = 32 – 45 kg (71 – 100 libbre), 2 = 46 - 59 kg (101 – 130 libbre), 3 = 60 - 70 kg (131 – 160 libbre), 4 = 71 - 86 kg (161 – 190 libbre), 5 = 87 - 100 kg (191 – 220 libbre), 6 = 101 - 113 kg (221 – 250 libbre), 7 = 114 - 127 kg (251 – 280 libbre), 8 = 128 – 145 kg (281 – 320 libbre), 9 = 146+ kg (321+ libbre), DL/ID, F1N
