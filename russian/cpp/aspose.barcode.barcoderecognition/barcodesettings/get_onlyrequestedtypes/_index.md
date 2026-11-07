---
title: "method"
linktitle: "get_OnlyRequestedTypes"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Возвращает только типы штрихкодов, явно указанные для распознавания. Когда включено, распознанные штрихкоды других совместимых или эквивалентных типов отфильтровываются. Значение по умолчанию — false в C++."
type: docs
weight: 500
url: /ru/cpp/aspose.barcode.barcoderecognition/barcodesettings/get_onlyrequestedtypes/
---
## BarcodeSettings::get_OnlyRequestedTypes method


Возвращает только типы штрихкодов, явно указанные для распознавания. При включении распознанные штрихкоды других совместимых или эквивалентных типов отфильтровываются. Значение по умолчанию — false.

```cpp
bool Aspose::BarCode::BarCodeRecognition::BarcodeSettings::get_OnlyRequestedTypes() const
```

## Примечания


Этот пример показывает, как ограничить результаты распознавания только запрошенными типами штрихкодов
```cpp
[C#]
//создать штрихкод EAN13
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//распознавать только штрихкоды UPCA (нет результатов, потому что источник — EAN13)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//распознавать совместимые типы: EAN13, UPCA, ISSN, ISMN, ISBN (EAN13 будет возвращён как эквивалент UPCA)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```


Возвращает только типы штрихкодов, явно указанные для распознавания. Значение по умолчанию — false.
## См. также

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
