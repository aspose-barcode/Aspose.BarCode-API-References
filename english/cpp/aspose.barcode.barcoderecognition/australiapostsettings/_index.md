---
title: Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings class
linktitle: AustraliaPostSettings
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings class. AustraliaPost decoding parameters. Contains parameters which make influence on recognized data of AustraliaPost symbology in C++.'
type: docs
weight: 200
url: /cpp/aspose.barcode.barcoderecognition/australiapostsettings/
---
## AustraliaPostSettings class


AustraliaPost decoding parameters. Contains parameters which make influence on recognized data of AustraliaPost symbology.

```cpp
class AustraliaPostSettings : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_CustomerInformationDecoder](./get_customerinformationdecoder/)() | Public interface for Customer Information Field decoding which is used in AustraliaPost symbology. |
| [get_CustomerInformationInterpretingType](./get_customerinformationinterpretingtype/)() | Gets the Interpreting Type for the Customer Information of AustralianPost [BarCode.Default](../checksumvalidation/) is [CustomerInformationInterpretingType.Other](../../aspose.barcode/customerinformationinterpretingtype/). |
| [get_IgnoreEndingFillingPatternsForCTable](./get_ignoreendingfillingpatternsforctable/)() | The flag which force AustraliaPost decoder to ignore last filling patterns in Customer Information Field during decoding as CTable method. CTable encoding method does not have any gaps in encoding table and sequnce "333" of filling paterns is decoded as letter "z". |
| [set_CustomerInformationDecoder](./set_customerinformationdecoder/)(System::SharedPtr\<AustraliaPostCustomerInformationDecoder\>) | Public interface for Customer Information Field decoding which is used in AustraliaPost symbology. |
| [set_CustomerInformationInterpretingType](./set_customerinformationinterpretingtype/)(Aspose::BarCode::CustomerInformationInterpretingType) | Sets the Interpreting Type for the Customer Information of AustralianPost [BarCode.Default](../checksumvalidation/) is [CustomerInformationInterpretingType.Other](../../aspose.barcode/customerinformationinterpretingtype/). |
| [set_IgnoreEndingFillingPatternsForCTable](./set_ignoreendingfillingpatternsforctable/)(bool) | The flag which force AustraliaPost decoder to ignore last filling patterns in Customer Information Field during decoding as CTable method. CTable encoding method does not have any gaps in encoding table and sequnce "333" of filling paterns is decoded as letter "z". |
## See Also

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
