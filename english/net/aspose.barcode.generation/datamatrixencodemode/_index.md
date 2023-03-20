---
title: Enum DataMatrixEncodeMode
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.DataMatrixEncodeMode enum. DataMatrix encoders encoding mode default to Auto
type: docs
weight: 880
url: /net/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enumeration

DataMatrix encoder's encoding mode, default to Auto

```csharp
public enum DataMatrixEncodeMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | `0` | Automatically pick up the best encode mode for Datamatrix encoding |
| ASCII | `1` | Encodes one alphanumeric or two numeric characters per byte |
| Full | `6` | Encode 8 bit values |
| Custom | `7` | Encode with the encoding specified in BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
| C40 | `8` | Uses C40 encoding. Encodes Upper-case alphanumeric, Lower case and special characters |
| Text | `9` | Uses Text encoding. Encodes Lower-case alphanumeric, Upper case and special characters |
| EDIFACT | `10` | Uses EDIFACT encoding. Uses six bits per character, encodes digits, upper-case letters, and many punctuation marks, but has no support for lower-case letters. |
| ANSIX12 | `11` | Uses ANSI X12 encoding. |
| ExtendedCodetext | `12` | ExtendedCodetext mode allows to manually switch encodation schemes in codetext.<br>Format : "\Encodation_scheme_name:text\Encodation_scheme_name:text".<br>Allowed encodation schemes are: EDIFACT, ANSIX12, ASCII, C40, Text, Auto.<br>Extended codetext example: @"\ansix12:ANSIX12TEXT\ascii:backslash must be \\ doubled\edifact:EdifactEncodedText"<br>All backslashes (\) must be doubled in text. |

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


