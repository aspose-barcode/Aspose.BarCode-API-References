---
title: "QREncodeMode"
second_title: "Aspose.Sildes für Python über .NET API‑Referenz"
description: 
type: docs
url: /de/python-net/aspose.barcode.generation/qrencodemode/
---

## QREncodeMode enumeration

Kodierungsmodus für QR‑Barcodes.

## Members
| Member‑Name | Beschreibung |
| :- | :- |
| AUTO | Im Auto‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. <br/>            Unicode‑Zeichen werden, wenn möglich, im Kanji‑Modus kodiert, oder sie werden mit der angegebenen ECIEncoding‑Kodierung und dem Einfügen eines ECI‑Identifikators erneut kodiert.<br/>            Wird ein Zeichen gefunden, das von der ausgewählten ECI‑Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst. |
| EXTENDED |  |
| BINARY | Im Binär‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. <br/>            Wird ein Unicode‑Zeichen gefunden, wird eine Ausnahme ausgelöst. |
| ECI | Im ECI‑Modus wird die gesamte Nachricht mit der angegebenen ECIEncoding‑Kodierung und dem Einfügen eines ECI‑Identifikators erneut kodiert.<br/>            Wird ein Zeichen gefunden, das von der ausgewählten ECI‑Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst.<br/>            Bitte beachten Sie, dass einige alte (vor 2006) Scanner diesen Modus möglicherweise nicht unterstützen.<br/>            Dieser Modus wird von MicroQR‑Barcodes nicht unterstützt. |

### Siehe auch

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

