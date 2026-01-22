---
title: Aspose::BarCode::BarCodeRecognition::BarCodeResult class
linktitle: BarCodeResult
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::BarCodeResult class. Stores recognized barcode data like SingleDecodeType type, System::String codetext, BarCodeRegionParameters region and other parameters in C++.'
type: docs
weight: 700
url: /cpp/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class


Stores recognized barcode data like [SingleDecodeType](../singledecodetype/) type, **System::String** codetext, [BarCodeRegionParameters](../barcoderegionparameters/) region and other parameters

```cpp
class BarCodeResult : public System::ICloneable,
                      public System::IEquatable<System::SharedPtr<Aspose::BarCode::BarCodeRecognition::BarCodeResult>>
```

## Methods

| Method | Description |
| --- | --- |
| [BarCodeResult](./barcoderesult/)(System::SharedPtr\<BarCodeResult\>) | Creates a a copy of the [BarCodeResult](./) class. |
| [Clone](./clone/)() override | Creates a copy of [BarCodeResult](./) class. |
| [Equals](./equals/)(System::SharedPtr\<BarCodeResult\>) override | Returns a value indicating whether this instance is equal to a specified [BarCodeResult](./) value. |
| [get_CodeBytes](./get_codebytes/)() | Gets the encoded code bytes |
| [get_CodeText](./get_codetext/)() | Gets the code text |
| [get_CodeType](./get_codetype/)() | Gets the barcode type |
| [get_CodeTypeName](./get_codetypename/)() | Gets the name of the barcode type |
| [get_Confidence](./get_confidence/)() | Gets recognition confidence level of the recognized barcode |
| [get_Extended](./get_extended/)() | Gets extended parameters of recognized barcode |
| [get_ReadingQuality](./get_readingquality/)() | Gets the reading quality. Works for 1D and postal barcodes. |
| [get_Region](./get_region/)() | Gets the barcode region |
| [GetCodeText](./getcodetext/)(System::SharedPtr\<System::Text::Encoding\>) | Gets the code text with encoding. |
| [GetHashCode](./gethashcode/)() const override | Returns the hash code for this instance. |
| [ToString](./tostring/)() const override | Returns a human-readable string representation of this [BarCodeResult](./). |
## Remarks


This sample shows how to obtain [BarCodeResult](./). 
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
    Next
End Using
```

## See Also

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
