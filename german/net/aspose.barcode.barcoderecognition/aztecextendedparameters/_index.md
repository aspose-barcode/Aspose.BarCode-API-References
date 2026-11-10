---
title: "Klasse AztecExtendedParameters"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.BarCodeRecognition.AztecExtendedParameters Klasse. Speichert spezielle Daten des erkannten Aztec-Barcodes."
type: docs
weight: 40
url: /de/net/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class

Speichert spezielle Daten des erkannten Aztec‑Barcodes.

```csharp
public sealed class AztecExtendedParameters : BaseExtendedParameters
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Prüft, ob alle Parameter nur Standardwerte haben |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/aztecextendedparameters/isreaderinitialization/) { get; } | Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder Neuprogrammierung des Barcodelesers zu interpretieren. Standardwert ist false. |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendbarcodeid/) { get; } | Liefert die ID des Aztec Structured Append Mode Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode-Anzahl sein. Der Standardwert ist 0. |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendbarcodescount/) { get; } | Liefert die Anzahl der Aztec Structured Append Mode Barcodes. Der Standardwert ist 0. Die Anzahl muss ein Wert zwischen 1 und 26 sein. |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendfileid/) { get; } | Liefert die Datei-ID des Aztec Structured Append Mode. Der Standardwert ist eine leere Zeichenkette. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/aztecextendedparameters/equals/)(object) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `AztecExtendedParameters`-Wert entspricht. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/aztecextendedparameters/gethashcode/)() | Gibt den Hash‑Code für diese Instanz zurück. |
| override [ToString](../../aspose.barcode.barcoderecognition/aztecextendedparameters/tostring/)() | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses `AztecExtendedParameters` zurück. |
| [operator ==](../../aspose.barcode.barcoderecognition/aztecextendedparameters/op_equality/) | Gibt einen Wert zurück, der angibt, ob der erste `AztecExtendedParameters`-Wert dem zweiten entspricht. |
| [operator !=](../../aspose.barcode.barcoderecognition/aztecextendedparameters/op_inequality/) | Gibt einen Wert zurück, der angibt, ob der erste `AztecExtendedParameters`-Wert vom zweiten abweicht. |

## Beispiele

Dieses Beispiel zeigt, wie man rohe Aztec-Werte erhält

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Aztec))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("Aztec barcode ID: " + result.Extended.Aztec.StructuredAppendBarcodeId);
        Console.WriteLine("Aztec barcodes count: " + result.Extended.Aztec.StructuredAppendBarcodesCount);
        Console.WriteLine("Aztec file ID: " + result.Extended.Aztec.StructuredAppendFileId);
        Console.WriteLine("Aztec is reader initialization: " + result.Extended.Aztec.IsReaderInitialization);
    }
}
```

### Siehe auch

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


