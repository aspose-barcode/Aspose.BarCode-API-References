---
title: "Klasse QualitySettings"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.BarCodeRecognition.QualitySettings Klasse. QualitySettings ermöglicht die manuelle Konfiguration von Erkennungsqualität und -geschwindigkeit. Sie können QualitySettings schnell mit eingebetteten Voreinstellungen HighPerformance, NormalQuality, HighQuality, MaxQuality einrichten oder einzelne Optionen manuell konfigurieren. Der Standardwert von QualitySettings ist NormalQuality."
type: docs
weight: 370
url: /de/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

QualitySettings ermöglicht es, die Erkennungsqualität und -geschwindigkeit manuell zu konfigurieren. Sie können QualitySettings schnell mit eingebetteten Voreinstellungen einrichten: HighPerformance, NormalQuality, HighQuality, MaxQuality, oder Sie können die einzelnen Optionen manuell konfigurieren. Der Standardwert von QualitySettings ist NormalQuality.

```csharp
public sealed class QualitySettings
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance/) { get; } | HighPerformance‑Voreinstellung für die Erkennungsqualität. Hochwertige Barcodes werden in diesem Modus gut erkannt. |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality/) { get; } | HighQuality‑Voreinstellung für die Erkennungsqualität. Diese Voreinstellung ist für Barcodes niedriger Qualität entwickelt. Sie ermöglicht das Erkennen stark beschädigter Barcodes. |
| static [MaxQuality](../../aspose.barcode.barcoderecognition/qualitysettings/maxquality/) { get; } | MaxQuality‑Voreinstellung für die Erkennungsqualität. Diese Voreinstellung ist entwickelt, um alle möglichen Barcodes zu erkennen, sogar fehlerhafte Barcodes. |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality/) { get; } | NormalQuality Erkennungsqualitäts‑Voreinstellung. Geeignet für die meisten Barcodes |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes/) { get; set; } | Ermöglicht der Engine, Barcodes zu erkennen, die eine falsche Prüfsumme oder falsche Werte haben. Der Modus kann verwendet werden, um beschädigte Barcodes mit falschem Text zu erkennen. |
| [BarcodeQuality](../../aspose.barcode.barcoderecognition/qualitysettings/barcodequality/) { get; set; } | Modus, der Methoden aktiviert, um Barcode‑Elemente mit der ausgewählten Qualität zu erkennen. Ein Barcode‑Element mit niedrigerer Qualität erfordert aufwändigere Methoden, was die Erkennung verlangsamt. |
| [ComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/complexbackground/) { get; set; } | Modus, der die zusätzliche Erkennung von Farbbarcodes in Farbbildern ein- oder ausschaltet. |
| [Deconvolution](../../aspose.barcode.barcoderecognition/qualitysettings/deconvolution/) { get; set; } | Deconvolution‑Modus (Bildrestaurierung), der das Niveau der Bilddegradation definiert. Ursprünglich ist Deconvolution eine Funktion, die ein durch eine natürliche Funktion wie Unschärfe (Blur) degradierte (konvolutierte) Bild wiederherstellen kann, das bei der Aufnahme mit einer Kamera entsteht. Da wir die Bildfunktion, die das Bild beschädigt, nicht erkennen können, müssen wir die am besten bekannten Funktionen wie Schärfen oder mathematische Morphologie prüfen. |
| [InverseImage](../../aspose.barcode.barcoderecognition/qualitysettings/inverseimage/) { get; set; } | Modus, der die zusätzliche Erkennung von Barcodes in Bildern mit invertierten Farben (Luminanz) ein- oder ausschaltet. |
| [MinimalXDimension](../../aspose.barcode.barcoderecognition/qualitysettings/minimalxdimension/) { get; set; } | Minimale Größe von XDimension in Pixeln, die mit UseMinimalXDimension verwendet wird. |
| [XDimension](../../aspose.barcode.barcoderecognition/qualitysettings/xdimension/) { get; set; } | Erkennungsmodus, der die Größe (von 1 bis unendlich) des minimalen Barcode‑Elements festlegt: Matrixzelle oder Strich. |

## Beispiele

Dieses Beispiel zeigt, wie man QualitySettings mit BarCodeReader verwendet

```csharp
[C#]
//HighPerformance-Erkennungsmodus setzen
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//HighQuality-Erkennungsmodus setzen
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//HighPerformance-Erkennungsmodus für kleinformatige Barcodes setzen
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//HighPerformance-Erkennungsmodus für Barcodes niedriger Qualität setzen
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}    
```

### Siehe auch

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


