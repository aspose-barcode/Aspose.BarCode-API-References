---
title: "AztecEncodeMode"
second_title: "Aspose.Sildes for Python via .NET API Reference"
description: 
type: docs
url: /ru/python-net/aspose.barcode.generation/aztecencodemode/
---

## AztecEncodeMode enumeration

Режим кодирования для штрихкодов Aztec.

## Members
| Имя члена | Описание |
| :- | :- |
| AUTO | В режиме Auto кодировка CodeText производится с максимальной компактностью данных. <br/>            Юникод‑символы перекодируются в указанную кодировку ECIEncoding с вставкой идентификатора ECI.<br/>            Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение. |
| EXTENDED |  |
| BINARY | В режиме Binary кодировка CodeText производится с максимальной компактностью данных. <br/>            Если найден юникод‑символ, генерируется исключение. |
| ECI | В режиме ECI всё сообщение перекодируется в указанную кодировку ECIEncoding с вставкой идентификатора ECI.<br/>            Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение.<br/>            Обратите внимание, что некоторые старые сканеры (до 2006 года) могут не поддерживать этот режим. |

### See Also

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

