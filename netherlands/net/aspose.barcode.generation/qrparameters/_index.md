---
title: "Klasse QrParameters"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.QrParameters klasse. QR-parameters"
type: docs
weight: 1650
url: /nl/net/aspose.barcode.generation/qrparameters/
---
## QrParameters class

QR-parameters.

```csharp
public class QrParameters
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/qrparameters/aspectratio/) { get; set; } | Hoogte/breedteverhouding van 2D BarCode-module. |
| [ECIEncoding](../../aspose.barcode.generation/qrparameters/eciencoding/) { get; set; } | Extended Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. De huidige implementatie bevat alle bekende tekensetcoderingen. Niet ondersteund door MicroQR. |
| [EncodeGS1SeparatorInByteMode](../../aspose.barcode.generation/qrparameters/encodegs1separatorinbytemode/) { get; set; } | Haalt een waarde op of stelt deze in die aangeeft of GS1-specialtekens moeten worden gecodeerd in Byte-modus voor QR- en RectMicroQR-streepjescodes. |
| [EncodeMode](../../aspose.barcode.generation/qrparameters/encodemode/) { get; set; } | QR-symbologie type van de coderingsmodus van BarCode. Standaardwaarde: QREncodeMode.Auto. |
| [ErrorLevel](../../aspose.barcode.generation/qrparameters/errorlevel/) { get; set; } | Niveau van Reed-Solomon-foutcorrectie voor QR-, MicroQR- en RectMicroQR-barcode. Van laag naar hoog: LevelL, LevelM, LevelQ, LevelH. Zie QRErrorLevel. |
| [MicroQRVersion](../../aspose.barcode.generation/qrparameters/microqrversion/) { get; set; } | Versie van MicroQR-code. Van versie M1 tot versie M4. Standaardwaarde is MicroQRVersion.Auto. |
| [RectMicroQrVersion](../../aspose.barcode.generation/qrparameters/rectmicroqrversion/) { get; set; } | Versie van RectMicroQR-code. Van versie R7x59 tot versie R17x139. Standaardwaarde is RectMicroQRVersion.Auto. |
| [StructuredAppend](../../aspose.barcode.generation/qrparameters/structuredappend/) { get; set; } | QR-gestructureerde toevoegingsparameters. Gestructureerde toevoegingsmodus wordt niet ondersteund door MicroQR- en RectMicroQR-barcode. |
| [Version](../../aspose.barcode.generation/qrparameters/version/) { get; set; } | Versie van QR-code. Van Version1 tot Version40. Standaardwaarde is QRVersion.Auto. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/qrparameters/tostring/)() | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze `QrParameters`. |

### Zie ook

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


