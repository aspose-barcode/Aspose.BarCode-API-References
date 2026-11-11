---
title: "Classe USADriveIdCodetext.MandatoryFields"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Classe Aspose.BarCode.ComplexBarcode.USADriveIdCodetextMandatoryFields. Campi degli elementi obbligatori della carta"
type: docs
weight: 820
url: /it/net/aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
## USADriveIdCodetext.MandatoryFields class

Elementi obbligatori (campi) della carta

```csharp
public class MandatoryFields
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/.ctor)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AddressCity](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresscity) { get; set; } | DAI, parte della città dell'indirizzo del titolare della carta, DL/ID, V20ANS |
| [AddressPostalCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresspostalcode) { get; set; } | DAK, parte del codice postale dell'indirizzo del titolare della carta negli Stati Uniti e in Canada. Se la parte finale del codice postale negli Stati Uniti non è nota, verranno usati zeri per riempire la sequenza finale di numeri fino a 9 cifre, DL/ID, F11ANS |
| [AddressState](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstate) { get; set; } | DAJ, parte dello stato dell'indirizzo del titolare della carta, DL/ID, F2A |
| [AddressStreet1](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstreet1) { get; set; } | DAG, parte della via dell'indirizzo del titolare della carta, DL/ID, V35ANS |
| [CountryIdentification](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/countryidentification) { get; set; } | DCG, Paese in cui è rilasciato il DL/ID. U.S. = USA, Canada = CAN, DL/ID, F3A |
| [CustomerIDNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/customeridnumber) { get; set; } | DAQ, Numero assegnato o calcolato dall'autorità emittente, DL/ID, V25ANS |
| [DateOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/dateofbirth) { get; set; } | DBB, Data di emissione del documento, MMDDCCYY per gli Stati Uniti, CCYYMMDD per il Canada, DL/ID, F8N |
| [DocumentDiscriminator](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/documentdiscriminator) { get; set; } | DCF, Il numero deve identificare in modo univoco un documento specifico rilasciato a quel cliente rispetto ad altri che potrebbero essere stati emessi in passato. Questo numero può servire a molteplici scopi, come discriminazione del documento, numero di informazione di audit e/o controllo dell'inventario, DL/ID, V25ANS |
| [EndorsementCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/endorsementcodes) { get; set; } | DCD, Codici di endorsement specifici della giurisdizione, DL, V5ANS |
| [ExpirationDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/expirationdate) { get; set; } | DBA, Data di scadenza del documento, MMDDCCYY per gli Stati Uniti, CCYYMMDD per il Canada, DL/ID, F8N |
| [EyeColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/eyecolor) { get; set; } | DAY, Colore degli occhi del titolare della carta. (codici ANSI D-20). DL/ID, F3A |
| [FamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familyname) { get; set; } | DCS, Cognome del titolare della carta, DL/ID, V40ANS |
| [FamilyNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familynametruncation) { get; set; } | DDE, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N) o se lo stato di troncamento è sconosciuto (U), DL/ID, F1A |
| [FirstName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstname) { get; set; } | DAC, Nome del titolare della carta, DL/ID, V40ANS |
| [FirstNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstnametruncation) { get; set; } | DDF, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N) o se lo stato di troncamento è sconosciuto (U), DL/ID, F1A |
| [Height](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/height) { get; set; } | DAU, Altezza del titolare della carta. Pollici (in): numero di pollici seguito da " in" es. 6'1'' = "073 in" Centimetri (cm): numero di centimetri seguito da " cm" es. 181 centimetri="181 cm" , DL/ID, F6ANS |
| [IssueDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/issuedate) { get; set; } | DBD, Data di emissione del documento, MMDDCCYY per gli Stati Uniti, CCYYMMDD per il Canada, DL/ID, F8N |
| [MiddleName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlename) { get; set; } | DAD, Secondo(i) nome(i) del titolare della carta. Nel caso di più secondi nomi devono essere separati da una virgola ",". , DL/ID, V40ANS |
| [MiddleNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlenametruncation) { get; set; } | DDG, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N) o se lo stato di troncamento è sconosciuto (U), DL/ID, F1A |
| [RestrictionCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/restrictioncodes) { get; set; } | DCB, Codici di restrizioni specifici per la giurisdizione, DL, V12ANS |
| [Sex](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/sex) { get; set; } | DBC, Sesso del titolare della carta. 1 = maschile, 2 = femminile, 9 = non specificato, DL/ID, F1N |
| [VehicleClass](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/vehicleclass) { get; set; } | DCA, Codice di classe/gruppo veicolo specifico per la giurisdizione, DL, V6ANS |

### Vedi anche

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


