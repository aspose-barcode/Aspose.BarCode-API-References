---
title: "enum"
linktitle: "ComplexBackgroundMode"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "C++'da enum nasıl kullanılır?"
type: docs
weight: 3700
url: /tr/cpp/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enum




```cpp
enum class ComplexBackgroundMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Otomatik | 0 | Şu anda Disabled ile aynı. Renkli görüntülerde renkli barkodların ek tanımasını devre dışı bırakır. |
| Devre dışı | 1 | Renkli görüntülerde renkli barkodların ek tanımasını devre dışı bırakır. |
| Etkin | 2 | Renkli görüntülerde renkli barkodların ek tanımasını etkinleştirir. |

## Açıklamalar


Renkli görüntülerde renkli barkodların ek tanımını etkinleştiren veya devre dışı bırakan mod.

Bu örnek ComplexBackground modunun nasıl kullanılacağını gösterir
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
