---
title: Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext class
linktitle: MaxiCodeCodetext
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext class. Base class for encoding and decoding the text embedded in the MaxiCode code in C++.'
type: docs
weight: 1400
url: /cpp/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class


Base class for encoding and decoding the text embedded in the MaxiCode code.

```cpp
class MaxiCodeCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Description |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() | Gets ECI encoding. Used when MaxiCodeEncodeMode is Auto. Default value: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Gets a MaxiCode encode mode. Default value: Auto. |
| [get_MaxiCodeEncodeMode](./get_maxicodeencodemode/)() | Gets a MaxiCode encode mode. Default value: Auto. |
| [GetBarcodeType](./getbarcodetype/)() override | Gets barcode type. |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | Constructs codetext |
| virtual [GetMode](./getmode/)() const | Gets MaxiCode mode. |
| virtual [InitFromString](./initfromstring/)(System::String) | Initializes instance from constructed codetext. |
| [MaxiCodeCodetext](./maxicodecodetext/)() |  |
| [set_ECIEncoding](./set_eciencoding/)(Aspose::BarCode::Generation::ECIEncodings) | Sets ECI encoding. Used when MaxiCodeEncodeMode is Auto. Default value: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(Aspose::BarCode::Generation::MaxiCodeEncodeMode) | Sets a MaxiCode encode mode. Default value: Auto. |
| [set_MaxiCodeEncodeMode](./set_maxicodeencodemode/)(Aspose::BarCode::Generation::MaxiCodeEncodeMode) | Sets a MaxiCode encode mode. Default value: Auto. |
## Remarks


This sample shows how to decode raw MaxiCode codetext to [MaxiCodeCodetext](./) instance. 
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("MaxiCode mode: " + resultMaxiCodeCodetext.GetMode());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

## See Also

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
