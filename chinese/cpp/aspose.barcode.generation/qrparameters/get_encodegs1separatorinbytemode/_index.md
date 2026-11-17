---
title: "method"
linktitle: "get_EncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode for C++ API 参考"
description: "如何在 C++ 中使用 Aspose::BarCode::Generation::QrParameters 类的 get_EncodeGS1SeparatorInByteMode 方法。"
type: docs
weight: 1700
url: /zh/cpp/aspose.barcode.generation/qrparameters/get_encodegs1separatorinbytemode/
---
## QrParameters::get_EncodeGS1SeparatorInByteMode method




```cpp
bool Aspose::BarCode::Generation::QrParameters::get_EncodeGS1SeparatorInByteMode() const
```

## 备注


获取一个值，指示是否应在 QR 和 RectMicroQR 条码中以字节模式编码 GS1 特殊字符。

如果为 false，则根据 QR 规范，GS1 分隔符可能在字母数字模式下编码为 ''。

如果为 true，GS1 组分隔符将以字节模式编码为 0x1D 字符，且 '' 字符也以字节模式编码以保留为数据。

此选项可能提升与期望字节级 GS1 组分隔符的解码器的兼容性，并防止 '' 数据字符被解释为 GS1 分隔符。
## 另见

* Class [QrParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
