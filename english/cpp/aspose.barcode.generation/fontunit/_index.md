---
title: Aspose::BarCode::Generation::FontUnit class
linktitle: FontUnit
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::Generation::FontUnit class. Defines a particular format for text, including font face, size, and style attributes where size in Unit value property in C++.'
type: docs
weight: 2400
url: /cpp/aspose.barcode.generation/fontunit/
---
## FontUnit class


Defines a particular format for text, including font face, size, and style attributes where size in [Unit](../unit/) value property.

```cpp
class FontUnit : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_FamilyName](./get_familyname/)() | Gets the face name of this Font. |
| [get_Size](./get_size/)() | Gets size of this [FontUnit](./) in [Unit](../unit/) value. |
| [get_Style](./get_style/)() | Gets style information for this [FontUnit](./). |
| [set_FamilyName](./set_familyname/)(System::String) | Sets the face name of this Font. |
| [set_Style](./set_style/)(System::Drawing::FontStyle) | Sets style information for this [FontUnit](./). |
## Remarks


This sample shows how to create and save a [BarCode](../../aspose.barcode/) image. 
```cpp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
