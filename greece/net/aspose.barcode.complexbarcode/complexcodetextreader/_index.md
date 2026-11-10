---
title: "Κλάση ComplexCodetextReader"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κλάση Aspose.BarCode.ComplexBarcode.ComplexCodetextReader. Ο ComplexCodetextReader αποκωδικοποιεί το κείμενο κώδικα σε καθορισμένο σύνθετο τύπο barcode."
type: docs
weight: 520
url: /el/net/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class

ComplexCodetextReader αποκωδικοποιεί το κείμενο κώδικα σε καθορισμένο τύπο σύνθετου γραμμωτού κώδικα.

```csharp
public sealed class ComplexCodetextReader
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [TryDecodeGS1Codetext](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodegs1codetext/)(string) | Αποκωδικοποιεί το κείμενο κώδικα GS1. |
| static [TryDecodeGS1DigitalLink](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodegs1digitallink/)(string) | Αποκωδικοποιεί το GS1 Digital Link. |
| static [TryDecodeHIBCLIC](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodehibclic/)(string) | Αποκωδικοποιεί το κείμενο κώδικα HIBC LIC. |
| static [TryDecodeHIBCPAS](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodehibcpas/)(string) | Αποκωδικοποιεί το κείμενο κώδικα HIBC PAS. |
| static [TryDecodeMailmark](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark/)(string) | Αποκωδικοποιεί το κείμενο κώδικα Mailmark Barcode C και L. |
| static [TryDecodeMailmark2D](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark2d/)(string) | Αποκωδικοποιεί το κείμενο κώδικα Royal Mail Mailmark 2D. |
| static [TryDecodeMaxiCode](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemaxicode/)(MaxiCodeMode, string) | Αποκωδικοποιεί το κείμενο κώδικα MaxiCode. |
| static [TryDecodeSwissQR](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodeswissqr/)(string) | Αποκωδικοποιεί το κείμενο κώδικα SwissQR. |
| static [TryDecodeUSADriveId](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodeusadriveid/)(string) | Αποκωδικοποιεί το κείμενο κώδικα USADriveId. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να αναγνωρίσετε και να αποκωδικοποιήσετε την εικόνα SwissQR.

```csharp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

### Δείτε επίσης

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


