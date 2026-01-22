---
title: Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext class
linktitle: MaxiCodeStandardCodetext
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext class. Class for encoding and decoding MaxiCode codetext for modes 4, 5 and 6 in C++.'
type: docs
weight: 1800
url: /cpp/aspose.barcode.complexbarcode/maxicodestandardcodetext/
---
## MaxiCodeStandardCodetext class


Class for encoding and decoding MaxiCode codetext for modes 4, 5 and 6.

```cpp
class MaxiCodeStandardCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Returns a value indicating whether this instance is equal to a specified [MaxiCodeStandardCodetext](./) value. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() | Gets ECI encoding. Used when MaxiCodeEncodeMode is Auto. Default value: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Gets a MaxiCode encode mode. Default value: Auto. |
| [get_MaxiCodeEncodeMode](../maxicodecodetext/get_maxicodeencodemode/)() | Gets a MaxiCode encode mode. Default value: Auto. |
| [get_Message](./get_message/)() const | Gets message. |
| [get_Mode](./get_mode/)() | Gets MaxiCode mode. Standard codetext can be used only with modes 4, 5 and 6. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Gets barcode type. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Constructs codetext |
| [GetHashCode](./gethashcode/)() const override | Returns the hash code for this instance. |
| [GetMode](./getmode/)() const override | Gets MaxiCode mode. |
| [InitFromString](./initfromstring/)(System::String) override | Initializes instance from constructed codetext. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/)() |  |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Aspose::BarCode::Generation::ECIEncodings) | Sets ECI encoding. Used when MaxiCodeEncodeMode is Auto. Default value: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Aspose::BarCode::Generation::MaxiCodeEncodeMode) | Sets a MaxiCode encode mode. Default value: Auto. |
| [set_MaxiCodeEncodeMode](../maxicodecodetext/set_maxicodeencodemode/)(Aspose::BarCode::Generation::MaxiCodeEncodeMode) | Sets a MaxiCode encode mode. Default value: Auto. |
| [set_Message](./set_message/)(System::String) | Sets message. |
| [set_Mode](./set_mode/)(Aspose::BarCode::Generation::MaxiCodeMode) | Sets MaxiCode mode. Standard codetext can be used only with modes 4, 5 and 6. |
## Remarks


//Mode 4 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode4; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //Mode 5 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode5; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //Mode 6 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode6; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } 
## See Also

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
