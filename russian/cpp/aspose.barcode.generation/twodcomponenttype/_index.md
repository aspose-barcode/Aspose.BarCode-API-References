---
title: "enum"
linktitle: "TwoDComponentType"
second_title: "Aspose.BarCode для C++ справочник API"
description: " enum. Тип 2D компонента в C++."
type: docs
weight: 8700
url: /ru/cpp/aspose.barcode.generation/twodcomponenttype/
---
## TwoDComponentType enum


Тип 2D‑компонента

```cpp
enum class TwoDComponentType
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Авто | 0 | Автоматический выбор типа 2D компонента |
| CC_A | 1 | Тип CC-A 2D компонента. Это структурный вариант MicroPDF417 |
| CC_B | 2 | Тип CC-B 2D компонента. Это символ MicroPDF417. |
| CC_C | 3 | Тип CC-C 2D компонента. Это символ PDF417. |

## Примечания


Этот пример показывает, как создать и сохранить изображение GS1 Composite Bar. Обратите внимание, что 1D codetext и 2D codetext разделены символом '/'
```cpp
[C#]
var codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
    using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
    {
    generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
    generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;

    // Соотношение сторон 2D компонента
    generator.Parameters.Barcode.Pdf417.AspectRatio = 3;

    // X-Размер 1D и 2D компонентов
    generator.Parameters.Barcode.XDimension.Pixels = 3;

    // Высота 1D компонента
    generator.Parameters.Barcode.BarHeight.Pixels = 100;

    generator.Save("test.png");
}
```

## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
