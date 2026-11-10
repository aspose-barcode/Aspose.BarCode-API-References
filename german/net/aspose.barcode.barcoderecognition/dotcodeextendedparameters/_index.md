---
title: "Klasse DotCodeExtendedParameters"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.BarCodeRecognition.DotCodeExtendedParameters Klasse. Speichert spezielle Daten des erkannten DotCode-Barcodes"
type: docs
weight: 250
url: /de/net/aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
## DotCodeExtendedParameters class

Speichert spezielle Daten des erkannten DotCode‑Barcodes.

```csharp
public sealed class DotCodeExtendedParameters : BaseExtendedParameters
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Prüft, ob alle Parameter nur Standardwerte haben |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/isreaderinitialization/) { get; } | Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder Neuprogrammierung des Barcodelesers zu interpretieren. Standardwert ist false. |
| [StructuredAppendModeBarcodeId](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/structuredappendmodebarcodeid/) { get; } | Ermittelt die ID des DotCode Structured Append‑Modus‑Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode‑Anzahl sein. Standardwert ist -1. |
| [StructuredAppendModeBarcodesCount](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/structuredappendmodebarcodescount/) { get; } | Ermittelt die Anzahl der DotCode Structured Append‑Modus‑Barcodes. Standardwert ist -1. Die Anzahl muss ein Wert von 1 bis 35 sein. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/equals/)(object) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `DotCodeExtendedParameters`‑Wert entspricht. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/gethashcode/)() | Gibt den Hash‑Code für diese Instanz zurück. |
| override [ToString](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/tostring/)() | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses `DotCodeExtendedParameters` zurück. |
| [operator ==](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/op_equality/) | Gibt einen Wert zurück, der angibt, ob der erste `DotCodeExtendedParameters`‑Wert dem zweiten entspricht. |
| [operator !=](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/op_inequality/) | Gibt einen Wert zurück, der angibt, ob der erste `DotCodeExtendedParameters`‑Wert vom zweiten abweicht. |

## Beispiele

Dieses Beispiel zeigt, wie man rohe DotCode‑Werte erhält

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DotCode))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DotCode barcode ID: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodeId);
        Console.WriteLine("DotCode barcodes count: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodesCount);
    }
}
```

### Siehe auch

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


