---
title: "DataMatrixEncodeMode"
second_title: "Aspose.Sildes för Python via .NET API-referens"
description: 
type: docs
url: /sv/python-net/aspose.barcode.generation/datamatrixencodemode/
---

## DataMatrixEncodeMode enumeration

DataMatrix-kodares kodningsläge, standard är Auto

## Members
| Medlemsnamn | Beskrivning |
| :- | :- |
| AUTO | I Auto‑läge kodas CodeText med maximal datakomprimering. <br/>            Unicode‑tecken omkodas i den angivna ECIEncoding‑kodningen med införande av en ECI‑identifierare.<br/>            Om ett tecken hittas som inte stöds av den valda ECI‑kodningen, kastas ett undantag. |
| ASCII | Kodar ett alfanumeriskt eller två numeriska tecken per byte |
| C40 | Använder C40‑kodning. Kodar versala alfanumeriska tecken, gemener och specialtecken |
| TEXT | Använder Text‑kodning. Kodar gemena alfanumeriska tecken, versaler och specialtecken |
| EDIFACT | Använder EDIFACT‑kodning. Använder sex bitar per tecken, kodar siffror, versala bokstäver och många skiljetecken, men har ingen stöd för gemena bokstäver. |
| ANSIX12 | Använder ANSI X12‑kodning. |
| EXTENDED |  |
| BASE256 | Koda 8‑bitarsvärden |
| BINARY | I Binary‑läge kodas CodeText med maximal datakomprimering. <br/>            Om ett Unicode‑tecken hittas, kastas ett undantag. |
| ECI | I ECI‑läge omkodas hela meddelandet i den angivna ECIEncoding‑kodningen med införande av en ECI‑identifierare.<br/>            Om ett tecken hittas som inte stöds av den valda ECI‑kodningen, kastas ett undantag.<br/>            Observera att vissa äldre (före 2006) skannrar kanske inte stödjer detta läge. |

### Se även

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

