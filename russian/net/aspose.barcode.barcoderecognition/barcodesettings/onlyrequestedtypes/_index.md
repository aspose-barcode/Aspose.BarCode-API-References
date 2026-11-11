---
title: "BarcodeSettings.OnlyRequestedTypes"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Свойство BarcodeSettings. Возвращает только типы штрихкодов, явно указанные для распознавания. Когда включено, распознанные штрихкоды других совместимых или эквивалентных типов отфильтровываются. Значение по умолчанию — ложь"
type: docs
weight: 50
url: /ru/net/aspose.barcode.barcoderecognition/barcodesettings/onlyrequestedtypes/
---
## BarcodeSettings.OnlyRequestedTypes property

Возвращает только типы штрихкодов, явно указанные для распознавания. Когда включено, распознанные штрихкоды других совместимых или эквивалентных типов отфильтровываются. Значение по умолчанию — ложь.

```csharp
public bool OnlyRequestedTypes { get; set; }
```

### Property Value

Возвращает только типы штрихкодов, явно указанные для распознавания. Значение по умолчанию — ложь.

## Примеры

Этот пример показывает, как ограничить результаты распознавания только запрошенными типами штрихкодов

```csharp
[C#]
//создать штрихкод EAN13
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//распознавать только штрихкоды UPCA (результатов нет, потому что источник — EAN13)
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

### См. также

* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


