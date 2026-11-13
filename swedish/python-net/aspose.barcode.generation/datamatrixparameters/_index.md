---
title: "DataMatrixParameters"
second_title: "Aspose.BarCode för Python via .NET API-referens"
description: 
type: docs
url: /sv/python-net/aspose.barcode.generation/datamatrixparameters/
---

## DataMatrixParameters class

DataMatrix-parametrar.

Typen DataMatrixParameters exponerar följande medlemmar:
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| ecc_type | Hämtar eller anger en Datamatrix ECC-typ.<br/>            Standardvärde: DataMatrixEccType.Ecc200. |
| version | Hämtar eller anger en Datamatrix-symbolstorlek.<br/>            Standardvärde: Version.Auto. |
| encode_mode | Kodningsläge för Datamatrix-streckkod.<br/>            Standardvärde: EncodeMode.Auto. |
| structured_append_barcode_id | Streckkod-ID för Structured Append-läge för Datamatrix-streckkod.<br/>            Standardvärde: 0 |
| structured_append_barcodes_count | Antal streckkoder för Structured Append-läge för Datamatrix-streckkod.<br/>            Standardvärde: 0 |
| structured_append_file_id | Fil-ID för Structured Append-läge för Datamatrix-streckkod.<br/>            Standardvärde: 0 |
| is_reader_programming | Används för att instruera läsaren att tolka data som finns i symbolen<br/>            som programmering för läsarinitialisering.<br/>            Standardvärde: false |
| macro_characters | Makrotecken 05 och 06 används för att erhålla mer kompakt kodning i speciella lägen.<br/>            Kan endast användas med DataMatrixEccType.Ecc200 eller DataMatrixEccType.EccAuto.<br/>            Kan inte användas med EncodeTypes.GS1DataMatrix<br/>            Standardvärde: MacroCharacters.None. |
| aspect_ratio | Höjd/Bredd-förhållande för 2D BarCode-modulen. |
| eci_encoding | Hämtar eller anger ECI‑kodning. Används när EncodeMode är Auto.<br/>            Standardvärde: ISO-8859-1 |

### Se även

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

