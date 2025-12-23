---
title: Enum Code128EncodeMode
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.Code128EncodeMode enum. Encoding mode for Code128 barcodes. Code 128 specification
type: docs
weight: 1020
url: /net/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enumeration

Encoding mode for Code128 barcodes. [Code 128](https://en.wikipedia.org/wiki/Code_128) specification.

```csharp
public enum Code128EncodeMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | `0` | Encode codetext in classic ISO 15417 mode. The mode should be used in all ordinary cases. |
| CodeA | `1` | Encode codetext only in 128A codeset. |
| CodeB | `2` | Encode codetext only in 128B codeset. |
| CodeC | `4` | Encode codetext only in 128C codeset. |
| CodeAB | `3` | Encode codetext only in 128A and 128B codesets. |
| CodeAC | `5` | Encode codetext only in 128A and 128C codesets. |
| CodeBC | `6` | Encode codetext only in 128B and 128C codesets. |

## Examples

Thos code demonstrates how to generate code 128 with different encodings

```csharp
[C#]
//Generate code 128 with ISO 15417 encoding
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//Generate code 128 only with Codeset A encoding
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


