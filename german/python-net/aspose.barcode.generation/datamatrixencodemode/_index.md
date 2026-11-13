---
title: "DataMatrixEncodeMode"
second_title: "Aspose.Sildes für Python über .NET API‑Referenz"
description: 
type: docs
url: /de/python-net/aspose.barcode.generation/datamatrixencodemode/
---

## DataMatrixEncodeMode enumeration

Kodierungsmodus des DataMatrix-Encoders, standardmäßig Auto

## Members
| Member‑Name | Beschreibung |
| :- | :- |
| AUTO | Im Auto‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. <br/>            Unicode‑Zeichen werden mit der im ECIEncoding angegebenen Kodierung neu kodiert, wobei ein ECI‑Identifier eingefügt wird.<br/>            Wird ein Zeichen gefunden, das von der ausgewählten ECI‑Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst. |
| ASCII | Kodiert ein alphanumerisches oder zwei numerische Zeichen pro Byte |
| C40 | Verwendet C40‑Kodierung. Kodiert alphanumerische Zeichen in Großschreibung, Kleinbuchstaben und Sonderzeichen |
| TEXT | Verwendet Text‑Kodierung. Kodiert alphanumerische Zeichen in Kleinbuchstaben, Großschreibung und Sonderzeichen |
| EDIFACT | Verwendet EDIFACT‑Kodierung. Nutzt sechs Bits pro Zeichen, kodiert Ziffern, Großbuchstaben und viele Satzzeichen, unterstützt jedoch keine Kleinbuchstaben. |
| ANSIX12 | Verwendet ANSI‑X12‑Kodierung. |
| EXTENDED |  |
| BASE256 | Kodiert 8‑Bit‑Werte |
| BINARY | Im Binär‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. <br/>            Wird ein Unicode‑Zeichen gefunden, wird eine Ausnahme ausgelöst. |
| ECI | Im ECI‑Modus wird die gesamte Nachricht mit der im ECIEncoding angegebenen Kodierung neu kodiert, wobei ein ECI‑Identifier eingefügt wird.<br/>            Wird ein Zeichen gefunden, das von der ausgewählten ECI‑Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst.<br/>            Bitte beachten Sie, dass einige alte (vor 2006) Scanner diesen Modus möglicherweise nicht unterstützen. |

### Siehe auch

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

