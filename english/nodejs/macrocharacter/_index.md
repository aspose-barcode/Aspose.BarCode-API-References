---
title: MacroCharacter Enum
linktitle: MacroCharacter
articleTitle: MacroCharacter
second_title: Aspose.BarCode for Node.js via Java
description: "Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. 05 Macro craracter is translated to \"[)>\u001E05\u001D\" as decoded data header and \"\u001E\u0004\" as decoded data trailer. 06 Macro craracter is translated to \"[)>\u001E06\u001D\" as decoded data header and..."
type: docs
weight: 1060
url: /nodejs/macrocharacter/
---
## MacroCharacter enumeration

Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. 05 Macro craracter is translated to "[)>\u001E05\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer. 06 Macro craracter is translated to "[)>\u001E06\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer.

```javascript
public enum MacroCharacter
```

## Values

| Name | Value | Description |
| --- | :---: | --- |
| NONE | `0` | None of Macro Characters are added to barcode data |
| MACRO_05 | `5` | 05 Macro craracter is added to barcode data in first position. GS1 Data Identifier ISO 15434 Character is translated to "[)>\u001E05\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer. //to generate autoidentified GS1 message like this "(10)123ABC(10)123ABC" in ISO 15434 format you need: let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "10123ABC\u001D10123ABC"); generator.getParameters().getBarcode().getDataMatrix().setMacroCharacters(MacroCharacter.MACRO_05); let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), DecodeType.GS_1_DATA_MATRIX); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; cosole.log("BarCode CodeText: " + result.getCodeText()); } |
| MACRO_06 | `6` | 06 Macro craracter is added to barcode data in first position. ASC MH10 Data Identifier ISO 15434 Character is translated to "[)>\u001E06\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer. |

## Examples

# to generate autoidentified GS1 message like this "(10)123ABC(10)123ABC" in ISO 15434 format you need:

```javascript
let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "10123ABC\u001D10123ABC");
generator.getParameters().getBarcode().getDataMatrix().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS1DataMatrix);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log("BarCode CodeText: " + result.getCodeText());
}
```

# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"

```javascript
let generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log( result.getCodeText());
}
```

# Encodes MicroPdf417 with 06 Macro the string: "[)>\u001E06\u001Dabcde1234\u001E\u0004"

```javascript
let generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_06);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log( result.getCodeText());
}
</pre>
</pre>
```

### See Also

* assembly [Aspose.BarCode](../)

