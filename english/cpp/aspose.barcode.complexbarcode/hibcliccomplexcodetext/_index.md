---
title: Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext class
linktitle: HIBCLICComplexCodetext
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext class. Base class for encoding and decoding the text embedded in the HIBC LIC code in C++.'
type: docs
weight: 600
url: /cpp/aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
## HIBCLICComplexCodetext class


Base class for encoding and decoding the text embedded in the HIBC LIC code.

```cpp
class HIBCLICComplexCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Description |
| --- | --- |
| [get_BarcodeType](./get_barcodetype/)() | Gets barcode type. HIBC LIC codetext can be encoded using HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC and HIBCQRLIC encode types. Default value: HIBCCode39LIC. |
| [GetBarcodeType](./getbarcodetype/)() override | Gets barcode type. |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | Constructs codetext |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/)() |  |
| virtual [InitFromString](./initfromstring/)(System::String) | Initializes instance from constructed codetext. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Aspose::BarCode::Generation::BaseEncodeType\>) | Sets barcode type. HIBC LIC codetext can be encoded using HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC and HIBCQRLIC encode types. Default value: HIBCCode39LIC. |
## Remarks


This sample shows how to decode raw HIBC LIC codetext to [HIBCLICComplexCodetext](./) instance. 
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.HIBCAztecLIC))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        HIBCLICComplexCodetext resultHIBCLICComplexCodetext = ComplexCodetextReader.TryDecodeHIBCLIC(result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

## See Also

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
