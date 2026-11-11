---
title: "Перечисление Pdf417EncodeMode"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Aspose.BarCode.Generation.Pdf417EncodeMode перечисление. Режим кодирования штрих‑кода Pdf417"
type: docs
weight: 1540
url: /ru/net/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enumeration

Режим кодирования штрих‑кода Pdf417

```csharp
public enum Pdf417EncodeMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Auto | `0` | В режиме Auto кодировка CodeText выполняется с максимальной компактностью данных. Символы Unicode перекодируются в указанную кодировку ECIEncoding с вставкой идентификатора ECI. Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение. |
| Binary | `1` | В режиме Binary кодировка CodeText выполняется с максимальной компактностью данных. Если найден символ Unicode, генерируется исключение. |
| ECI | `2` | В режиме ECI всё сообщение перекодируется в указанную кодировку ECIEncoding с вставкой идентификатора ECI. Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение. Обратите внимание, что некоторые старые сканеры (до 2006 года) могут не поддерживать этот режим. |
| Extended | `3` | Расширенный режим, поддерживающий несколько режимов ECI. |

### См. также

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


