---
title:  method
linktitle: set_OnlyRequestedTypes
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Returns only barcode types explicitly specified for recognition. When enabled, recognized barcodes of other compatible or equivalent types are filtered out. Default value is false in C++.'
type: docs
weight: 600
url: /cpp/aspose.barcode.barcoderecognition/barcodesettings/set_onlyrequestedtypes/
---
## BarcodeSettings::set_OnlyRequestedTypes method


Returns only barcode types explicitly specified for recognition. When enabled, recognized barcodes of other compatible or equivalent types are filtered out. Default value is false.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarcodeSettings::set_OnlyRequestedTypes(bool value)
```

## Remarks


This sample shows how to restrict recognition results to requested barcode types only 
```cpp
[C#]
//generate EAN13 barcode
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//recognize only UPCA barcodes (no results, because source is EAN13)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN (EAN13 will be returned as UPCA-equivalent)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```


Returns only barcode types explicitly specified for recognition. Default value is false.
## See Also

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
