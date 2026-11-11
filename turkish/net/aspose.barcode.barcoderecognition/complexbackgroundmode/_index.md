---
title: "Enum ComplexBackgroundMode"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.BarCodeRecognition.ComplexBackgroundMode enum. Renkli görüntülerde renkli barkodların ek tanımını etkinleştiren veya devre dışı bırakan mod."
type: docs
weight: 200
url: /tr/net/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enumeration

Renkli görüntülerde renkli barkodların ek tanımasını etkinleştiren veya devre dışı bırakan mod.

```csharp
public enum ComplexBackgroundMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Auto | `0` | Şu anda Disabled ile aynı. Renkli görüntülerde renkli barkodların ek tanımını devre dışı bırakır. |
| Disabled | `1` | Renkli görüntülerde renkli barkodların ek tanımını devre dışı bırakır. |
| Enabled | `2` | Renkli görüntülerde renkli barkodların ek tanımını etkinleştirir. |

## Örnekler

Bu örnek, ComplexBackground modunun nasıl kullanılacağını gösterir

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


