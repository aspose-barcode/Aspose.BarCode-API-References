---
title: "enum"
linktitle: "TwoDComponentType"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " enum. C++ içinde 2D bileşeninin türü."
type: docs
weight: 8700
url: /tr/cpp/aspose.barcode.generation/twodcomponenttype/
---
## TwoDComponentType enum


2D bileşen tipi

```cpp
enum class TwoDComponentType
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Otomatik | 0 | 2D bileşeninin türünü otomatik olarak seç |
| CC_A | 1 | CC-A 2D bileşen türü. MicroPDF417'nin yapısal bir varyantıdır. |
| CC_B | 2 | CC-B 2D bileşen türü. Bir MicroPDF417 sembolüdür. |
| CC_C | 3 | CC-C 2D bileşen türü. Bir PDF417 sembolüdür. |

## Açıklamalar


Bu örnek, bir GS1 Composite Bar görüntüsünün nasıl oluşturulup kaydedileceğini gösterir. 1D kod metni ile 2D kod metninin '/' sembolüyle ayrıldığını unutmayın.
```cpp
[C#]
var codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
    using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
    {
    generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
    generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;

    // 2D bileşenin en-boy oranı
    generator.Parameters.Barcode.Pdf417.AspectRatio = 3;

    // 1D ve 2D bileşenlerin X Boyutu
    generator.Parameters.Barcode.XDimension.Pixels = 3;

    // 1D bileşenin yüksekliği
    generator.Parameters.Barcode.BarHeight.Pixels = 100;

    generator.Save("test.png");
}
```

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
