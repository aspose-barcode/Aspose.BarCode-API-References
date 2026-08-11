---
title: "MacroCharacter"
linktitle: "MacroCharacter"
second_title: "Aspose.BarCode for Python via Java"
description: "Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. 05 Macro craracter is translated to \"[)>\\u001E05\\u001D\" as decoded "
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/macrocharacter/
---

## MacroCharacter enum

**Module:** `aspose_barcode.generation.macro_character`


Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. 05 Macro craracter is translated to "[)>\u001E05\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer. 06 Macro craracter is translated to "[)>\u001E06\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer. here samples show how to encode Macro Characters in MicroPdf417 and DataMatrix


## Enum Values

| Name | Value | Description |
| --- | --- | --- |
| [MACRO_05](#macro_05) | `5` | 05 Macro craracter is added to barcode data in first position. GS1 Data Identifier ISO 15434 Character is translated to "[)>\u001E05\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer. to generate autoidentified GS1 message like this "(10)123ABC(10)123ABC" in ISO 15434 format you need: |
| [MACRO_06](#macro_06) | `6` | 06 Macro craracter is added to barcode data in first position. ASC MH10 Data Identifier ISO 15434 Character is translated to "[)>\u001E06\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer. |
| [NONE](#none) | `0` | None of Macro Characters are added to barcode data. |
### MacroCharacter.MACRO_05 {#macro_05}

**Type:** `int`

**Value:** `5`

05 Macro craracter is added to barcode data in first position. GS1 Data Identifier ISO 15434 Character is translated to "[)>\u001E05\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer. to generate autoidentified GS1 message like this "(10)123ABC(10)123ABC" in ISO 15434 format you need:

### MacroCharacter.MACRO_06 {#macro_06}

**Type:** `int`

**Value:** `6`

06 Macro craracter is added to barcode data in first position. ASC MH10 Data Identifier ISO 15434 Character is translated to "[)>\u001E06\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer.

### MacroCharacter.NONE {#none}

**Type:** `int`

**Value:** `0`

None of Macro Characters are added to barcode data.

