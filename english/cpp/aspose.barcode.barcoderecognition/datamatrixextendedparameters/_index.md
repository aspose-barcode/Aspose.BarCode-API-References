---
title: Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters class
linktitle: DataMatrixExtendedParameters
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters class. Stores special data of DataMatrix recognized barcode in C++.'
type: docs
weight: 1500
url: /cpp/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class


Stores special data of DataMatrix recognized barcode

```cpp
class DataMatrixExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Description |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() | **Tests** whether all parameters has only default values |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() | Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. Default value is false. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() | Gets the ID of the DataMatrix structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() | Gets the DataMatrix structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() | Gets the ID of the DataMatrix structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1. |
| [GetHashCode](./gethashcode/)() const override | Returns the hash code for this instance. |
| [ToString](./tostring/)() const override | Returns a human-readable string representation of this [DataMatrixExtendedParameters](./). |
## Remarks


This sample shows how to get DataMatrix raw values 
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DataMatrix))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DataMatrix barcode ID: " + result.Extended.DataMatrix.StructuredAppendBarcodeId);
        Console.WriteLine("DataMatrix barcodes count: " + result.Extended.DataMatrix.StructuredAppendBarcodesCount);
        Console.WriteLine("DataMatrix file ID: " + result.Extended.DataMatrix.StructuredAppendFileId);
        Console.WriteLine("DataMatrix is reader programming: " + result.Extended.DataMatrix.IsReaderProgramming);
    }
}
```

## See Also

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
