---
title: "QREncodeMode"
second_title: "Aspose.Sildes för Python via .NET API-referens"
description: 
type: docs
url: /sv/python-net/aspose.barcode.generation/qrencodemode/
---

## QREncodeMode enumeration

Kodningsläge för QR-streckkoder.

## Members
| Medlemsnamn | Beskrivning |
| :- | :- |
| AUTO | I Auto-läge kodas CodeText med maximal datakomprimering. <br/>            Unicode-tecken kodas i kanji-läge om möjligt, eller de kodas om i den angivna ECIEncoding‑kodningen med insättning av en ECI‑identifierare.<br/>            Om ett tecken hittas som inte stöds av den valda ECI‑kodningen, kastas ett undantag. |
| EXTENDED |  |
| BINARY | I Binary‑läge kodas CodeText med maximal datakomprimering. <br/>            Om ett Unicode‑tecken hittas, kastas ett undantag. |
| ECI | I ECI-läge kodas hela meddelandet om i den angivna ECIEncoding‑kodningen med insättning av en ECI‑identifierare.<br/>            Om ett tecken hittas som inte stöds av den valda ECI‑kodningen, kastas ett undantag.<br/>            Observera att vissa äldre (före 2006) skannrar kanske inte stöder detta läge.<br/>            Detta läge stöds inte av MicroQR‑streckkoder. |

### Se även

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

