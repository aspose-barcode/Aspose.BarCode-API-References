---
title: "HanXinEncodeMode"
second_title: "Aspose.Sildes für Python über .NET API‑Referenz"
description: 
type: docs
url: /de/python-net/aspose.barcode.generation/hanxinencodemode/
---

## HanXinEncodeMode enumeration

Han Xin Code Kodierungsmodus. Es wird empfohlen, Auto mit ASCII-/Chinesischen Zeichen oder Unicode für Unicode‑Zeichen zu verwenden.

## Members
| Member‑Name | Beschreibung |
| :- | :- |
| AUTO | Im Auto‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. <br/>            Unicode‑Zeichen werden gemäß der HanXin‑Barcode‑Spezifikation mit GB18030‑Kodierung kodiert. |
| BINARY | Im Binär‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. <br/>            Wird ein Unicode‑Zeichen gefunden, wird eine Ausnahme ausgelöst. |
| ECI | Im ECI‑Modus wird die gesamte Nachricht mit der im ECIEncoding angegebenen Kodierung neu kodiert, wobei ein ECI‑Identifier eingefügt wird.<br/>            Wird ein Zeichen gefunden, das von der ausgewählten ECI‑Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst.<br/>            Bitte beachten Sie, dass einige alte (vor 2006) Scanner diesen Modus möglicherweise nicht unterstützen. |
| UNICODE | Der Unicode‑Modus bietet eine Methode, beliebige Textdaten in Bezug auf UTF‑8‑Kodierung/Zeichensatz im Han‑Xin‑Code darzustellen. |
| URI | Der URI‑Modus zeigt an, dass die im Han‑Xin‑Code dargestellten Daten ein Uniform Resource Identifier (URI) sind<br/>            Verweis auf RFC 3986. |
| EXTENDED | Der erweiterte Modus erlaubt Kombinationen interner Modi: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One,<br/>            Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte.<br/>            Der Codetext kann manuell mit Präfixen und doppelten Backslashes erstellt werden, z. B.: @"\auto:abc\000009:ΑΒΓΔΕ\auto:ab\\c" oder mit dem HanXinExtCodetextBuilder.<br/>            Enthält der Codetext ein ECI‑Fragment, dürfen danach im Codetext nur die folgenden Modi vorkommen:<br/>            Auto, Binary, Text, Numeric, URI, ECI. |

### Siehe auch

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

