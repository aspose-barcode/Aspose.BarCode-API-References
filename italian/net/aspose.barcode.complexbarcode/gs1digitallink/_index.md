---
title: "Classe GS1DigitalLink"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Classe Aspose.BarCode.ComplexBarcode.GS1DigitalLink. Rappresenta il codetext GS1 Digital Link per la codifica e la decodifica come una sequenza ordinata di elementi Application Identifier. L'ordine di origine e gli Application Identifier ripetuti sono preservati. Il codetext costruito è un URI GS1 Digital Link non compresso. I parametri di query NonGS1 e i frammenti URI sono ignorati durante l'analisi."
type: docs
weight: 540
url: /it/net/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class

Rappresenta il codetext GS1 Digital Link per la codifica e la decodifica come una sequenza ordinata di elementi Application Identifier. L'ordine di origine e gli Application Identifier ripetuti sono preservati. Il codetext costruito è un URI GS1 Digital Link non compresso. I parametri di query e i frammenti URI non-GS1 sono ignorati durante l'analisi.

```csharp
public sealed class GS1DigitalLink : IComplexCodetext
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [GS1DigitalLink](gs1digitallink/#constructor)(string) | Inizializza un GS1 Digital Link vuoto con il ramo URI specificato. La chiave primaria viene selezionata automaticamente quando è presente esattamente un candidato chiave primaria. |
| [GS1DigitalLink](gs1digitallink/#constructor_1)(string, string) | Inizializza un GS1 Digital Link vuoto con il ramo URI specificato e la chiave primaria. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/barcodetype/) { get; set; } | Ottiene o imposta il tipo di codice a barre utilizzato per codificare questo GS1 Digital Link. I tipi supportati sono QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF e Code128. Il valore predefinito è QR. |
| [Count](../../aspose.barcode.complexbarcode/gs1digitallink/count/) { get; } | Restituisce il numero di elementi Application Identifier. |
| [Elements](../../aspose.barcode.complexbarcode/gs1digitallink/elements/) { get; } | Restituisce una copia di tutti gli elementi nell'ordine di origine. |
| [Item](../../aspose.barcode.complexbarcode/gs1digitallink/item/) { get; } | Restituisce un elemento in base alla sua posizione nella sequenza ordinata. |
| [PrimaryApplicationIdentifier](../../aspose.barcode.complexbarcode/gs1digitallink/primaryapplicationidentifier/) { get; } | Restituisce l'Application Identifier utilizzato come chiave primaria del Digital Link. Null indica che la chiave primaria viene selezionata automaticamente quando l'URI è costruito. |
| [UriStem](../../aspose.barcode.complexbarcode/gs1digitallink/uristem/) { get; } | Restituisce il prefisso URI assoluto prima del segmento di percorso della chiave primaria GS1. Il ramo non contiene una stringa di query o un frammento. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create)(string, GS1Codetext) | Crea un GS1 Digital Link copiando tutti gli elementi dal codetext GS1 e selezionando l'unica chiave primaria disponibile. |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create_1)(string, GS1Codetext, string) | Crea un GS1 Digital Link copiando tutti gli elementi dal codetext GS1 e utilizzando la chiave primaria specificata. |
| static [Parse](../../aspose.barcode.complexbarcode/gs1digitallink/parse/)(string) | Analizza un URI GS1 Digital Link non compresso. |
| [Add](../../aspose.barcode.complexbarcode/gs1digitallink/add/)(string, string) | Aggiunge un elemento Application Identifier convalidato. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1digitallink/getall/)(string) | Restituisce tutti i valori di un Application Identifier nell'ordine di origine. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/getbarcodetype/)() | Restituisce il tipo di codice a barre utilizzato per codificare questo GS1 Digital Link. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1digitallink/getconstructedcodetext/)() | Costruisce l'URI GS1 Digital Link non compresso. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1digitallink/getfirst/)(string) | Restituisce il primo valore di un Application Identifier. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1digitallink/initfromstring/)(string) | Inizializza questa istanza da un URI GS1 Digital Link non compresso. Lo stato esistente viene sostituito solo dopo che l'URI fornito è stato analizzato con successo. Il tipo di codice a barre selezionato viene preservato. |
| [ToGS1Codetext](../../aspose.barcode.complexbarcode/gs1digitallink/togs1codetext/)() | Crea un codetext GS1 indipendente contenente gli elementi GS1 correnti. Le informazioni solo URI non sono incluse. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1digitallink/tostring/)() | Restituisce l'URI GS1 Digital Link non compresso. |
| [ToUriString](../../aspose.barcode.complexbarcode/gs1digitallink/touristring/)() | Formatta lo stato corrente dell'oggetto come un URI GS1 Digital Link non compresso. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1digitallink/tryparse/)(string, out GS1DigitalLink, out GS1ValidationResult) | Tenta di analizzare un URI GS1 Digital Link non compresso e restituisce errori di convalida strutturati. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1digitallink/validate/)(string) | Convalida un URI GS1 Digital Link non compresso senza creare un oggetto. |

### Vedi anche

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


