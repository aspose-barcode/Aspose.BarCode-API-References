---
title: Class ComplexCodetextReader
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.ComplexBarcode.ComplexCodetextReader class. ComplexCodetextReader decodes codetext to specified complex barcode type
type: docs
weight: 440
url: /net/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class

ComplexCodetextReader decodes codetext to specified complex barcode type.

```csharp
public sealed class ComplexCodetextReader
```

## Methods

| Name | Description |
| --- | --- |
| static [TryDecodeHIBCLIC](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodehibclic/)(string) | Decodes HIBC LIC codetext. |
| static [TryDecodeHIBCPAS](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodehibcpas/)(string) | Decodes HIBC PAS codetext. |
| static [TryDecodeMailmark](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark/)(string) | Decodes Mailmark Barcode C and L codetext. |
| static [TryDecodeMailmark2D](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark2d/)(string) | Decodes Royal Mail Mailmark 2D codetext. |
| static [TryDecodeMaxiCode](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemaxicode/)(MaxiCodeMode, string) | Decodes MaxiCode codetext. |
| static [TryDecodeSwissQR](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodeswissqr/)(string) | Decodes SwissQR codetext. |
| static [TryDecodeUSADriveId](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodeusadriveid/)(string) | Decodes USADriveId codetext. |

## Examples

This sample shows how to recognize and decode SwissQR image.

```csharp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

### See Also

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


