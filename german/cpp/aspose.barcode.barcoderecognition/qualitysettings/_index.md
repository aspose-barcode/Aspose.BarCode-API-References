---
title: "Aspose::BarCode::BarCodeRecognition::QualitySettings Klasse"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::BarCodeRecognition::QualitySettings Klasse. QualitySettings ermöglicht es, die Erkennungsqualität und -geschwindigkeit manuell zu konfigurieren. Sie können QualitySettings schnell mit eingebetteten Voreinstellungen einrichten: HighPerformance, NormalQuality, HighQuality, MaxQuality oder Sie können einzelne Optionen manuell konfigurieren. Der Standardwert von QualitySettings ist NormalQuality in C++."
type: docs
weight: 3100
url: /de/cpp/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class


[QualitySettings](./) allows to configure recognition quality and speed manually. You can quickly set up [QualitySettings](./) with embedded presets: HighPerformance, NormalQuality, HighQuality, MaxQuality or you can manually configure separate options. Default value of [QualitySettings](./) is NormalQuality.

```cpp
class QualitySettings : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_AllowIncorrectBarcodes](./get_allowincorrectbarcodes/)() const | Ermöglicht der Engine, Strichcodes zu erkennen, die eine falsche Prüfsumme oder falsche Werte haben. Der Modus kann verwendet werden, um beschädigte Strichcodes mit falschem Text zu erkennen. |
| [get_BarcodeQuality](./get_barcodequality/)() const | Modus, der Methoden aktiviert, um Strichcode-Elemente mit der ausgewählten Qualität zu erkennen. Ein Strichcode-Element mit niedrigerer Qualität erfordert aufwändigere Methoden, was die Erkennung verlangsamt. |
| [get_ComplexBackground](./get_complexbackground/)() const | Modus, der die zusätzliche Erkennung von Farbcodes in Farbbildern ein- oder ausschaltet. |
| [get_Deconvolution](./get_deconvolution/)() const | Deconvolution (Bildrestaurierung) Modus, der das Niveau der Bilddegradation definiert. Ursprünglich ist Deconvolution eine Funktion, die ein durch eine natürliche Funktion wie Unschärfe degradierte (konvolutierte) Bild wiederherstellen kann, das bei der Aufnahme mit einer Kamera entsteht. Da wir die Bildfunktion, die das Bild beschädigt, nicht erkennen können, müssen wir die am besten bekannten Funktionen wie Schärfen oder mathematische Morphologie prüfen. |
| static [get_HighPerformance](./get_highperformance/)() | HighPerformance Erkennungsqualitätsvorgabe. Hochwertige Strichcodes werden in diesem Modus gut erkannt. |
| static [get_HighQuality](./get_highquality/)() | HighQuality Erkennungsqualitätsvorgabe. Diese Vorgabe wurde für Strichcodes niedriger Qualität entwickelt. Ermöglicht das Erkennen stark beschädigter Strichcodes. |
| [get_InverseImage](./get_inverseimage/)() const | Modus, der die zusätzliche Erkennung von Barcodes auf Bildern mit invertierten Farben (Luminanz) aktiviert oder deaktiviert. |
| static [get_MaxQuality](./get_maxquality/)() | MaxQuality-Erkennungsqualitätsvorgabe. Diese Vorgabe wurde entwickelt, um alle möglichen Barcodes zu erkennen, sogar fehlerhafte Barcodes. |
| [get_MinimalXDimension](./get_minimalxdimension/)() const | Minimale Größe von XDimension in Pixel, die mit UseMinimalXDimension verwendet wird. |
| static [get_NormalQuality](./get_normalquality/)() | NormalQuality-Erkennungsqualitätsvorgabe. Geeignet für die meisten Barcodes. |
| [get_XDimension](./get_xdimension/)() const | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) Modus, der die Größe (von 1 bis unendlich) des minimalen Barcode-Elements festlegt: Matrixzelle oder Strich. |
| [set_AllowIncorrectBarcodes](./set_allowincorrectbarcodes/)(bool) | Ermöglicht der Engine, Strichcodes zu erkennen, die eine falsche Prüfsumme oder falsche Werte haben. Der Modus kann verwendet werden, um beschädigte Strichcodes mit falschem Text zu erkennen. |
| [set_BarcodeQuality](./set_barcodequality/)(BarcodeQualityMode) | Modus, der Methoden aktiviert, um Strichcode-Elemente mit der ausgewählten Qualität zu erkennen. Ein Strichcode-Element mit niedrigerer Qualität erfordert aufwändigere Methoden, was die Erkennung verlangsamt. |
| [set_ComplexBackground](./set_complexbackground/)(ComplexBackgroundMode) | Modus, der die zusätzliche Erkennung von Farbcodes in Farbbildern ein- oder ausschaltet. |
| [set_Deconvolution](./set_deconvolution/)(DeconvolutionMode) | Deconvolution (Bildrestaurierung) Modus, der das Niveau der Bilddegradation definiert. Ursprünglich ist Deconvolution eine Funktion, die ein durch eine natürliche Funktion wie Unschärfe degradierte (konvolutierte) Bild wiederherstellen kann, das bei der Aufnahme mit einer Kamera entsteht. Da wir die Bildfunktion, die das Bild beschädigt, nicht erkennen können, müssen wir die am besten bekannten Funktionen wie Schärfen oder mathematische Morphologie prüfen. |
| [set_InverseImage](./set_inverseimage/)(InverseImageMode) | Modus, der die zusätzliche Erkennung von Barcodes auf Bildern mit invertierten Farben (Luminanz) aktiviert oder deaktiviert. |
| [set_MinimalXDimension](./set_minimalxdimension/)(float) | Minimale Größe von XDimension in Pixel, die mit UseMinimalXDimension verwendet wird. |
| [set_XDimension](./set_xdimension/)(XDimensionMode) | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) Modus, der die Größe (von 1 bis unendlich) des minimalen Barcode-Elements festlegt: Matrixzelle oder Strich. |
## Hinweise


Dieses Beispiel zeigt, wie man [QualitySettings](./) mit [BarCodeReader](../barcodereader/) verwendet.
```cpp
[C#]
//HighPerformance-Erkennungsmodus festlegen
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//HighQuality-Erkennungsmodus festlegen
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//HighPerformance-Erkennungsmodus für kleinformatige Barcodes festlegen
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//HighPerformance-Erkennungsmodus für Barcodes niedriger Qualität festlegen
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Siehe auch

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
