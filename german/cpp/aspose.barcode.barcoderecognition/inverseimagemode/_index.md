---
title: "enum"
linktitle: "InverseImageMode"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Wie man das enum in C++ verwendet."
type: docs
weight: 3900
url: /de/cpp/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enum




```cpp
enum class InverseImageMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | 0 | Deaktiviert die zusätzliche Erkennung von Barcodes auf inversen Bildern für alle Barcode-Typen außer dem [QR](../../aspose.barcode.barcoderecognition.qr/) Code. |
| Deaktiviert | 1 | Deaktiviert die zusätzliche Erkennung von Barcodes auf inversen Bildern. |
| Aktiviert | 2 | Aktiviert die zusätzliche Erkennung von Barcodes auf inversen Bildern |

## Hinweise


Modus, der die zusätzliche Erkennung von Barcodes auf Bildern mit invertierten Farben (Luminanz) aktiviert oder deaktiviert.

Dieses Beispiel zeigt, wie der InverseImage-Modus verwendet wird
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Siehe auch

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
