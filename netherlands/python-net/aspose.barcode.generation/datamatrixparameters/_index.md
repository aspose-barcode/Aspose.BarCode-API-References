---
title: "DataMatrixParameters"
second_title: "Aspose.BarCode voor Python via .NET API-referentie"
description: 
type: docs
url: /nl/python-net/aspose.barcode.generation/datamatrixparameters/
---

## DataMatrixParameters class

DataMatrix-parameters.

Het type DataMatrixParameters biedt de volgende leden:
## Properties
| Name | Beschrijving |
| :- | :- |
| ecc_type | Haalt of stelt een Datamatrix ECC-type in.<br/>            Standaardwaarde: DataMatrixEccType.Ecc200. |
| version | Haalt of stelt een Datamatrix-symboolgrootte in.<br/>            Standaardwaarde: Version.Auto. |
| encode_mode | Encode-modus van Datamatrix-barcode.<br/>            Standaardwaarde: EncodeMode.Auto. |
| structured_append_barcode_id | Barcode-ID voor Structured Append-modus van Datamatrix-barcode.<br/>            Standaardwaarde: 0 |
| structured_append_barcodes_count | Aantal barcodes voor Structured Append-modus van Datamatrix-barcode.<br/>            Standaardwaarde: 0 |
| structured_append_file_id | Bestands-ID voor Structured Append-modus van Datamatrix-barcode.<br/>            Standaardwaarde: 0 |
| is_reader_programming | Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren<br/>            als programmering voor lezerinitialisatie.<br/>            Standaardwaarde: false |
| macro_characters | Macro Characters 05 en 06 waarden worden gebruikt om compactere codering te verkrijgen in speciale modi.<br/>            Kan alleen worden gebruikt met DataMatrixEccType.Ecc200 of DataMatrixEccType.EccAuto.<br/>            Kan niet worden gebruikt met EncodeTypes.GS1DataMatrix<br/>            Standaardwaarde: MacroCharacters.None. |
| aspect_ratio | Hoogte/breedteverhouding van de 2D BarCode-module. |
| eci_encoding | Haalt of stelt de ECI-codering in. Wordt gebruikt wanneer EncodeMode Auto is.<br/>            Standaardwaarde: ISO-8859-1 |

### Zie ook

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

