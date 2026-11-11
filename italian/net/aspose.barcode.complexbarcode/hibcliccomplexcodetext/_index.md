---
title: "Classe HIBCLICComplexCodetext"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Aspose.BarCode.ComplexBarcode.HIBCLICComplexCodetext class. Classe base per la codifica e decodifica del testo incorporato nel codice HIBC LIC"
type: docs
weight: 560
url: /it/net/aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
## HIBCLICComplexCodetext class

Classe base per la codifica e decodifica del testo incorporato nel codice HIBC LIC.

```csharp
public abstract class HIBCLICComplexCodetext : IComplexCodetext
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | Ottiene o imposta il tipo di codice a barre. Il testo del codice HIBC LIC può essere codificato usando i tipi di codifica HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC e HIBCQRLIC. Valore predefinito: HIBCCode39LIC. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | Ottiene il tipo di codice a barre. |
| abstract [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getconstructedcodetext/)() | Costruisce il testo del codice |
| abstract [InitFromString](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/initfromstring/)(string) | Inizializza l'istanza dal testo del codice costruito. |

## Esempi

Questo esempio mostra come decodificare il codetext grezzo HIBC LIC in un'istanza HIBCLICComplexCodetext.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.HIBCAztecLIC))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        HIBCLICComplexCodetext resultHIBCLICComplexCodetext = ComplexCodetextReader.TryDecodeHIBCLIC(result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

### Vedi anche

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


