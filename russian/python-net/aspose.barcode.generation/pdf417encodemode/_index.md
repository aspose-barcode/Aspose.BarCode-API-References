---
title: "Pdf417EncodeMode"
second_title: "Aspose.Sildes for Python via .NET API Reference"
description: 
type: docs
url: /ru/python-net/aspose.barcode.generation/pdf417encodemode/
---

## Pdf417EncodeMode enumeration

Режим кодирования штрих‑кода Pdf417

## Members
| Имя члена | Описание |
| :- | :- |
| AUTO | В режиме Auto кодировка CodeText производится с максимальной компактностью данных. <br/>            Юникод‑символы перекодируются в указанную кодировку ECIEncoding с вставкой идентификатора ECI.<br/>            Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение. |
| BINARY | В режиме Binary кодировка CodeText производится с максимальной компактностью данных. <br/>            Если найден юникод‑символ, генерируется исключение. |
| ECI | В режиме ECI всё сообщение перекодируется в указанную кодировку ECIEncoding с вставкой идентификатора ECI.<br/>            Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение.<br/>            Обратите внимание, что некоторые старые сканеры (до 2006 года) могут не поддерживать этот режим. |
| EXTENDED |  |

### See Also

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

