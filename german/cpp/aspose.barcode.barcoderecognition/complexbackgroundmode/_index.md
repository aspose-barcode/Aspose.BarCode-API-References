---
title: "enum"
linktitle: "ComplexBackgroundMode"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Wie man das enum in C++ verwendet."
type: docs
weight: 3700
url: /de/cpp/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enum




```cpp
enum class ComplexBackgroundMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | 0 | Derzeit identisch mit Deaktiviert. Deaktiviert die zusätzliche Erkennung von Farbbarkodes in Farbbildern. |
| Deaktiviert | 1 | Deaktiviert die zusätzliche Erkennung von Farbbarkodes in Farbbildern. |
| Aktiviert | 2 | Aktiviert die zusätzliche Erkennung von Farbbarkodes in Farbbildern. |

## Hinweise


Modus, der die zusätzliche Erkennung von Farbcodes in Farbbildern ein- oder ausschaltet.

Dieses Beispiel zeigt, wie man den ComplexBackground‑Modus verwendet
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Siehe auch

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
