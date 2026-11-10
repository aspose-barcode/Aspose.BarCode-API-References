---
title: "BarCodeResult.GetCodeText"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "BarCodeResult-Methode. Liefert den Code-Text mit Kodierung."
type: docs
weight: 130
url: /de/net/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult.GetCodeText method

Liefert den Code‑Text mit Kodierung.

```csharp
public string GetCodeText(Encoding encoding)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Kodierung | Kodierung | Die Kodierung für den Code-Text. |

### Rückgabewert

Eine Zeichenkette, die den erkannten Code-Text enthält.

## Beispiele

Dieses Beispiel zeigt, wie man `GetCodeText` verwendet:

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

### Siehe auch

* class [BarCodeResult](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


