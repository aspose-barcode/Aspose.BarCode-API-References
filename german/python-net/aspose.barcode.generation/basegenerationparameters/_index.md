---
title: "BaseGenerationParameters"
second_title: "Aspose.BarCode für Python über .NET API-Referenz"
description: 
type: docs
url: /de/python-net/aspose.barcode.generation/basegenerationparameters/
---

## BaseGenerationParameters class

Parameter zur Erzeugung von Barcode‑Bildern.

Der BaseGenerationParameters-Typ stellt die folgenden Mitglieder bereit:
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| use_anti_alias | Ruft einen Wert ab oder legt ihn fest, der angibt, ob der Anti-Aliasing-Modus zum Rendern des Bildes verwendet wird |
| back_color | Hintergrundfarbe des Barcode-Bildes.<br/>            Standardwert: Color.White.<br/>            Siehe [Color](/barcode/python-net/aspose.drawing/color/). |
| Auflösung | Ruft die Auflösung des Barcode-Bildes ab oder legt sie fest.<br/>            Ein Wert für beide Dimensionen.<br/>            Standardwert: 96 dpi. |
| rotation_angle | Drehwinkel des Barcode-Bildes, gemessen in Grad, z. B. RotationAngle = 0 oder RotationAngle = 360 bedeutet keine Drehung.<br/>            Wenn RotationAngle NICHT gleich 90, 180, 270 oder 0 ist, kann dies die Schwierigkeit für den Scanner erhöhen, das Bild zu lesen.<br/>            Standardwert: 0. |
| caption_above | Beschriftung über dem Barcode-Bild. Siehe [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| caption_below | Beschriftung unter dem Barcode-Bild. Siehe [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| image | Bildparameter. Siehe [ImageParameters](/barcode/python-net/aspose.barcode.generation/imageparameters/). |
| auto_size_mode | Gibt die verschiedenen Typen automatischer Größenmodi an.<br/>            Standardwert: AutoSizeMode.None. |
| image_height | BarCode-Bildhöhe, wenn die [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) Eigenschaft auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist. |
| image_width | BarCode-Bildbreite, wenn die [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) Eigenschaft auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist. |
| barcode | Ruft die [BarcodeParameters](/barcode/python-net/aspose.barcode.generation/barcodeparameters/) ab, die alle Barcode-Eigenschaften enthält. |
| border | Ruft die [BorderParameters](/barcode/python-net/aspose.barcode.generation/borderparameters/) ab, die alle Konfigurationseigenschaften für den Barcode-Rahmen enthält. |

### Siehe auch

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

