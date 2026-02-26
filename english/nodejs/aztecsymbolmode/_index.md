---
title: "AztecSymbolMode Enum"
linktitle: "AztecSymbolMode"
articleTitle: "AztecSymbolMode"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Specifies the Aztec symbol mode."
type: docs
weight: 930
url: /nodejs/aztecsymbolmode/
---
## AztecSymbolMode enumeration

Specifies the Aztec symbol mode.

```javascript
public enum AztecSymbolMode
```

## Values

| Name | Value | Description |
| --- | :---: | --- |
| AUTO | `0` | Specifies to automatically pick up the best symbol (COMPACT or FULL-range) for Aztec. This is default value. |
| COMPACT | `1` | Specifies the COMPACT symbol for Aztec. Aztec COMPACT symbol permits only 1, 2, 3 or 4 layers. |
| FULL_RANGE | `2` | Specifies the FULL-range symbol for Aztec. Aztec FULL-range symbol permits from 1 to 32 layers. |
| RUNE | `3` | Specifies the RUNE symbol for Aztec. Aztec Runes are a series of small but distinct machine-readable marks. It permits only number value from 0 to 255. |

## Examples

```javascript
let generator = new BarcodeGenerator(EncodeTypes.AZTEC);
generator.setCodeText("125");
generator.getParameters().getBarcode().getAztec().setAztecSymbolMode(AztecSymbolMode.RUNE);
generator.save("test.png", BarCodeImageFormat.PNG);
```

### See Also

* assembly [Aspose.BarCode](../)

