---
title: Enum MacroCharacter
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.MacroCharacter enum. Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. 05 Macro craracter is translated to u001E05u001D as decoded data header and u001Eu0004 as decoded data trailer. 06 Macro craracter is translated to u001E06u001D as decoded data header and u001Eu0004 as decoded data trailer
type: docs
weight: 1020
url: /net/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enumeration

Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. 05 Macro craracter is translated to "[)&gt;\u001E05\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer. 06 Macro craracter is translated to "[)&gt;\u001E06\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer.

```csharp
public enum MacroCharacter
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | None of Macro Characters are added to barcode data |
| Macro05 | `5` | 05 Macro craracter is added to barcode data in first position. GS1 Data Identifier ISO 15434 Character is translated to "[)&gt;\u001E05\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer. |
| Macro06 | `6` | 06 Macro craracter is added to barcode data in first position. ASC MH10 Data Identifier ISO 15434 Character is translated to "[)&gt;\u001E06\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer. |

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


