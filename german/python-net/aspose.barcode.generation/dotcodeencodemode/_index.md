---
title: "DotCodeEncodeMode"
second_title: "Aspose.Sildes für Python über .NET API‑Referenz"
description: 
type: docs
url: /de/python-net/aspose.barcode.generation/dotcodeencodemode/
---

## DotCodeEncodeMode enumeration

Kodierungsmodus für DotCode-Barcodes.

## Members
| Member‑Name | Beschreibung |
| :- | :- |
| AUTO | Im Auto‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. <br/>            Unicode‑Zeichen werden mit der im ECIEncoding angegebenen Kodierung neu kodiert, wobei ein ECI‑Identifier eingefügt wird.<br/>            Wird ein Zeichen gefunden, das von der ausgewählten ECI‑Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst. |
| BINARY | Im Binär‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. <br/>            Wird ein Unicode‑Zeichen gefunden, wird eine Ausnahme ausgelöst. |
| ECI | Im ECI‑Modus wird die gesamte Nachricht mit der im ECIEncoding angegebenen Kodierung neu kodiert, wobei ein ECI‑Identifier eingefügt wird.<br/>            Wird ein Zeichen gefunden, das von der ausgewählten ECI‑Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst.<br/>            Bitte beachten Sie, dass einige alte (vor 2006) Scanner diesen Modus möglicherweise nicht unterstützen. |
| EXTENDED |  |

### Siehe auch

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

