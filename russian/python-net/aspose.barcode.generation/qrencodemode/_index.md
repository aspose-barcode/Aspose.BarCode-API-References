---
title: "QREncodeMode"
second_title: "Aspose.Sildes for Python via .NET API Reference"
description: 
type: docs
url: /ru/python-net/aspose.barcode.generation/qrencodemode/
---

## QREncodeMode enumeration

Режим кодирования для штрих‑кодов QR.

## Members
| Имя члена | Описание |
| :- | :- |
| AUTO | В режиме Auto код текста кодируется с максимальной компактностью данных. <br/>            Юникодные символы кодируются в режиме кандзи, если это возможно, или они перекодируются в указанной кодировке ECIEncoding с вставкой идентификатора ECI.<br/>            Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение. |
| EXTENDED |  |
| BINARY | В режиме Binary кодировка CodeText производится с максимальной компактностью данных. <br/>            Если найден юникод‑символ, генерируется исключение. |
| ECI | В режиме ECI всё сообщение перекодируется в указанной кодировке ECIEncoding с вставкой идентификатора ECI.<br/>            Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение.<br/>            Обратите внимание, что некоторые старые (до 2006) сканеры могут не поддерживать этот режим.<br/>            Этот режим не поддерживается штрих‑кодами MicroQR. |

### See Also

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

