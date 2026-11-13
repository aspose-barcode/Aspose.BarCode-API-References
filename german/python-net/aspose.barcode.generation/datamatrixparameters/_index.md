---
title: "DataMatrixParameters"
second_title: "Aspose.BarCode für Python über .NET API-Referenz"
description: 
type: docs
url: /de/python-net/aspose.barcode.generation/datamatrixparameters/
---

## DataMatrixParameters class

DataMatrix‑Parameter.

Der Typ DataMatrixParameters stellt die folgenden Member bereit:
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| ecc_type | Liest oder setzt einen Datamatrix‑ECC‑Typ.<br/>            Standardwert: DataMatrixEccType.Ecc200. |
| version | Liest oder setzt die Symbolgröße der Datamatrix.<br/>            Standardwert: Version.Auto. |
| encode_mode | Kodierungsmodus des Datamatrix‑Barcodes.<br/>            Standardwert: EncodeMode.Auto. |
| structured_append_barcode_id | Barcode‑ID für den Structured‑Append‑Modus des Datamatrix‑Barcodes.<br/>            Standardwert: 0 |
| structured_append_barcodes_count | Anzahl der Barcodes für den Structured‑Append‑Modus des Datamatrix‑Barcodes.<br/>            Standardwert: 0 |
| structured_append_file_id | Datei‑ID für den Structured‑Append‑Modus des Datamatrix‑Barcodes.<br/>            Standardwert: 0 |
| is_reader_programming | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten<br/>            als Programmierung für die Leserinitialisierung zu interpretieren.<br/>            Standardwert: false |
| macro_characters | Die Werte der Makro‑Zeichen 05 und 06 werden verwendet, um in speziellen Modi eine kompaktere Kodierung zu erhalten.<br/>            Können nur mit DataMatrixEccType.Ecc200 oder DataMatrixEccType.EccAuto verwendet werden.<br/>            Können nicht mit EncodeTypes.GS1DataMatrix verwendet werden<br/>            Standardwert: MacroCharacters.None. |
| aspect_ratio | Höhen‑/Breiten‑Verhältnis des 2D‑Barcode‑Moduls. |
| eci_encoding | Liest oder setzt die ECI-Codierung. Wird verwendet, wenn EncodeMode auf Auto steht.<br/>            Standardwert: ISO-8859-1 |

### Siehe auch

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

