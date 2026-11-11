---
title: "BarCodeResult.GetCodeText"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "BarCodeResult methode. Haalt de code-tekst op met codering"
type: docs
weight: 130
url: /nl/net/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult.GetCodeText method

Haalt de code-tekst op met codering.

```csharp
public string GetCodeText(Encoding encoding)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| codering | Codering | De codering voor code-tekst. |

### Retourwaarde

Een tekenreeks die herkende code-tekst bevat.

## Voorbeelden

Dit voorbeeld toont hoe `GetCodeText` te gebruiken:

```csharp
[C#]
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    gen.SetCodeText("車種名", Encoding.GetEncoding(932));
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

### Zie ook

* class [BarCodeResult](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


