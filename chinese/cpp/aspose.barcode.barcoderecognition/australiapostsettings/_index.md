---
title: "Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings 类"
linktitle: "AustraliaPostSettings"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings 类。AustraliaPost 解码参数。包含对 C++ 中 AustraliaPost 符号学已识别数据产生影响的参数。"
type: docs
weight: 200
url: /zh/cpp/aspose.barcode.barcoderecognition/australiapostsettings/
---
## AustraliaPostSettings class


AustraliaPost 解码参数。包含对 AustraliaPost 符号系统识别数据产生影响的参数。

```cpp
class AustraliaPostSettings : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_CustomerInformationDecoder](./get_customerinformationdecoder/)() const | 用于 AustraliaPost 符号学的客户信息字段解码的公共接口。 |
| [get_CustomerInformationInterpretingType](./get_customerinformationinterpretingtype/)() const | 获取 AustralianPost 客户信息的解释类型，默认值为 [BarCode.Default](../checksumvalidation/)，即 [CustomerInformationInterpretingType.Other](../../aspose.barcode/customerinformationinterpretingtype/)。 |
| [get_IgnoreEndingFillingPatternsForCTable](./get_ignoreendingfillingpatternsforctable/)() const | 强制 AustraliaPost 解码器在使用 CTable 方法解码时忽略客户信息字段中最后的填充模式的标志。CTable 编码方法在编码表中没有任何间隙，填充模式序列 \"333\" 被解码为字母 \"z\"。 |
| [set_CustomerInformationDecoder](./set_customerinformationdecoder/)(System::SharedPtr\<AustraliaPostCustomerInformationDecoder\>) | 用于 AustraliaPost 符号学的客户信息字段解码的公共接口。 |
| [set_CustomerInformationInterpretingType](./set_customerinformationinterpretingtype/)(Aspose::BarCode::CustomerInformationInterpretingType) | 设置 AustralianPost 客户信息的解释类型，默认值为 [BarCode.Default](../checksumvalidation/)，即 [CustomerInformationInterpretingType.Other](../../aspose.barcode/customerinformationinterpretingtype/)。 |
| [set_IgnoreEndingFillingPatternsForCTable](./set_ignoreendingfillingpatternsforctable/)(bool) | 强制 AustraliaPost 解码器在使用 CTable 方法解码时忽略客户信息字段中最后的填充模式的标志。CTable 编码方法在编码表中没有任何间隙，填充模式序列 \"333\" 被解码为字母 \"z\"。 |
## 另见

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
