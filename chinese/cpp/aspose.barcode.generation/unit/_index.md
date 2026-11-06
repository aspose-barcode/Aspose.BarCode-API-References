---
title: "Aspose::BarCode::Generation::Unit 类"
linktitle: "Unit"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::Generation::Unit 类。指定 C++ 中以不同单位（像素、英寸等）表示的尺寸值。"
type: docs
weight: 5000
url: /zh/cpp/aspose.barcode.generation/unit/
---
## Unit class


指定不同单位（像素、英寸等）下的尺寸值。

```cpp
class Unit : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 确定此实例和指定对象（该对象也必须是 [Unit](./) 对象）是否具有相同的值。 |
| [get_Document](./get_document/)() | 获取文档单位中的尺寸值。 |
| [get_Inches](./get_inches/)() | 获取英寸单位中的尺寸值。 |
| [get_Millimeters](./get_millimeters/)() | 获取毫米单位中的尺寸值。 |
| [get_Pixels](./get_pixels/)() | 获取像素单位中的尺寸值。 |
| [get_Point](./get_point/)() | 获取点（point）单位中的尺寸值。 |
| [get_Resolution](./get_resolution/)() const | 分辨率 |
| [GetHashCode](./gethashcode/)() const override | 返回此对象的哈希码。 |
| [set_Document](./set_document/)(float) | 设置文档单位中的尺寸值。 |
| [set_Inches](./set_inches/)(float) | 设置英寸单位中的尺寸值。 |
| [set_Millimeters](./set_millimeters/)(float) | 设置毫米单位中的尺寸值。 |
| [set_Pixels](./set_pixels/)(float) | 设置像素单位中的尺寸值。 |
| [set_Point](./set_point/)(float) | 设置点（point）单位中的尺寸值。 |
| [ToString](./tostring/)() const override | 返回此 [Unit](./) 的人类可读字符串表示。 |
## 备注


此示例展示了如何创建并保存 [BarCode](../../aspose.barcode/) 图像。
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
