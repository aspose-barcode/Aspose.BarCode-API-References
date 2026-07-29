---
title: "MacroCharacter Enum"
linktitle: "MacroCharacter"
articleTitle: "MacroCharacter"
second_title: "Aspose.BarCode for PHP via Java"
description: "Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. 05 Macro craracter is translated to \"[)>\\u001E05\\u001D\" as decoded data header and \"\\u001E\\u0004\" as decode"
type: docs
weight: 10
url: /php/aspose/barcode/generation/macrocharacter/
---

## MacroCharacter enum

**Namespace:** `Aspose.Barcode.Generation`


Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. 05 Macro craracter is translated to "[)>\u001E05\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer. 06 Macro craracter is translated to "[)>\u001E06\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer.


## Enum Values

| Name | Value | Description |
| --- | --- | --- |
| [MACRO_05](/php/aspose/barcode/generation/macrocharacter/macro_05/) | `5` | 05 Macro craracter is added to barcode data in first position. GS1 Data Identifier ISO 15434 Character is translated to "[)>\u001E05\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer. |
| [MACRO_06](/php/aspose/barcode/generation/macrocharacter/macro_06/) | `6` | 06 Macro craracter is added to barcode data in first position. ASC MH10 Data Identifier ISO 15434 Character is translated to "[)>\u001E06\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer. |
| [NONE](/php/aspose/barcode/generation/macrocharacter/none/) | `0` | None of Macro Characters are added to barcode data |
