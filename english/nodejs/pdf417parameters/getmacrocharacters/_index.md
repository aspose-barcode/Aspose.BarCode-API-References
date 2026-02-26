---
title: "Pdf417Parameters.getMacroCharacters"
linktitle: "getMacroCharacters"
articleTitle: "getMacroCharacters"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with MicroPdf417 and encodes 916 and 917 MicroP..."
type: docs
weight: 750
url: /nodejs/pdf417parameters/getmacrocharacters/
---
## getMacroCharacters() {#getmacrocharacters}

Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with MicroPdf417 and encodes 916 and 917 MicroPdf417 modes Default value: MacroCharacters.None.

```javascript
getMacroCharacters()
```

## Examples

# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"

```javascript
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
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
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_06);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log(result.getCodeText());
}
</pre>
</pre></blockquote></hr></p>
```

### See Also

* class [Pdf417Parameters](../)
* assembly [Aspose.BarCode](../../)

