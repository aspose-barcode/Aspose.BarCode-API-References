---
title: "Aspose::BarCode::BarCodeRecognition::BarcodeSettings 类"
linktitle: "BarcodeSettings"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::BarCodeRecognition::BarcodeSettings 类。主要的条形码解码参数。包含对 C++ 中识别数据产生影响的参数。"
type: docs
weight: 800
url: /zh/cpp/aspose.barcode.barcoderecognition/barcodesettings/
---
## BarcodeSettings class


主要的 [BarCode](../../aspose.barcode/) 解码参数。包含影响识别数据的参数。

```cpp
class BarcodeSettings : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_AustraliaPost](./get_australiapost/)() const | 获取 AustraliaPost 解码参数 |
| [get_CalculateSymbolQuality](./get_calculatesymbolquality/)() const | 获取一个值，指示在识别期间是否计算条形码符号质量。 |
| [get_ChecksumValidation](./get_checksumvalidation/)() const |  |
| [get_DetectEncoding](./get_detectencoding/)() const | 强制引擎检测 Unicode 代码集的代码文本编码的标志。默认值为 true。 |
| [get_OnlyRequestedTypes](./get_onlyrequestedtypes/)() const | 仅返回明确指定用于识别的条形码类型。启用后，其他兼容或等效类型的已识别条形码将被过滤掉。默认值为 false。 |
| [get_StripFNC](./get_stripfnc/)() const | 从代码文本中剥离 FNC1、FNC2、FNC3 字符。默认值为 false。 |
| [set_CalculateSymbolQuality](./set_calculatesymbolquality/)(bool) | 设置一个值，指示在识别期间是否计算条形码符号质量。 |
| [set_ChecksumValidation](./set_checksumvalidation/)(Aspose::BarCode::BarCodeRecognition::ChecksumValidation) |  |
| [set_DetectEncoding](./set_detectencoding/)(bool) | 强制引擎检测 Unicode 代码集的代码文本编码的标志。默认值为 true。 |
| [set_OnlyRequestedTypes](./set_onlyrequestedtypes/)(bool) | 仅返回明确指定用于识别的条形码类型。启用后，其他兼容或等效类型的已识别条形码将被过滤掉。默认值为 false。 |
| [set_StripFNC](./set_stripfnc/)(bool) | 从代码文本中剥离 FNC1、FNC2、FNC3 字符。默认值为 false。 |
## 另见

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
