---
title: "BaseGenerationParameters"
second_title: "Aspose.BarCode voor Python via .NET API-referentie"
description: 
type: docs
url: /nl/python-net/aspose.barcode.generation/basegenerationparameters/
---

## BaseGenerationParameters class

Barcode-afbeeldingsgeneratieparameters.

Het type BaseGenerationParameters bevat de volgende leden:
## Properties
| Name | Beschrijving |
| :- | :- |
| use_anti_alias | Haalt een waarde op of stelt een waarde in die aangeeft of anti-aliasing-modus wordt gebruikt om de afbeelding te renderen |
| back_color | Achtergrondkleur van de barcode-afbeelding.<br/>            Standaardwaarde: Color.White.<br/>            Zie [Color](/barcode/python-net/aspose.drawing/color/). |
| resolutie | Haalt de resolutie van de BarCode-afbeelding op of stelt deze in.<br/>            Eén waarde voor beide dimensies.<br/>            Standaardwaarde: 96 dpi. |
| rotation_angle | Rotatiehoek van de BarCode-afbeelding, gemeten in graden, bijv. RotationAngle = 0 of RotationAngle = 360 betekent geen rotatie.<br/>            Als RotationAngle NIET gelijk is aan 90, 180, 270 of 0, kan dit de moeilijkheid voor de scanner om de afbeelding te lezen vergroten.<br/>            Standaardwaarde: 0. |
| caption_above | Bijschrift boven de BarCode-afbeelding. Zie [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| caption_below | Bijschrift onder de BarCode-afbeelding. Zie [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| image | Afbeeldingsparameters. Zie [ImageParameters](/barcode/python-net/aspose.barcode.generation/imageparameters/). |
| auto_size_mode | Specificeert de verschillende typen automatische grootte-modusinstellingen.<br/>            Standaardwaarde: AutoSizeMode.None. |
| image_height | BarCode-beeldhoogte wanneer de [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) eigenschap is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation. |
| image_width | BarCode-beeldbreedte wanneer de [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) eigenschap is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation. |
| barcode | Haalt de [BarcodeParameters](/barcode/python-net/aspose.barcode.generation/barcodeparameters/) op die alle barcode-eigenschappen bevat. |
| border | Haalt de [BorderParameters](/barcode/python-net/aspose.barcode.generation/borderparameters/) op die alle configuratie-eigenschappen voor de barcode-rand bevat. |

### Zie ook

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

