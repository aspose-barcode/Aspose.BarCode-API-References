---
title: Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters class
linktitle: DotCodeExtendedParameters
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters class. Stores special data of DotCode recognized barcode in C++.'
type: docs
weight: 1900
url: /cpp/aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
## DotCodeExtendedParameters class


Stores special data of DotCode recognized barcode

```cpp
class DotCodeExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Description |
| --- | --- |
| [get_DotCodeIsReaderInitialization](./get_dotcodeisreaderinitialization/)() | Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. Default value is false. |
| [get_DotCodeStructuredAppendModeBarcodeId](./get_dotcodestructuredappendmodebarcodeid/)() | Gets the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1. |
| [get_DotCodeStructuredAppendModeBarcodesCount](./get_dotcodestructuredappendmodebarcodescount/)() | Gets the DotCode structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() | **Tests** whether all parameters has only default values |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() | Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. Default value is false. |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() | Gets the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1. |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() | Gets the DotCode structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35. |
| [GetHashCode](./gethashcode/)() const override | Returns the hash code for this instance. |
| [ToString](./tostring/)() const override | Returns a human-readable string representation of this [DotCodeExtendedParameters](./). |
## Remarks


This sample shows how to get DotCode raw values 
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DotCode))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DotCode barcode ID: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodeId);
        Console.WriteLine("DotCode barcodes count: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodesCount);
    }
}
```

## See Also

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
