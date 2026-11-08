---
title: "enum"
linktitle: "InverseImageMode"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "C++'da enum nasıl kullanılır?"
type: docs
weight: 3900
url: /tr/cpp/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enum




```cpp
enum class InverseImageMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Auto | 0 | Ters görüntülerde barkodların ek tanımasını, [QR](../../aspose.barcode.barcoderecognition.qr/) Kodu hariç tüm barkod türleri için devre dışı bırakır. |
| Devre dışı | 1 | Ters görüntülerde barkodların ek tanımasını devre dışı bırakır. |
| Etkin | 2 | Ters görüntülerde barkodların ek tanımasını etkinleştirir |

## Açıklamalar


Ters renkli (parlaklık) görüntülerde barkodların ek tanımını etkinleştiren veya devre dışı bırakan mod.

Bu örnek, InverseImage modunun nasıl kullanılacağını gösterir
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
