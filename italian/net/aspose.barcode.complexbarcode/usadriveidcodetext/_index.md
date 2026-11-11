---
title: "Classe USADriveIdCodetext"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetext class. Classe per la codifica e la decodifica del testo incorporato nel codice PDF417 della Patente di Guida USA"
type: docs
weight: 810
url: /it/net/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class

Classe per la codifica e la decodifica del testo incorporato nel codice PDF417 della Patente di Guida USA.

```csharp
public sealed class USADriveIdCodetext : IComplexCodetext
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [USADriveIdCodetext](usadriveidcodetext/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AAMVAVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/aamvaversionnumber/) { get; set; } | Numero di versione AAMVA 00-99 |
| [IssuerIdentificationNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/issueridentificationnumber/) { get; set; } | Questo numero identifica in modo univoco la giurisdizione emittente e può essere ottenuto contattando l'Autorità di Emissione ISO (AAMVA). L'intero IIN a 6 cifre dovrebbe essere codificato. |
| [JurisdictionSpecificSubfile](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionspecificsubfile/) { get; set; } | Campi specifici della giurisdizione |
| [JurisdictionVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionversionnumber/) { get; set; } | Numero di versione della giurisdizione 00-99 |
| [MandatoryElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/mandatoryelements/) { get; set; } | Elementi obbligatori (campi) della carta |
| [NumberOfEntries](../../aspose.barcode.complexbarcode/usadriveidcodetext/numberofentries/) { get; set; } | Numero 00-99 di sottofile |
| [OptionalElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/optionalelements/) { get; set; } | Elementi opzionali (campi) della carta |
| [SubfileDesignator](../../aspose.barcode.complexbarcode/usadriveidcodetext/subfiledesignator/) { get; set; } | Contiene informazioni sui seguenti sottofile, tipi, offset e lunghezze. Importante: impostare solo il tipo, l'offset e la lunghezza verranno impostati automaticamente. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/usadriveidcodetext/getbarcodetype/)() | Restituisce il tipo di codice a barre della patente USA (Pdf417) |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/usadriveidcodetext/getconstructedcodetext/)() | Costruisci il testo del codice dai dati della patente USA |
| [InitFromString](../../aspose.barcode.complexbarcode/usadriveidcodetext/initfromstring/)(string) | Inizializza l'oggetto della patente USA dal testo del codice |
| [SaveToXml](../../aspose.barcode.complexbarcode/usadriveidcodetext/savetoxml/)(Stream) | Salva in XML |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields) | Elementi obbligatori (campi) della carta |
| class [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields) | Elementi opzionali (campi) della carta |
| class [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties) | Le proprietà del subfile USA DL, offset e lunghezza, sono impostate automaticamente. |

### Vedi anche

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


