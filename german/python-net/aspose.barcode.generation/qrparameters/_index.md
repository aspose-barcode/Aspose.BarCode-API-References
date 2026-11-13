---
title: "QrParameters"
second_title: "Aspose.BarCode für Python über .NET API-Referenz"
description: 
type: docs
url: /de/python-net/aspose.barcode.generation/qrparameters/
---

## QrParameters class

QR-Parameter.

Der Typ QrParameters stellt die folgenden Mitglieder bereit:
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| eci_encoding | Erweiterte Channel Interpretation Identifikatoren. Sie werden verwendet, um dem Barcode-Leser Details mitzuteilen<br/>            über die verwendeten Referenzen zur Kodierung der Daten im Symbol.<br/>            Die aktuelle Implementierung umfasst alle bekannten Zeichensatzkodierungen.<br/>            Nicht unterstützt von MicroQR. |
| encode_mode | QR-Symbologie-Typ des Kodierungsmodus von BarCode.<br/>            Standardwert: QREncodeMode.Auto. |
| error_level | Level der Reed-Solomon-Fehlerkorrektur für QR-, MicroQR- und RectMicroQR-Barcodes.<br/>             Von niedrig bis hoch: LevelL, LevelM, LevelQ, LevelH. Siehe QRErrorLevel. |
| version | Version des QR-Codes. Von Version1 bis Version40.<br/>            Standardwert ist QRVersion.Auto. |
| micro_qr_version | Version des MicroQR-Codes. Von Version M1 bis Version M4.<br/>            Standardwert ist MicroQRVersion.Auto. |
| rect_micro_qr_version | Version des RectMicroQR-Codes. Von Version R7x59 bis Version R17x139.<br/>            Standardwert ist RectMicroQRVersion.Auto. |
| aspect_ratio | Höhen‑/Breiten‑Verhältnis des 2D‑Barcode‑Moduls. |
| structured_append | QR-Parameter für strukturiertes Anfügen.<br/>            Der strukturierte Anfügemodus wird von MicroQR- und RectMicroQR-Barcodes nicht unterstützt. |
| encode_gs1_separator_in_byte_mode |  |

### Siehe auch

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

