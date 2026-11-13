---
title: "AztecParameters"
second_title: "Aspose.BarCode för Python via .NET API-referens"
description: 
type: docs
url: /sv/python-net/aspose.barcode.generation/aztecparameters/
---

## AztecParameters class

Aztec-parametrar.

Typen AztecParameters innehåller följande medlemmar:
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| encode_mode | Hämtar eller anger ett Aztec-kodningsläge. <br/>            Standardvärde: Auto. |
| eci_encoding | Hämtar eller anger ECI-kodning. Används när AztecEncodeMode är Auto.<br/>            Standardvärde: ISO-8859-1 |
| structured_append_barcode_id | Streckkod-ID för Structured Append-läge i Aztec-streckkod. Streckkod-ID bör vara i intervallet 1 till antalet streckkoder.<br/>            Standardvärde: 0 |
| structured_append_barcodes_count | Antalet streckkoder för Structured Append-läget i Aztec-streckkod. Antalet streckkoder bör vara i intervallet 1 till 26.<br/>            Standardvärde: 0 |
| structured_append_file_id | Fil-ID för Structured Append-läget i Aztec-streckkod (valfritt fält). Fil-ID får inte innehålla mellanslag.<br/>            Standardvärde: tom sträng |
| error_level | Nivå för felkorrigering för Aztec-typer av streckkod.<br/>            Värdet bör vara mellan 5 och 95. |
| symbol_mode | Hämtar eller anger ett Aztec Symbol-läge.<br/>            Standardvärde: AztecSymbolMode.Auto. |
| layers_count | Hämtar eller anger antalet lager för Aztec-symbolen. Antalet lager bör vara i intervallet 1 till 3 för Compact-läget och<br/>            i intervallet 1 till 32 för Full Range-läget.<br/>            Standardvärde: 0 (auto). |
| is_reader_initialization | Används för att instruera läsaren att tolka data som finns i symbolen<br/>            som programmering för läsarens initiering. |
| aspect_ratio | Höjd/Bredd-förhållande för 2D BarCode-modulen. |

### Se även

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

