---
title: "Aspose::BarCode::Generation::HanXinParameters class"
linktitle: "HanXinParameters"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::Generation::HanXinParameters class. C++ 中的 Han Xin 参数。"
type: docs
weight: 2900
url: /zh/cpp/aspose.barcode.generation/hanxinparameters/
---
## HanXinParameters class


Han Xin 参数。

```cpp
class HanXinParameters : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | 扩展通道解释标识符。它用于向条码阅读器提供有关在符号中对数据进行编码所使用的参考的详细信息。当前实现包含所有已知的字符集编码。 |
| [get_EncodeMode](./get_encodemode/)() const | HanXin 编码模式。默认值：EncodeMode.Mixed。 |
| [get_ErrorLevel](./get_errorlevel/)() const | Han Xin 条码的 Reed-Solomon 错误纠正级别。从低到高：L1、L2、L3、L4。参见 ErrorLevel。 |
| [get_Version](./get_version/)() const | HanXin 码的版本。从 Version01 到 Version84。默认值是 [Version.Auto](../aztecencodemode/)。 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | 扩展通道解释标识符。它用于向条码阅读器提供有关在符号中对数据进行编码所使用的参考的详细信息。当前实现包含所有已知的字符集编码。 |
| [set_EncodeMode](./set_encodemode/)(HanXinEncodeMode) | HanXin 编码模式。默认值：EncodeMode.Mixed。 |
| [set_ErrorLevel](./set_errorlevel/)(HanXinErrorLevel) | Han Xin 条码的 Reed-Solomon 错误纠正级别。从低到高：L1、L2、L3、L4。参见 ErrorLevel。 |
| [set_Version](./set_version/)(HanXinVersion) | HanXin 码的版本。从 Version01 到 Version84。默认值是 [Version.Auto](../aztecencodemode/)。 |
| [ToString](./tostring/)() const override | 返回此 [HanXinParameters](./) 的人类可读字符串表示。 |
## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
