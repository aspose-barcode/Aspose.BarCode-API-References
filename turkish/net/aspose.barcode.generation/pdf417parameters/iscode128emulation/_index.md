---
title: "Pdf417Parameters.IsCode128Emulation"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Pdf417Parameters özelliği. Yalnızca MicroPdf417 ile kullanılabilir ve Code 128 emülasyon modlarını kodlar. 908 ve 909 modlarında ikinci konumdaki FNC1'i kodlayabilir, ayrıca 910 ve 911'i de kodlayabilir; bu sadece tanınan MicroPdf417'nin Code 128 olarak yorumlanabileceğini gösterir"
type: docs
weight: 60
url: /tr/net/aspose.barcode.generation/pdf417parameters/iscode128emulation/
---
## Pdf417Parameters.IsCode128Emulation property

Sadece MicroPdf417 ile kullanılabilir ve Code 128 emülasyon modlarını kodlar. İkinci konumdaki FNC1'i 908 ve 909 modlarında kodlayabilir, ayrıca sadece tanınan MicroPdf417'nin Code 128 olarak yorumlanabileceğini belirten 910 ve 911'i de kodlayabilir.

```csharp
public bool IsCode128Emulation { get; set; }
```

## Örnekler

Bu örnekler, ikinci konumdaki FNC1 ile ve olmadan Code 128 emülasyon modlarının nasıl kodlanacağını gösterir. Bu şekilde MicroPdf417, Code 128 barkod olarak çözülebilir

```csharp
[C#]
//MicroPdf417'yi Code 128 emülasyon modunda, ikinci konumda FNC1 ile ve "a" Uygulama Göstergesi ile kodlar, mod 908.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//MicroPdf417'yi Code 128 emülasyon modunda, ikinci konumda FNC1 ile ve "99" Uygulama Göstergesi ile kodlar, mod 909.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "99\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//MicroPdf417'yi Code 128 emülasyon modunda, 910, 911 modlarıyla kodlar
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
```

### Ayrıca Bakınız

* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


