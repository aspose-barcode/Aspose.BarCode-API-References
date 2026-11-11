---
title: "Klasse ComplexCodetextReader"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.ComplexBarcode.ComplexCodetextReader klasse. ComplexCodetextReader decodeert codetext naar het opgegeven complexe barcode-type."
type: docs
weight: 520
url: /nl/net/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class

ComplexCodetextReader decodeert codetekst naar het opgegeven complexe barcode‑type.

```csharp
public sealed class ComplexCodetextReader
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| static [TryDecodeGS1Codetext](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodegs1codetext/)(string) | Decodeert GS1-codetext. |
| static [TryDecodeGS1DigitalLink](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodegs1digitallink/)(string) | Decodeert GS1 Digital Link. |
| static [TryDecodeHIBCLIC](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodehibclic/)(string) | Decodeert HIBC LIC-codetekst. |
| static [TryDecodeHIBCPAS](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodehibcpas/)(string) | Decodeert HIBC PAS-codetekst. |
| static [TryDecodeMailmark](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark/)(string) | Decodeert Mailmark Barcode C en L codetekst. |
| static [TryDecodeMailmark2D](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark2d/)(string) | Decodeert Royal Mail Mailmark 2D-codetekst. |
| static [TryDecodeMaxiCode](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemaxicode/)(MaxiCodeMode, string) | Decodeert MaxiCode-codetekst. |
| static [TryDecodeSwissQR](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodeswissqr/)(string) | Decodeert SwissQR-codetekst. |
| static [TryDecodeUSADriveId](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodeusadriveid/)(string) | Decodeert USADriveId-codetekst. |

## Voorbeelden

Dit voorbeeld laat zien hoe een SwissQR-afbeelding te herkennen en te decoderen.

```csharp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

### Zie ook

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


