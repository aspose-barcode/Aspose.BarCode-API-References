---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeReader class"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeReader class. BarCodeReader kapselt ein Bild, das einen oder mehrere Barcodes enthalten kann, und kann anschließend die ReadBarCodes-Operation ausführen, um Barcodes in C++ zu erkennen."
type: docs
weight: 500
url: /de/cpp/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class


[BarCodeReader](./) encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes.

```cpp
class BarCodeReader : public System::IDisposable
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [Abort](./abort/)() | Funktion fordert die Beendigung der aktuellen Erkennungssitzung von einem anderen Thread an. Abort ist eine nicht abbruchbare Methode und gibt die Kontrolle unmittelbar nach dem Aufruf zurück. Die Methode sollte verwendet werden, wenn der Erkennungsprozess zu lange dauert. |
| [BarCodeReader](./barcodereader/)() | Initialisiert eine neue Instanz der [BarCodeReader](./)-Klasse mit Standardwerten. Erfordert das Setzen eines Bildes (SetBitmapImage()), bevor die Methode [ReadBarCodes()](./readbarcodes/) aufgerufen wird. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>) | Initialisiert eine neue Instanz der [BarCodeReader](./)-Klasse aus einem Bild. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initialisiert eine neue Instanz der [BarCodeReader](./)-Klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::SharedPtr\<BaseDecodeType\>) | Initialisiert eine neue Instanz der [BarCodeReader](./)-Klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initialisiert eine neue Instanz der [BarCodeReader](./)-Klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | Initialisiert eine neue Instanz der [BarCodeReader](./)-Klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initialisiert eine neue Instanz der [BarCodeReader](./)-Klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | Initialisiert eine neue Instanz der [BarCodeReader](./)-Klasse. |
| [BarCodeReader](./barcodereader/)(System::String) | Initialisiert eine neue Instanz der [BarCodeReader](./)-Klasse aus einer Datei. |
| [BarCodeReader](./barcodereader/)(System::String, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initialisiert eine neue Instanz der [BarCodeReader](./)-Klasse. |
| [BarCodeReader](./barcodereader/)(System::String, System::SharedPtr\<BaseDecodeType\>) | Initialisiert eine neue Instanz der [BarCodeReader](./)-Klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>) | Initialisiert eine neue Instanz der [BarCodeReader](./)-Klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<BaseDecodeType\>) | Initialisiert eine neue Instanz der [BarCodeReader](./)-Klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initialisiert eine neue Instanz der [BarCodeReader](./)-Klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | Initialisiert eine neue Instanz der [BarCodeReader](./)-Klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initialisiert eine neue Instanz der [BarCodeReader](./)-Klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | Initialisiert eine neue Instanz der [BarCodeReader](./)-Klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initialisiert eine neue Instanz der [BarCodeReader](./)-Klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::SharedPtr\<BaseDecodeType\>) | Initialisiert eine neue Instanz der [BarCodeReader](./)-Klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initialisiert eine neue Instanz der [BarCodeReader](./)-Klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>) | Initialisiert eine neue Instanz der [BarCodeReader](./)-Klasse aus einem Luminanz-Frame. |
| [Dispose](./dispose/)() override | Ressource freigeben |
| [ExportToXml](./exporttoxml/)(System::String) | Exportiert die Eigenschaften von [BarCode](../../aspose.barcode/) in die angegebene XML-Datei |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | Exportiert die Eigenschaften von [BarCode](../../aspose.barcode/) in den angegebenen XML-Stream |
| [get_BarCodeReadType](./get_barcodereadtype/)() | Liefert den für die Erkennung verwendeten Barcode-Dekodierungstyp. Muss vor dem Aufruf von [ReadBarCodes](./readbarcodes/) festgelegt werden. |
| [get_BarcodeSettings](./get_barcodesettings/)() | Die wichtigsten [BarCode](../../aspose.barcode/)-Dekodierungsparameter. Enthält Parameter, die Einfluss auf die erkannten Daten haben. |
| [get_FoundBarCodes](./get_foundbarcodes/)() | Liefert das Array erkannter [BarCodeResult](../barcoderesult/)s |
| [get_FoundCount](./get_foundcount/)() | Ermittelt die Anzahl erkannter Barcodes |
| static [get_ProcessorSettings](./get_processorsettings/)() | Ermittelt die Einstellung zur Nutzung von Prozessorkernen. |
| [get_QualitySettings](./get_qualitysettings/)() | [QualitySettings](../qualitysettings/) ermöglicht es, die Erkennungsqualität und -geschwindigkeit manuell zu konfigurieren. Sie können [QualitySettings](../qualitysettings/) schnell über integrierte Voreinstellungen einrichten: HighPerformance, NormalQuality, HighQuality, MaxBarCodes oder Sie können einzelne Optionen manuell konfigurieren. Der Standardwert von [QualitySettings](../qualitysettings/) ist NormalQuality. |
| [get_Timeout](./get_timeout/)() | Ermittelt den Timeout des Erkennungsprozesses in Millisekunden. |
| static [ImportFromXml](./importfromxml/)(System::String) | Importiert die Eigenschaften von [BarCode](../../aspose.barcode/) aus der angegebenen XML-Datei und wendet sie auf die aktuelle Instanz von [BarCodeReader](./) an. |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | Importiert die Eigenschaften von [BarCode](../../aspose.barcode/) aus dem angegebenen XML-Stream und wendet sie auf die aktuelle Instanz von [BarCodeReader](./) an. |
| [ReadBarCodes](./readbarcodes/)() | Liest [BarCodeResult](../barcoderesult/)s aus dem Bild. |
| [set_BarCodeReadType](./set_barcodereadtype/)(System::SharedPtr\<BaseDecodeType\>) | Legt den für die Erkennung verwendeten Barcode-Dekodierungstyp fest. Muss gesetzt werden, bevor [ReadBarCodes](./readbarcodes/) aufgerufen wird. |
| [set_QualitySettings](./set_qualitysettings/)(System::SharedPtr\<Aspose::BarCode::BarCodeRecognition::QualitySettings\>) | [QualitySettings](../qualitysettings/) ermöglicht es, die Erkennungsqualität und -geschwindigkeit manuell zu konfigurieren. Sie können [QualitySettings](../qualitysettings/) schnell über integrierte Voreinstellungen einrichten: HighPerformance, NormalQuality, HighQuality, MaxBarCodes oder Sie können einzelne Optionen manuell konfigurieren. Der Standardwert von [QualitySettings](../qualitysettings/) ist NormalQuality. |
| [set_Timeout](./set_timeout/)(int32_t) | Legt den Timeout des Erkennungsprozesses in Millisekunden fest. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>) | Setzt das Bitmap-Bild für die Erkennung. Muss vor der Methode [ReadBarCodes()](./readbarcodes/) aufgerufen werden. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | Setzt das Bitmap-Bild und die Bereiche für die Erkennung. Muss vor der Methode [ReadBarCodes()](./readbarcodes/) aufgerufen werden. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle) | Setzt das Bitmap-Bild und den Bereich für die Erkennung. Muss vor der Methode [ReadBarCodes()](./readbarcodes/) aufgerufen werden. |
| [SetBarCodeImage](./setbarcodeimage/)(System::String) | Setzt die Bilddatei für die Erkennung. Muss vor der Methode [ReadBarCodes()](./readbarcodes/) aufgerufen werden. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::IO::Stream\>) | Setzt den Bild-Stream für die Erkennung. Muss vor der Methode [ReadBarCodes()](./readbarcodes/) aufgerufen werden. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle) | Setzt den Luminanzrahmen und den Bereich für die Erkennung. Muss vor der Methode [ReadBarCodes](./readbarcodes/) aufgerufen werden. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | Setzt den Luminanzrahmen und die Bereiche für die Erkennung. Muss vor der Methode [ReadBarCodes](./readbarcodes/) aufgerufen werden. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>) | Setzt den Luminanzrahmen für die Erkennung. Muss vor der Methode [ReadBarCodes](./readbarcodes/) aufgerufen werden. |
| [SetBarCodeReadType](./setbarcodereadtype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | Setzt das Typ-Array von [SingleDecodeType](../singledecodetype/) für die Erkennung. Muss vor der Methode [ReadBarCodes()](./readbarcodes/) aufgerufen werden. |
## Hinweise


Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes erkannt werden.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

## Siehe auch

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
