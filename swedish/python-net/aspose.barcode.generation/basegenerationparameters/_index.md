---
title: "BaseGenerationParameters"
second_title: "Aspose.BarCode för Python via .NET API-referens"
description: 
type: docs
url: /sv/python-net/aspose.barcode.generation/basegenerationparameters/
---

## BaseGenerationParameters class

Parametrar för generering av streckkodsbilder.

Typen BaseGenerationParameters exponerar följande medlemmar:
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| use_anti_alias | Hämtar eller anger ett värde som indikerar om anti-aliasing‑läge används för att rendera bilden |
| back_color | Bakgrundsfärg för streckkodsbilden.<br/>            Standardvärde: Color.White.<br/>            Se [Color](/barcode/python-net/aspose.drawing/color/). |
| upplösning | Hämtar eller anger upplösningen för BarCode‑bilden.<br/>            Ett värde för båda dimensionerna.<br/>            Standardvärde: 96 dpi. |
| rotation_angle | Rotationsvinkel för BarCode‑bilden, mätt i grader, t.ex. RotationAngle = 0 eller RotationAngle = 360 betyder ingen rotation.<br/>            Om RotationAngle INTE är lika med 90, 180, 270 eller 0 kan det öka svårigheten för skannern att läsa bilden.<br/>            Standardvärde: 0. |
| caption_above | Rubrik ovanför BarCode‑bilden. Se [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| caption_below | Rubrik under BarCode‑bilden. Se [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| image | Bildparametrar. Se [ImageParameters](/barcode/python-net/aspose.barcode.generation/imageparameters/). |
| auto_size_mode | Anger de olika typerna av automatiska storleksinställningslägen.<br/>            Standardvärde: AutoSizeMode.None. |
| image_height | BarCode-bildens höjd när egenskapen [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) är inställd på AutoSizeMode.Nearest eller AutoSizeMode.Interpolation. |
| image_width | BarCode-bildens bredd när egenskapen [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) är inställd på AutoSizeMode.Nearest eller AutoSizeMode.Interpolation. |
| barcode | Hämtar [BarcodeParameters](/barcode/python-net/aspose.barcode.generation/barcodeparameters/) som innehåller alla streckkodsegenskaper. |
| border | Hämtar [BorderParameters](/barcode/python-net/aspose.barcode.generation/borderparameters/) som innehåller alla konfigurationsinställningar för streckkodens ram. |

### Se även

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

