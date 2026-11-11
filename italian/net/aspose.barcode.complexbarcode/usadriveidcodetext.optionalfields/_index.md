---
title: "Classe USADriveIdCodetext.OptionalFields"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Classe Aspose.BarCode.ComplexBarcode.USADriveIdCodetextOptionalFields. Campi opzionali degli elementi della carta"
type: docs
weight: 830
url: /it/net/aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
## USADriveIdCodetext.OptionalFields class

Elementi opzionali (campi) della carta

```csharp
public class OptionalFields
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/.ctor)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AddressStreet2](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/addressstreet2) { get; set; } | DAH, Seconda riga della parte via dell'indirizzo del titolare della carta, DL/ID, V35ANS |
| [AliasAKAFamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakafamilyname) { get; set; } | DBN, Altro cognome con cui è noto il titolare della carta, DL/ID, V10ANS |
| [AliasAKAGivenName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakagivenname) { get; set; } | DBG, Altro nome proprio con cui è noto il titolare della carta, DL/ID, V15ANS |
| [AliasAKASuffixName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakasuffixname) { get; set; } | DBS, Altro suffisso con cui è noto il titolare della carta, DL/ID, V5ANS |
| [AuditInformation](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/auditinformation) { get; set; } | DCJ, Una stringa di lettere e/o numeri che identifica quando, dove e da chi è stata prodotta la patente di guida/carta d'identità. Se le informazioni di audit non sono utilizzate sulla carta o sul MRT, devono essere incluse nel record del conducente, DL/ID, V25ANS |
| [CardRevisionDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/cardrevisiondate) { get; set; } | DDB, Campo richiesto dal DHS che indica la data dell'ultima modifica della versione o della modifica al formato visibile del DL/ID. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL/ID, F8N |
| [ComplianceType](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/compliancetype) { get; set; } | DDA, Campo richiesto dal DHS che indica la conformità: “F” = conforme; e, “N” = non conforme, DL/ID, F1A |
| [EndorsementCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/endorsementcodedescription) { get; set; } | DCQ, Testo che spiega il(i) codice(i) specifico(i) della giurisdizione che indica i privilegi di guida aggiuntivi concessi al titolare della carta oltre la classe del veicolo, DL, V50ANS |
| [HairColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/haircolor) { get; set; } | DAZ, Calvo, nero, biondo, castano, grigio, rosso/marrone, sabbioso, bianco, sconosciuto. Se la giurisdizione emittente desidera abbreviare i colori, devono essere usati i codici a tre caratteri forniti in AAMVA D20, DL/ID, V12A |
| [HAZMATEndorsementExpDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/hazmatendorsementexpdate) { get; set; } | DDC, Data in cui l'approvazione per materiale pericoloso concessa dal documento non è più valida. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL, F8N |
| [InventoryControlNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/inventorycontrolnumber) { get; set; } | DCK, Una stringa di lettere e/o numeri che è applicata alle materie prime (carta, laminato, ecc.) utilizzate nella produzione di patenti di guida e carte d'identità. (campo consigliato dal DHS), DL/ID, V25ANS |
| [LimitedDurationDocIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/limiteddurationdocindicator) { get; set; } | DDD, Campo richiesto dal DHS che indica che il titolare della carta ha uno stato legale temporaneo = “1”, DL/ID, F1N |
| [NameSuffix](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/namesuffix) { get; set; } | DCU, Suffisso del nome (Se la giurisdizione partecipa a sistemi che richiedono il suffisso del nome (PDPS, CDLIS, ecc.), il suffisso deve essere raccolto e visualizzato sulla patente/ID e nel MRT). JR (Junior), SR (Senior), 1ST o I (Primo), fino a 9TH o IX (Nono), DL/ID, V5ANS |
| [OrganDonorIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/organdonorindicator) { get; set; } | DDK, Campo che indica che il titolare della carta è un donatore di organi = “1”, DL/ID, F1N |
| [PlaceOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/placeofbirth) { get; set; } | DCI, Paese e comune e/o stato/provincia, DL/ID, V33A |
| [RaceEthnicity](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/raceethnicity) { get; set; } | DCL, Codici per la razza o l'etnia del titolare della carta, come definito in AAMVA D20, DL/ID, V3A |
| [RestrictionCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/restrictioncodedescription) { get; set; } | DCR, Testo che descrive i codici di restrizione specifici della giurisdizione che limitano i privilegi di guida, DL, V50ANS |
| [StandardEndorsementCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardendorsementcode) { get; set; } | DCN, Codici di endorsement standard per il titolare della carta. Vedi i codici in D20. Questo elemento dati è un segnaposto per futuri sforzi di standardizzazione dei codici di endorsement, DL, F5AN |
| [StandardRestrictionCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardrestrictioncode) { get; set; } | DCO, Codici di restrizione standard per il titolare della carta. Vedi i codici in D20. Questo elemento dati è un segnaposto per futuri sforzi di standardizzazione dei codici di restrizione, DL, F12AN |
| [StandardVehClassification](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardvehclassification) { get; set; } | DCM, Codici di classificazione dei veicoli standard per il titolare della carta. Questo elemento dati è un segnaposto per futuri sforzi di standardizzazione delle classificazioni dei veicoli, DL, F4AN |
| [Under18Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under18until) { get; set; } | DDH, Data in cui il titolare della carta compie 18 anni. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL/ID, F8N |
| [Under19Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under19until) { get; set; } | DDI, Data in cui il titolare della carta compie 19 anni. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL/ID, F8N |
| [Under21Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under21until) { get; set; } | DDJ, Data in cui il titolare della carta compie 21 anni. (MMDDCCYY per gli USA, CCYYMMDD per il Canada), DL/ID, F8N |
| [VehClassDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/vehclassdescription) { get; set; } | DCP, Testo che spiega i codici specifici della giurisdizione per le classificazioni dei veicoli che il titolare della carta è autorizzato a guidare, DL, V50ANS |
| [VeteranIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/veteranindicator) { get; set; } | DDL, Campo che indica che il titolare della carta è un veterano = “1”, DL/ID, F1N |
| [WeightKilograms](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightkilograms) { get; set; } | DAX, Peso del titolare della carta in chilogrammi, Es. 84 kg = “084”, DL/ID, F3N |
| [WeightPounds](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightpounds) { get; set; } | DAW, Peso del titolare della carta in libbre, Es. 185 lb = “185”, DL/ID, F3N |
| [WeightRange](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightrange) { get; set; } | DCE, Indica la fascia di peso approssimativa del titolare della carta: 0 = fino a 31 kg (fino a 70 libbre), 1 = 32 – 45 kg (71 – 100 libbre), 2 = 46 - 59 kg (101 – 130 libbre), 3 = 60 - 70 kg (131 – 160 libbre), 4 = 71 - 86 kg (161 – 190 libbre), 5 = 87 - 100 kg (191 – 220 libbre), 6 = 101 - 113 kg (221 – 250 libbre), 7 = 114 - 127 kg (251 – 280 libbre), 8 = 128 – 145 kg (281 – 320 libbre), 9 = 146+ kg (321+ libbre), DL/ID, F1N |

### Vedi anche

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


