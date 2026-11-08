---
title: "metot"
linktitle: "set_IsCode128Emulation"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " method. Yalnızca MicroPdf417 ile kullanılabilir ve Code 128 emülasyon modlarını kodlar. İkinci konumdaki FNC1'i mod 908 ve 909'da kodlayabilir, ayrıca 910 ve 911'i de kodlayabilir; bu sadece tanınan MicroPdf417'nin Code 128 olarak yorumlanabileceğini gösterir C++ içinde."
type: docs
weight: 4400
url: /tr/cpp/aspose.barcode.generation/pdf417parameters/set_iscode128emulation/
---
## Pdf417Parameters::set_IsCode128Emulation method


Sadece MicroPdf417 ile kullanılabilir ve Code 128 emülasyon modlarını kodlar. İkinci konumdaki FNC1'i 908 ve 909 modlarında kodlayabilir, ayrıca 910 ve 911'i kodlayabilir; bu sadece tanınan MicroPdf417'nin Code 128 olarak yorumlanabileceğini gösterir.

```cpp
void Aspose::BarCode::Generation::Pdf417Parameters::set_IsCode128Emulation(bool value)
```

## Açıklamalar


Bu örnekler, ikinci konumda FNC1 ile ve olmadan Code 128 emülasyon modlarını nasıl kodlayacağını gösterir. Bu şekilde MicroPdf417, Code 128 barkod olarak çözülebilir.
```cpp
[C#]
//MicroPdf417'yi ikinci konumda FNC1 ve Uygulama Göstergesi "a" ile Code 128 emülasyon modunda, mod 908 olarak kodlar.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//MicroPdf417'yi ikinci konumda FNC1 ve Uygulama Göstergesi "99" ile Code 128 emülasyon modunda, mod 909 olarak kodlar.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "99\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//MicroPdf417'yi Code 128 emülasyon modunda, modlar 910, 911 olarak kodlar.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
```

## Ayrıca Bakınız

* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
