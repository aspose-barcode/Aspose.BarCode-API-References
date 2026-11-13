---
title: "QrParameters"
second_title: "Aspose.BarCode voor Python via .NET API-referentie"
description: 
type: docs
url: /nl/python-net/aspose.barcode.generation/qrparameters/
---

## QrParameters class

QR-parameters.

Het type QrParameters bevat de volgende leden:
## Properties
| Name | Beschrijving |
| :- | :- |
| eci_encoding | Extended Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven<br/>            over de gebruikte referenties voor het coderen van de gegevens in het symbool.<br/>            De huidige implementatie bevat alle bekende charset‑coderingen.<br/>            Niet ondersteund door MicroQR. |
| encode_mode | QR-symbologie type van de coderingsmodus van BarCode.<br/>            Standaardwaarde: QREncodeMode.Auto. |
| error_level | Niveau van Reed‑Solomon-foutcorrectie voor QR-, MicroQR- en RectMicroQR-barcode.<br/>             Van laag naar hoog: LevelL, LevelM, LevelQ, LevelH. Zie QRErrorLevel. |
| version | Versie van QR Code. Van Version1 tot Version40.<br/>            Standaardwaarde is QRVersion.Auto. |
| micro_qr_version | Versie van MicroQR Code. Van versie M1 tot versie M4.<br/>            Standaardwaarde is MicroQRVersion.Auto. |
| rect_micro_qr_version | Versie van RectMicroQR Code. Van versie R7x59 tot versie R17x139.<br/>            Standaardwaarde is RectMicroQRVersion.Auto. |
| aspect_ratio | Hoogte/breedteverhouding van de 2D BarCode-module. |
| structured_append | QR gestructureerde toevoegingsparameters.<br/>            Gestructureerde toevoegingsmodus wordt niet ondersteund door MicroQR- en RectMicroQR-barcodes. |
| encode_gs1_separator_in_byte_mode |  |

### Zie ook

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

