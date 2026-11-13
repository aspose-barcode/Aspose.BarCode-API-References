---
title: "QrParameters"
second_title: "Aspose.BarCode för Python via .NET API-referens"
description: 
type: docs
url: /sv/python-net/aspose.barcode.generation/qrparameters/
---

## QrParameters class

QR-parametrar.

Typen QrParameters visar följande medlemmar:
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| eci_encoding | Utökade kanalinterpretationsidentifierare. Den används för att ge streckkodsläsaren detaljer<br/>            om de använda referenserna för kodning av data i symbolen.<br/>            Den aktuella implementeringen innehåller alla välkända teckenuppsättningskodningar.<br/>            Stöds inte av MicroQR. |
| encode_mode | QR-symbologityp för BarCodes kodningsläge.<br/>            Standardvärde: QREncodeMode.Auto. |
| error_level | Nivå för Reed-Solomon-felkorrigering för QR-, MicroQR- och RectMicroQR-streckkod.<br/>             Från låg till hög: LevelL, LevelM, LevelQ, LevelH. Se QRErrorLevel. |
| version | Version av QR-kod. Från Version1 till Version40.<br/>            Standardvärde är QRVersion.Auto. |
| micro_qr_version | Version av MicroQR-kod. Från version M1 till version M4.<br/>            Standardvärde är MicroQRVersion.Auto. |
| rect_micro_qr_version | Version av RectMicroQR-kod. Från version R7x59 till version R17x139.<br/>            Standardvärde är RectMicroQRVersion.Auto. |
| aspect_ratio | Höjd/Bredd-förhållande för 2D BarCode-modulen. |
| structured_append | QR strukturerade tilläggsparametrar.<br/>            Strukturerat tilläggsläge stöds inte av MicroQR- och RectMicroQR-streckkoder. |
| encode_gs1_separator_in_byte_mode |  |

### Se även

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

