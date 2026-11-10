---
title: "Klasse BarcodeGenerator"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Generation.BarcodeGenerator Klasse. BarcodeGenerator zur Erzeugung von Barcode-Bildern im Backend"
type: docs
weight: 1000
url: /de/net/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class

BarcodeGenerator zur Erzeugung von Barcode‑Bildern im Backend.

unterstützte Symbologien: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR-Code ...

```csharp
public sealed class BarcodeGenerator : Component
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [BarcodeGenerator](barcodegenerator/#constructor)(BaseEncodeType) | Erstellt eine Instanz von BarcodeGenerator. |
| [BarcodeGenerator](barcodegenerator/#constructor_1)(BaseEncodeType, string) | Erstellt eine Instanz von BarcodeGenerator. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BarcodeType](../../aspose.barcode.generation/barcodegenerator/barcodetype/) { get; set; } | Barcode‑Symbologie‑Typ. |
| [CodeText](../../aspose.barcode.generation/barcodegenerator/codetext/) { get; set; } | Zu codierender Text. |
| [Parameters](../../aspose.barcode.generation/barcodegenerator/parameters/) { get; } | Generierungsparameter. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml)(Stream) | Importiert BarCode‑Eigenschaften aus dem angegebenen XML‑Stream und erstellt eine BarcodeGenerator‑Instanz. |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml_1)(string) | Importiert BarCode‑Eigenschaften aus der angegebenen XML‑Datei und erstellt eine BarcodeGenerator‑Instanz. |
| [DrawWpf](../../aspose.barcode.generation/barcodegenerator/drawwpf/)(DrawingContext) | Zeichnet das Barcode‑Bild auf einer WPF‑Leinwand. |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml)(Stream) | Exportiert BarCode‑Eigenschaften in den angegebenen XML‑Stream |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml_1)(string) | Exportiert BarCode-Eigenschaften in die angegebene XML-Datei. |
| [GenerateBarCodeImage](../../aspose.barcode.generation/barcodegenerator/generatebarcodeimage/)() | Erzeugt das Barcode‑Bild mit den aktuellen Einstellungen. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_1)(string) | Speichert das Barcode‑Bild in einer bestimmten Datei. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save)(Stream, BarCodeImageFormat) | Speichert das Barcode‑Bild in einen Stream in einem bestimmten Format. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_2)(string, BarCodeImageFormat) | Speichert das Barcode‑Bild in einer bestimmten Datei in einem bestimmten Format. |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext)(byte[]) | Setzt den Codetext als Byte‑Sequenz. |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext_1)(string, Encoding) | Kodiert den Unicode **codeText** in eine Byte‑Sequenz unter Verwendung der angegebenen **encoding**. UTF-8 ist das am häufigsten verwendete Encoding. Unterstützt das Encoding dies, fügt die Funktion automatisch ein [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) ein. |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext_2)(string, Encoding, bool) | Kodiert den Unicode **codeText** in eine Byte‑Sequenz unter Verwendung der angegebenen **encoding**. UTF-8 ist das am häufigsten verwendete Encoding. Unterstützt das Encoding dies und ist **insertBOM** auf `true` gesetzt, fügt die Funktion ein [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) hinzu. |

## Beispiele

Dieses Beispiel zeigt, wie man ein Barcode‑Bild erstellt und speichert.

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

### Siehe auch

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


