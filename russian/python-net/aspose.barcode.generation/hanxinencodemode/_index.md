---
title: "HanXinEncodeMode"
second_title: "Aspose.Sildes for Python via .NET API Reference"
description: 
type: docs
url: /ru/python-net/aspose.barcode.generation/hanxinencodemode/
---

## HanXinEncodeMode enumeration

Режим кодирования Han Xin Code. Рекомендуется использовать Auto с символами ASCII/китайскими символами или Unicode для символов Unicode.

## Members
| Имя члена | Описание |
| :- | :- |
| AUTO | В режиме Auto текст кода (CodeText) кодируется с максимальной компактностью данных. <br/>            Символы Unicode кодируются с использованием кодировки GB18030 в соответствии со спецификацией штрих‑кода HanXin. |
| BINARY | В режиме Binary кодировка CodeText производится с максимальной компактностью данных. <br/>            Если найден юникод‑символ, генерируется исключение. |
| ECI | В режиме ECI всё сообщение перекодируется в указанную кодировку ECIEncoding с вставкой идентификатора ECI.<br/>            Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение.<br/>            Обратите внимание, что некоторые старые сканеры (до 2006 года) могут не поддерживать этот режим. |
| UNICODE | Режим Unicode предоставляет способ представления любых текстовых данных с ссылкой на кодировку/набор символов UTF8 в коде Han Xin. |
| URI | Режим URI указывает, что данные, представленные в коде Han Xin, являются Uniform Resource Identifier (URI)<br/>            со ссылкой на RFC 3986. |
| EXTENDED | Режим Extended позволяет комбинировать внутренние режимы: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One,<br/>            Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte.<br/>            Текст кода (Codetext) можно создавать вручную с префиксами и удвоенными обратными слешами, например: @"\auto:abc\000009:ΑΒΓΔΕ\auto:ab\\c" или используя HanXinExtCodetextBuilder.<br/>            Если текст кода содержит фрагмент ECI, то после фрагмента ECI в нем могут быть только следующие режимы:<br/>            Auto, Binary, Text, Numeric, URI, ECI. |

### See Also

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

