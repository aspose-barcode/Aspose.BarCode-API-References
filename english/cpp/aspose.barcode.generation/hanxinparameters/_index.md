---
title: Aspose::BarCode::Generation::HanXinParameters class
linktitle: HanXinParameters
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::Generation::HanXinParameters class. Han Xin parameters in C++.'
type: docs
weight: 2700
url: /cpp/aspose.barcode.generation/hanxinparameters/
---
## HanXinParameters class


Han Xin parameters.

```cpp
class HanXinParameters : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation contains all well known charset encodings. |
| [get_EncodeMode](./get_encodemode/)() const | HanXin encoding mode. Default value: EncodeMode.Mixed. |
| [get_ErrorLevel](./get_errorlevel/)() const | Level of Reed-Solomon error correction for Han Xin barcode. From low to high: L1, L2, L3, L4. see ErrorLevel. |
| [get_HanXinECIEncoding](./get_hanxineciencoding/)() | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation contains all well known charset encodings. |
| [get_HanXinEncodeMode](./get_hanxinencodemode/)() | HanXin encoding mode. Default value: EncodeMode.Mixed. |
| [get_HanXinErrorLevel](./get_hanxinerrorlevel/)() | Level of Reed-Solomon error correction for Han Xin barcode. From low to high: L1, L2, L3, L4. see ErrorLevel. |
| [get_HanXinVersion](./get_hanxinversion/)() | Version of HanXin Code. From Version01 to Version84 for Han Xin code. Default value is [Version.Auto](../aztecencodemode/). |
| [get_Version](./get_version/)() const | Version of HanXin Code. From Version01 to Version84 for Han Xin code. Default value is [Version.Auto](../aztecencodemode/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation contains all well known charset encodings. |
| [set_EncodeMode](./set_encodemode/)(Aspose::BarCode::Generation::HanXinEncodeMode) | HanXin encoding mode. Default value: EncodeMode.Mixed. |
| [set_ErrorLevel](./set_errorlevel/)(Aspose::BarCode::Generation::HanXinErrorLevel) | Level of Reed-Solomon error correction for Han Xin barcode. From low to high: L1, L2, L3, L4. see ErrorLevel. |
| [set_Version](./set_version/)(Aspose::BarCode::Generation::HanXinVersion) | Version of HanXin Code. From Version01 to Version84 for Han Xin code. Default value is [Version.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Returns a human-readable string representation of this [HanXinParameters](./). |
## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
