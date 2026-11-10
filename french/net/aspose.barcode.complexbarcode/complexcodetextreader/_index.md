---
title: "Classe ComplexCodetextReader"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Aspose.BarCode.ComplexBarcode.ComplexCodetextReader classe. ComplexCodetextReader décode le texte de code vers le type de code-barres complexe spécifié"
type: docs
weight: 520
url: /fr/net/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class

ComplexCodetextReader décode le texte de code vers le type de code-barres complexe spécifié.

```csharp
public sealed class ComplexCodetextReader
```

## Méthodes

| Nom | Description |
| --- | --- |
| static [TryDecodeGS1Codetext](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodegs1codetext/)(string) | Décode le texte de code GS1. |
| static [TryDecodeGS1DigitalLink](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodegs1digitallink/)(string) | Décode le lien numérique GS1. |
| static [TryDecodeHIBCLIC](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodehibclic/)(string) | Décode le texte de code HIBC LIC. |
| static [TryDecodeHIBCPAS](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodehibcpas/)(string) | Décode le texte de code HIBC PAS. |
| static [TryDecodeMailmark](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark/)(string) | Décode le texte de code du code-barres Mailmark C et L. |
| static [TryDecodeMailmark2D](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark2d/)(string) | Décode le texte de code Royal Mail Mailmark 2D. |
| static [TryDecodeMaxiCode](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemaxicode/)(MaxiCodeMode, string) | Décode le texte de code MaxiCode. |
| static [TryDecodeSwissQR](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodeswissqr/)(string) | Décode le texte de code SwissQR. |
| static [TryDecodeUSADriveId](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodeusadriveid/)(string) | Décode le texte de code USADriveId. |

## Exemples

Cet exemple montre comment reconnaître et décoder une image SwissQR.

```csharp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

### Voir aussi

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


