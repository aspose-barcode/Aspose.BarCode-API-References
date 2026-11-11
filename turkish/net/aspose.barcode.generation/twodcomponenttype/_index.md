---
title: "Enum TwoDComponentType"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.TwoDComponentType enum. 2D bileşen türü"
type: docs
weight: 1730
url: /tr/net/aspose.barcode.generation/twodcomponenttype/
---
## TwoDComponentType enumeration

2D bileşen türü

```csharp
public enum TwoDComponentType
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Auto | `0` | 2D bileşen türünü otomatik seç |
| CC_A | `1` | CC-A tipi 2D bileşen. MicroPDF417'nin yapısal bir varyantıdır |
| CC_B | `2` | CC-B tipi 2D bileşen. Bir MicroPDF417 sembolüdür. |
| CC_C | `3` | CC-C tipi 2D bileşen. Bir PDF417 sembolüdür. |

## Örnekler

Bu örnek, bir GS1 Bileşik Çubuk görüntüsü nasıl oluşturulur ve kaydedilir gösterir. 1D kod metni ve 2D kod metninin '/' sembolüyle ayrıldığını unutmayın.

```csharp
[C#]
var codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
{
    generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
    generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;
    
    // 2D bileşenin en-boy oranı
    generator.Parameters.Barcode.Pdf417.AspectRatio = 3;
        
    // 1D ve 2D bileşenlerin X-Boyutu
    generator.Parameters.Barcode.XDimension.Pixels = 3;
        
    // 1D bileşenin yüksekliği
    generator.Parameters.Barcode.BarHeight.Pixels = 100;
    
    generator.Save("test.png");
}
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


