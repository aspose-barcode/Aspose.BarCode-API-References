---
title: "Clase ComplexCodetextReader"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.ComplexBarcode.ComplexCodetextReader. ComplexCodetextReader decodifica el texto de código al tipo de código de barras complejo especificado"
type: docs
weight: 520
url: /es/net/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class

ComplexCodetextReader decodifica codetext al tipo de código de barras complejo especificado.

```csharp
public sealed class ComplexCodetextReader
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [TryDecodeGS1Codetext](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodegs1codetext/)(string) | Decodifica texto de código GS1. |
| static [TryDecodeGS1DigitalLink](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodegs1digitallink/)(string) | Decodifica GS1 Digital Link. |
| static [TryDecodeHIBCLIC](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodehibclic/)(string) | Decodifica HIBC LIC codetext. |
| static [TryDecodeHIBCPAS](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodehibcpas/)(string) | Decodifica HIBC PAS codetext. |
| static [TryDecodeMailmark](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark/)(string) | Decodifica Mailmark Barcode C y L codetext. |
| static [TryDecodeMailmark2D](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark2d/)(string) | Decodifica Royal Mail Mailmark 2D codetext. |
| static [TryDecodeMaxiCode](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemaxicode/)(MaxiCodeMode, string) | Decodifica MaxiCode codetext. |
| static [TryDecodeSwissQR](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodeswissqr/)(string) | Decodifica SwissQR codetext. |
| static [TryDecodeUSADriveId](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodeusadriveid/)(string) | Decodifica USADriveId codetext. |

## Ejemplos

Este ejemplo muestra cómo reconocer y decodificar la imagen SwissQR.

```csharp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

### Ver también

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


