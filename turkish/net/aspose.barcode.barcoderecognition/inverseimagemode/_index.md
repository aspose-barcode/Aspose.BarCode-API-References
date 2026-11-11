---
title: "Enum InverseImageMode"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.BarCodeRecognition.InverseImageMode enum. Renk parlaklığı ters çevrilmiş görüntülerde barkodların ek tanımını etkinleştiren veya devre dışı bırakan mod"
type: docs
weight: 270
url: /tr/net/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enumeration

Renkleri (parlaklığı) ters çevrilmiş görüntülerde barkodların ek tanımasını etkinleştiren veya devre dışı bırakan mod.

```csharp
public enum InverseImageMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Auto | `0` | QR Code dışındaki tüm barkod türleri için ters görüntülerde ek barkod tanımını devre dışı bırakır. |
| Disabled | `1` | Ters görüntülerde ek barkod tanımını devre dışı bırakır. |
| Enabled | `2` | Ters görüntülerde ek barkod tanımını etkinleştirir |

## Örnekler

Bu örnek, InverseImage modunun nasıl kullanılacağını gösterir

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


