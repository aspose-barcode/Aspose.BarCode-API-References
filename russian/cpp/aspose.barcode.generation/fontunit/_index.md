---
title: "Aspose::BarCode::Generation::FontUnit class"
linktitle: "FontUnit"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::Generation::FontUnit class. Определяет конкретный формат текста, включая тип шрифта, размер и атрибуты стиля, где размер задаётся в свойстве Unit value в C++."
type: docs
weight: 2500
url: /ru/cpp/aspose.barcode.generation/fontunit/
---
## FontUnit class


Определяет конкретный формат текста, включая тип шрифта, размер и атрибуты стиля, где размер задаётся в свойстве значения [Unit](../unit/).

```cpp
class FontUnit : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [get_FamilyName](./get_familyname/)() const | Получает название гарнитуры этого Font. |
| [get_Size](./get_size/)() const | Получает размер этого [FontUnit](./) в значении [Unit](../unit/). |
| [get_Style](./get_style/)() const | Получает информацию о стиле для этого [FontUnit](./). |
| [set_FamilyName](./set_familyname/)(System::String) | Устанавливает имя гарнитуры этого шрифта. |
| [set_Style](./set_style/)(System::Drawing::FontStyle) | Устанавливает информацию о стиле для этого [FontUnit](./). |
## Примечания


Этот пример показывает, как создать и сохранить изображение [BarCode](../../aspose.barcode/).
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
