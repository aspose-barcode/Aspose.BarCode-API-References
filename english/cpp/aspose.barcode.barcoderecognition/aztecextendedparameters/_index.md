---
title: Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters class
linktitle: AztecExtendedParameters
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters class. Stores special data of Aztec recognized barcode in C++.'
type: docs
weight: 300
url: /cpp/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class


Stores special data of Aztec recognized barcode

```cpp
class AztecExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Description |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() | **Tests** whether all parameters has only default values |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() | Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. Default value is false. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() | Gets the ID of the Aztec structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is 0. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() | Gets the Aztec structured append mode barcodes count. Default value is 0. Count must be a value from 1 to 26. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() | Gets the File ID of the Aztec structured append mode. Default value is empty string |
| [GetHashCode](./gethashcode/)() const override | Returns the hash code for this instance. |
| [ToString](./tostring/)() const override | Returns a human-readable string representation of this [AztecExtendedParameters](./). |
## Remarks


This sample shows how to get Aztec raw values 
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Aztec))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("Aztec barcode ID: " + result.Extended.Aztec.StructuredAppendBarcodeId);
        Console.WriteLine("Aztec barcodes count: " + result.Extended.Aztec.StructuredAppendBarcodesCount);
        Console.WriteLine("Aztec file ID: " + result.Extended.Aztec.StructuredAppendFileId);
        Console.WriteLine("Aztec is reader initialization: " + result.Extended.Aztec.IsReaderInitialization);
    }
}
```

## See Also

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
