---
title: "Aspose::BarCode::Generation::Unit класс"
linktitle: "Unit"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::Generation::Unit класс. Указывает значение размера в разных единицах (Pixel, Inches и т.д.) на C++."
type: docs
weight: 5000
url: /ru/cpp/aspose.barcode.generation/unit/
---
## Unit class


Указывает значение размера в разных единицах (Pixel, Inches и т.д.).

```cpp
class Unit : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Определяет, имеют ли этот экземпляр и указанный объект, который также должен быть объектом [Unit](./), одинаковое значение. |
| [get_Document](./get_document/)() | Получает значение размера в единицах документа. |
| [get_Inches](./get_inches/)() | Получает значение размера в дюймах. |
| [get_Millimeters](./get_millimeters/)() | Получает значение размера в миллиметрах. |
| [get_Pixels](./get_pixels/)() | Получает значение размера в пикселях. |
| [get_Point](./get_point/)() | Получает значение размера в пунктах. |
| [get_Resolution](./get_resolution/)() const | Resolution |
| [GetHashCode](./gethashcode/)() const override | Возвращает хеш‑код этого объекта. |
| [set_Document](./set_document/)(float) | Устанавливает значение размера в единицах документа. |
| [set_Inches](./set_inches/)(float) | Устанавливает значение размера в дюймах. |
| [set_Millimeters](./set_millimeters/)(float) | Устанавливает значение размера в миллиметрах. |
| [set_Pixels](./set_pixels/)(float) | Устанавливает значение размера в пикселях. |
| [set_Point](./set_point/)(float) | Устанавливает значение размера в пунктах. |
| [ToString](./tostring/)() const override | Возвращает человекочитаемое строковое представление этого [Unit](./). |
## Примечания


Этот пример показывает, как создать и сохранить изображение [BarCode](../../aspose.barcode/).
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
