---
title: "Aspose::BarCode::Generation::FontUnit 类"
linktitle: "FontUnit"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::Generation::FontUnit 类。定义文本的特定格式，包括字体、大小和样式属性，其中大小以 Unit 值属性表示（C++）。"
type: docs
weight: 2500
url: /zh/cpp/aspose.barcode.generation/fontunit/
---
## FontUnit class


定义文本的特定格式，包括字体、大小和样式属性，其中大小以 [Unit](../unit/) 值属性表示。

```cpp
class FontUnit : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_FamilyName](./get_familyname/)() const | 获取此 Font 的字体名称。 |
| [get_Size](./get_size/)() const | 获取此 [FontUnit](./) 在 [Unit](../unit/) 值中的大小。 |
| [get_Style](./get_style/)() const | 获取此 [FontUnit](./) 的样式信息。 |
| [set_FamilyName](./set_familyname/)(System::String) | 设置此 Font 的字体名称。 |
| [set_Style](./set_style/)(System::Drawing::FontStyle) | 设置此 [FontUnit](./) 的样式信息。 |
## 备注


此示例展示了如何创建并保存 [BarCode](../../aspose.barcode/) 图像。
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
