---
title: "Klasse QrParameters"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Generation.QrParameters Klasse. QR‑Parameter"
type: docs
weight: 1650
url: /de/net/aspose.barcode.generation/qrparameters/
---
## QrParameters class

QR-Parameter.

```csharp
public class QrParameters
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/qrparameters/aspectratio/) { get; set; } | Höhen/Breiten-Verhältnis des 2D‑BarCode‑Moduls. |
| [ECIEncoding](../../aspose.barcode.generation/qrparameters/eciencoding/) { get; set; } | Extended Channel Interpretation‑Bezeichner. Sie werden verwendet, um dem Barcode‑Leser Details zu den verwendeten Referenzen für die Kodierung der Daten im Symbol mitzuteilen. Die aktuelle Implementierung enthält alle bekannten Zeichensatzkodierungen. Nicht unterstützt von MicroQR. |
| [EncodeGS1SeparatorInByteMode](../../aspose.barcode.generation/qrparameters/encodegs1separatorinbytemode/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob GS1‑Sonderzeichen im Byte‑Modus für QR‑ und RectMicroQR‑Barcodes codiert werden sollen. |
| [EncodeMode](../../aspose.barcode.generation/qrparameters/encodemode/) { get; set; } | QR‑Symboltyp des Kodierungsmodus von BarCode. Standardwert: QREncodeMode.Auto. |
| [ErrorLevel](../../aspose.barcode.generation/qrparameters/errorlevel/) { get; set; } | Stufe der Reed‑Solomon‑Fehlerkorrektur für QR-, MicroQR‑ und RectMicroQR‑Barcodes. Von niedrig nach hoch: LevelL, LevelM, LevelQ, LevelH. Siehe QRErrorLevel. |
| [MicroQRVersion](../../aspose.barcode.generation/qrparameters/microqrversion/) { get; set; } | Version des MicroQR‑Codes. Von Version M1 bis Version M4. Standardwert ist MicroQRVersion.Auto. |
| [RectMicroQrVersion](../../aspose.barcode.generation/qrparameters/rectmicroqrversion/) { get; set; } | Version des RectMicroQR‑Codes. Von Version R7x59 bis Version R17x139. Standardwert ist RectMicroQRVersion.Auto. |
| [StructuredAppend](../../aspose.barcode.generation/qrparameters/structuredappend/) { get; set; } | QR‑Parameter für strukturiertes Anhängen. Der strukturierte Anfügemodus wird von MicroQR‑ und RectMicroQR‑Barcodes nicht unterstützt. |
| [Version](../../aspose.barcode.generation/qrparameters/version/) { get; set; } | Version des QR‑Codes. Von Version1 bis Version40. Standardwert ist QRVersion.Auto. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/qrparameters/tostring/)() | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses `QrParameters` zurück. |

### Siehe auch

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


