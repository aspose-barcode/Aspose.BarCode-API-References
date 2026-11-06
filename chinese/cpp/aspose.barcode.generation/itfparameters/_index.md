---
title: "Aspose::BarCode::Generation::ITFParameters class"
linktitle: "ITFParameters"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::Generation::ITFParameters 类。C++ 中的 ITF 参数。"
type: docs
weight: 3300
url: /zh/cpp/aspose.barcode.generation/itfparameters/
---
## ITFParameters class


ITF 参数。

```cpp
class ITFParameters : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_BorderThickness](./get_borderthickness/)() const | 获取 ITF 边框（承载条）的厚度，单位为 [Unit](../unit/)。默认值：12pt。 |
| [get_BorderType](./get_bordertype/)() const | ITF 条形码的边框类型。默认值：[ITF14BorderType.Bar](../itf14bordertype/)。 |
| [get_QuietZoneCoef](./get_quietzonecoef/)() const | 静区在 xDimension 中的大小。默认值：10，表示如果 xDimension = 2px，则静区将为 20px。 |
| [set_BorderThickness](./set_borderthickness/)(System::SharedPtr\<Unit\>) | 设置 ITF 边框（承载条）的厚度，以 [Unit](../unit/) 为单位。默认值：12pt。 |
| [set_BorderType](./set_bordertype/)(ITF14BorderType) | ITF 条形码的边框类型。默认值：[ITF14BorderType.Bar](../itf14bordertype/)。 |
| [set_QuietZoneCoef](./set_quietzonecoef/)(int32_t) | 静区在 xDimension 中的大小。默认值：10，表示如果 xDimension = 2px，则静区将为 20px。 |
| [ToString](./tostring/)() const override | 返回此 [ITFParameters](./) 的人类可读字符串表示。 |
## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
