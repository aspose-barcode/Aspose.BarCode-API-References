---
title: BarcodeSettings.OnlyRequestedTypes
second_title: Aspose.BarCode for .NET API Reference
description: BarcodeSettings property. Returns only barcode types explicitly specified for recognition. When enabled recognized barcodes of other compatible or equivalent types are filtered out. Default value is false
type: docs
weight: 40
url: /net/aspose.barcode.barcoderecognition/barcodesettings/onlyrequestedtypes/
---
## BarcodeSettings.OnlyRequestedTypes property

Returns only barcode types explicitly specified for recognition. When enabled, recognized barcodes of other compatible or equivalent types are filtered out. Default value is false.

```csharp
public bool OnlyRequestedTypes { get; set; }
```

### Property Value

Returns only barcode types explicitly specified for recognition. Default value is false.

## Examples

This sample shows how to restrict recognition results to requested barcode types only

```csharp
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

### See Also

* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


