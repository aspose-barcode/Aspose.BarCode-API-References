---
title: "enum"
linktitle: "AztecSymbolMode"
second_title: "Aspose.BarCode для C++ справочник API"
description: " enum. Указывает режим символов Aztec в C++."
type: docs
weight: 5400
url: /ru/cpp/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enum


Указывает режим символов Aztec.

```cpp
enum class AztecSymbolMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Авто | 0 | Указывает автоматически выбирать лучший символ (Compact или Full-range) для Aztec. Это значение по умолчанию. |
| Compact | 1 | Указывает компактный символ для Aztec. Компактный символ Aztec допускает только 1, 2, 3 или 4 слоя. |
| FullRange | 2 | Указывает символ Full-range для Aztec. Символ Aztec Full-range допускает от 1 до 32 слоёв. |
| Rune | 3 | Указывает символ Rune для Aztec. Rune Aztec — это серия небольших, но отличимых машинно‑читаемых меток. Допускаются только числовые значения от 0 до 255. |

## Примечания


Этот пример показывает, как изменить режим символов Aztec и сохранить изображение [BarCode](../../aspose.barcode/).
```cpp
[C#]
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.Aztec))
{
    generator.CodeText = "125";
    generator.Parameters.Barcode.Aztec.AztecSymbolMode = AztecSymbolMode.Rune;
    generator.Save("test.png");
}
    [VB.NET]
    Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.Aztec)
        generator.CodeText = "125"
        generator.Parameters.Barcode.Aztec.AztecSymbolMode = AztecSymbolMode.Rune
        generator.Save("test.png")
    End Using
```

## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
