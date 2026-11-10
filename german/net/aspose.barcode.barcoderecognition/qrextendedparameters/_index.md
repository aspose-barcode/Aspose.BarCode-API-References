---
title: "Klasse QRExtendedParameters"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.BarCodeRecognition.QRExtendedParameters Klasse. Speichert QR Structured Append‑Informationen des erkannten Barcodes."
type: docs
weight: 350
url: /de/net/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class

Speichert QR‑Structured‑Append‑Informationen des erkannten Barcodes.

```csharp
public sealed class QRExtendedParameters : BaseExtendedParameters
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ErrorLevel](../../aspose.barcode.barcoderecognition/qrextendedparameters/errorlevel/) { get; } | Reed‑Solomon‑Fehlerkorrekturstufe des erkannten Barcodes. Von niedrig nach hoch: LevelL, LevelM, LevelQ, LevelH. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Prüft, ob alle Parameter nur Standardwerte haben |
| [MicroQRVersion](../../aspose.barcode.barcoderecognition/qrextendedparameters/microqrversion/) { get; } | Version des erkannten MicroQR‑Codes. Von M1 bis M4. |
| [RectMicroQRVersion](../../aspose.barcode.barcoderecognition/qrextendedparameters/rectmicroqrversion/) { get; } | Version des erkannten RectMicroQR‑Codes. Von R7x43 bis R17x139. |
| [StructuredAppendModeBarCodeIndex](../../aspose.barcode.barcoderecognition/qrextendedparameters/structuredappendmodebarcodeindex/) { get; } | Liefert den Index des QR Structured Append‑Modus‑Barcodes. Der Index beginnt bei 0. Standardwert ist -1. |
| [StructuredAppendModeBarCodesQuantity](../../aspose.barcode.barcoderecognition/qrextendedparameters/structuredappendmodebarcodesquantity/) { get; } | Liefert die Anzahl der QR Structured Append‑Modus‑Barcodes. Standardwert ist -1. |
| [StructuredAppendModeParityData](../../aspose.barcode.barcoderecognition/qrextendedparameters/structuredappendmodeparitydata/) { get; } | Liefert die Paritätsdaten des QR Structured Append‑Modus. Standardwert ist -1. |
| [Version](../../aspose.barcode.barcoderecognition/qrextendedparameters/version/) { get; } | Version des erkannten QR-Codes. Von Version1 bis Version40. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/qrextendedparameters/equals/)(object) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `QRExtendedParameters`‑Wert entspricht. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/qrextendedparameters/gethashcode/)() | Gibt den Hash‑Code für diese Instanz zurück. |
| override [ToString](../../aspose.barcode.barcoderecognition/qrextendedparameters/tostring/)() | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses `QRExtendedParameters` zurück. |
| [operator ==](../../aspose.barcode.barcoderecognition/qrextendedparameters/op_equality/) | Gibt einen Wert zurück, der angibt, ob der erste `QRExtendedParameters`‑Wert dem zweiten entspricht. |
| [operator !=](../../aspose.barcode.barcoderecognition/qrextendedparameters/op_inequality/) | Gibt einen Wert zurück, der angibt, ob der erste `QRExtendedParameters`‑Wert vom zweiten abweicht. |

## Beispiele

Dieses Beispiel zeigt, wie man QR Structured Append‑Daten erhält.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.QR))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex);
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.QR)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex)
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData)
    Next
End Using
```

### Siehe auch

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


