---
title: "Klasse DataMatrixExtendedParameters"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.BarCodeRecognition.DataMatrixExtendedParameters‑Klasse. Speichert spezielle Daten des erkannten DataMatrix‑Barcodes"
type: docs
weight: 220
url: /de/net/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class

Speichert spezielle Daten des erkannten DataMatrix‑Barcodes.

```csharp
public sealed class DataMatrixExtendedParameters : BaseExtendedParameters
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Prüft, ob alle Parameter nur Standardwerte haben |
| [IsReaderProgramming](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/isreaderprogramming/) { get; } | Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder Neuprogrammierung des Barcodelesers zu interpretieren. Standardwert ist false. |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodeid/) { get; } | Liest die ID des DataMatrix Structured Append Mode Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode-Anzahl sein. Der Standardwert ist -1. |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodescount/) { get; } | Liest die Anzahl der DataMatrix Structured Append Mode Barcodes. Der Standardwert ist -1. Die Anzahl muss ein Wert von 1 bis 35 sein. |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendfileid/) { get; } | Liest die ID des DataMatrix Structured Append Mode Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode-Anzahl sein. Der Standardwert ist -1. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/equals/)(object) | Gibt einen Wert zurück, der angibt, ob diese Instanz gleich einem angegebenen `DataMatrixExtendedParameters`‑Wert ist. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/gethashcode/)() | Gibt den Hash‑Code für diese Instanz zurück. |
| override [ToString](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/tostring/)() | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses `DataMatrixExtendedParameters` zurück. |
| [operator ==](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_equality/) | Gibt einen Wert zurück, der angibt, ob der erste `DataMatrixExtendedParameters`‑Wert dem zweiten entspricht. |
| [operator !=](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_inequality/) | Gibt einen Wert zurück, der angibt, ob der erste `DataMatrixExtendedParameters`‑Wert vom zweiten abweicht. |

## Beispiele

Dieses Beispiel zeigt, wie man rohe DataMatrix‑Werte erhält

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DataMatrix))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DataMatrix barcode ID: " + result.Extended.DataMatrix.StructuredAppendBarcodeId);
        Console.WriteLine("DataMatrix barcodes count: " + result.Extended.DataMatrix.StructuredAppendBarcodesCount);
        Console.WriteLine("DataMatrix file ID: " + result.Extended.DataMatrix.StructuredAppendFileId);
        Console.WriteLine("DataMatrix is reader programming: " + result.Extended.DataMatrix.IsReaderProgramming);
    }
}
```

### Siehe auch

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


