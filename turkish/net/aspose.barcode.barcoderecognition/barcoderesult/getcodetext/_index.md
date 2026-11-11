---
title: "BarCodeResult.GetCodeText"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "BarCodeResult yöntemi. Kod metnini kodlama ile alır"
type: docs
weight: 130
url: /tr/net/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult.GetCodeText method

Kod metnini kodlamasıyla birlikte alır.

```csharp
public string GetCodeText(Encoding encoding)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kodlama | Kodlama | Kod metni için kodlama. |

### Dönüş Değeri

Tanımlanan kod metnini içeren bir dize.

## Örnekler

Bu örnek, `GetCodeText` kullanımını gösterir:

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

### Ayrıca Bakınız

* class [BarCodeResult](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


