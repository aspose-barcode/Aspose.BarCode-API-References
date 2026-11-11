---
title: "Класс USADriveIdCodetext.SubfileProperties"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Класс Aspose.BarCode.ComplexBarcode.USADriveIdCodetextSubfileProperties. Смещения и длина свойств подфайла USA DL устанавливаются автоматически"
type: docs
weight: 840
url: /ru/net/aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
## USADriveIdCodetext.SubfileProperties class

Свойства подфайла USA DL, смещение и длина устанавливаются автоматически.

```csharp
public class SubfileProperties
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/.ctor)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Length](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/length) { get; set; } | Эти 4 байта содержат 4‑значное числовое значение, указывающее длину подфайла в байтах. Терминатор сегмента должен быть включён при расчёте длины подфайла. Терминатор сегмента = 1. Каждый подфайл должен начинаться с двухсимвольного типа Subfile, и эти два символа также должны быть включены в длину. |
| [Offset](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/offset) { get; set; } | 4‑значное числовое значение, указывающее количество байтов от начала файла до места, где находятся данные, относящиеся к конкретному подфайлу. Первый байт в файле находится по смещению 0. |
| [Type](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/type) { get; set; } | 2‑байтовый тип подфайла, например "DL" |

### См. также

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


