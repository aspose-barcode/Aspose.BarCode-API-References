---
title: "Klasse ComplexCodetextReader"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.ComplexBarcode.ComplexCodetextReader Klasse. ComplexCodetextReader dekodiert den Codetext zum angegebenen komplexen Barcode-Typ"
type: docs
weight: 520
url: /de/net/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class

ComplexCodetextReader dekodiert den Codetext in den angegebenen komplexen Barcode‑Typ.

```csharp
public sealed class ComplexCodetextReader
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [TryDecodeGS1Codetext](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodegs1codetext/)(string) | Dekodiert GS1-Codetext. |
| static [TryDecodeGS1DigitalLink](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodegs1digitallink/)(string) | Dekodiert GS1 Digital Link. |
| static [TryDecodeHIBCLIC](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodehibclic/)(string) | Dekodiert HIBC LIC-Codetext. |
| static [TryDecodeHIBCPAS](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodehibcpas/)(string) | Dekodiert HIBC PAS-Codetext. |
| static [TryDecodeMailmark](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark/)(string) | Dekodiert Mailmark Barcode C und L Codetext. |
| static [TryDecodeMailmark2D](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark2d/)(string) | Dekodiert Royal Mail Mailmark 2D-Codetext. |
| static [TryDecodeMaxiCode](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemaxicode/)(MaxiCodeMode, string) | Dekodiert MaxiCode-Codetext. |
| static [TryDecodeSwissQR](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodeswissqr/)(string) | Dekodiert SwissQR-Codetext. |
| static [TryDecodeUSADriveId](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodeusadriveid/)(string) | Dekodiert USADriveId-Codetext. |

## Beispiele

Dieses Beispiel zeigt, wie man ein SwissQR-Bild erkennt und dekodiert.

```csharp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

### Siehe auch

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


