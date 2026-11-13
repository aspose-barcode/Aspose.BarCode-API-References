---
title: "MaxiCodeEncodeMode"
second_title: "Aspose.Sildes för Python via .NET API-referens"
description: 
type: docs
url: /sv/python-net/aspose.barcode.generation/maxicodeencodemode/
---

## MaxiCodeEncodeMode enumeration

Kodningsläge för MaxiCode-streckkoder.

## Members
| Medlemsnamn | Beskrivning |
| :- | :- |
| AUTO | I Auto‑läge kodas CodeText med maximal datakomprimering. <br/>            Unicode‑tecken omkodas i den angivna ECIEncoding‑kodningen med införande av en ECI‑identifierare.<br/>            Om ett tecken hittas som inte stöds av den valda ECI‑kodningen, kastas ett undantag. |
| EXTENDED |  |
| BINARY | I Binary‑läge kodas CodeText med maximal datakomprimering. <br/>            Om ett Unicode‑tecken hittas, kastas ett undantag. |
| ECI | I ECI‑läge omkodas hela meddelandet i den angivna ECIEncoding‑kodningen med införande av en ECI‑identifierare.<br/>            Om ett tecken hittas som inte stöds av den valda ECI‑kodningen, kastas ett undantag.<br/>            Observera att vissa äldre (före 2006) skannrar kanske inte stödjer detta läge. |

### Se även

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

