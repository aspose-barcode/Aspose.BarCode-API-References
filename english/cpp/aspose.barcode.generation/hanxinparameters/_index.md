---
title: Aspose::BarCode::Generation::HanXinParameters class
linktitle: HanXinParameters
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::Generation::HanXinParameters class. Han Xin parameters in C++.'
type: docs
weight: 2600
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
| [get_HanXinECIEncoding](./get_hanxineciencoding/)() const | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. |
| [get_HanXinEncodeMode](./get_hanxinencodemode/)() const | HanXin encoding mode. Default value: HanXinEncodeMode.Mixed. |
| [get_HanXinErrorLevel](./get_hanxinerrorlevel/)() const | Level of Reed-Solomon error correction for Han Xin barcode. From low to high: L1, L2, L3, L4. see HanXinErrorLevel. |
| [get_HanXinVersion](./get_hanxinversion/)() const | Version of HanXin Code. From Version01 to Version84 for Han Xin code. Default value is [HanXinVersion.Auto](../hanxinversion/). |
| [set_HanXinECIEncoding](./set_hanxineciencoding/)(ECIEncodings) | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. |
| [set_HanXinEncodeMode](./set_hanxinencodemode/)(Aspose::BarCode::Generation::HanXinEncodeMode) | HanXin encoding mode. Default value: HanXinEncodeMode.Mixed. |
| [set_HanXinErrorLevel](./set_hanxinerrorlevel/)(Aspose::BarCode::Generation::HanXinErrorLevel) | Level of Reed-Solomon error correction for Han Xin barcode. From low to high: L1, L2, L3, L4. see HanXinErrorLevel. |
| [set_HanXinVersion](./set_hanxinversion/)(Aspose::BarCode::Generation::HanXinVersion) | Version of HanXin Code. From Version01 to Version84 for Han Xin code. Default value is [HanXinVersion.Auto](../hanxinversion/). |
| [ToString](./tostring/)() const override | Returns a human-readable string representation of this [HanXinParameters](./). |
## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
