---
title: Aspose::BarCode::ComplexBarcode::HIBCPASCodetext class
linktitle: HIBCPASCodetext
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::ComplexBarcode::HIBCPASCodetext class. Class for encoding and decoding the text embedded in the HIBC PAS code in C++.'
type: docs
weight: 900
url: /cpp/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class


Class for encoding and decoding the text embedded in the HIBC PAS code.

```cpp
class HIBCPASCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Description |
| --- | --- |
| [AddRecord](./addrecord/)(HIBCPASDataType, System::String) | Adds new record |
| [AddRecord](./addrecord/)(System::SharedPtr\<HIBCPASRecord\>) | Adds new record |
| [Clear](./clear/)() | Clears records list |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Returns a value indicating whether this instance is equal to a specified [HIBCPASCodetext](./) value. |
| [get_BarcodeType](./get_barcodetype/)() | Gets barcode type. HIBC PAS codetext can be encoded using HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS and HIBCQRPAS encode types. Default value: HIBCCode39PAS. |
| [get_DataLocation](./get_datalocation/)() const | Identifies data location. |
| [GetBarcodeType](./getbarcodetype/)() override | Gets barcode type. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Constructs codetext |
| [GetHashCode](./gethashcode/)() const override | Returns the hash code for this instance. |
| [GetRecords](./getrecords/)() | Gets records list |
| [HIBCPASCodetext](./hibcpascodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Initializes instance from constructed codetext. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Aspose::BarCode::Generation::BaseEncodeType\>) | Sets barcode type. HIBC PAS codetext can be encoded using HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS and HIBCQRPAS encode types. Default value: HIBCCode39PAS. |
| [set_DataLocation](./set_datalocation/)(HIBCPASDataLocation) | Identifies data location. |
## Remarks


This sample shows how to encode and decode HIBC PAS using [HIBCPASCodetext](./). 
```cpp
[C#]
HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
complexCodetext.DataLocation = HIBCPASDataLocation.Patient;
complexCodetext.AddRecord(HIBCPASDataType.LabelerIdentificationCode, "A123");
complexCodetext.AddRecord(HIBCPASDataType.ManufacturerSerialNumber, "SERIAL123");
complexCodetext.BarcodeType = EncodeTypes.HIBCDataMatrixPAS;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.HIBCDataMatrixPAS))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText; 
        HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.TryDecodeHIBCPAS(codetext);
        Console.WriteLine("Data location: {0}", readCodetext.DataLocation);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[0].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[0].Data);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[1].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[1].Data);

    }
}
```

## See Also

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
