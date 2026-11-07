---
title: "Methode"
linktitle: "GetCodeText"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. Ruft den Code-Text mit Kodierung in C++ ab."
type: docs
weight: 1000
url: /de/cpp/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult::GetCodeText method


Liefert den Code‑Text mit Kodierung.

```cpp
System::String Aspose::BarCode::BarCodeRecognition::BarCodeResult::GetCodeText(System::SharedPtr<System::Text::Encoding> encoding)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Kodierung | System::SharedPtr\<System::Text::Encoding\> | Die Kodierung für den Code-Text. |

### ReturnValue

Eine Zeichenkette, die erkannten Code-Text enthält.
## Hinweise



Dieses Beispiel zeigt, wie **GetCodeText** verwendet wird:


```cpp
[C#]
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
    {
        gen.SetCodeText("車種名", Encoding.GetEncoding(932));
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

## Siehe auch

* Class [BarCodeResult](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
