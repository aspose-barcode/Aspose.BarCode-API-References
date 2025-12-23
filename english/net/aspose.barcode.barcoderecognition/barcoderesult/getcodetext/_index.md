---
title: BarCodeResult.GetCodeText
second_title: Aspose.BarCode for .NET API Reference
description: BarCodeResult method. Gets the code text with encoding
type: docs
weight: 120
url: /net/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult.GetCodeText method

Gets the code text with encoding.

```csharp
public string GetCodeText(Encoding encoding)
```

| Parameter | Type | Description |
| --- | --- | --- |
| encoding | Encoding | The encoding for codetext. |

### Return Value

A string containing recognized code text.

## Examples

This example shows how to use `GetCodeText`:

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

### See Also

* class [BarCodeResult](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


