---
title: "Methode"
linktitle: "get_OnlyRequestedTypes"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " method. Gibt nur Barcode‑Typen zurück, die ausdrücklich für die Erkennung angegeben wurden. Wenn aktiviert, werden erkannte Barcodes anderer kompatibler oder äquivalenter Typen herausgefiltert. Der Standardwert ist false in C++."
type: docs
weight: 500
url: /de/cpp/aspose.barcode.barcoderecognition/barcodesettings/get_onlyrequestedtypes/
---
## BarcodeSettings::get_OnlyRequestedTypes method


Gibt nur Barcode‑Typen zurück, die ausdrücklich für die Erkennung angegeben wurden. Wenn aktiviert, werden erkannte Barcodes anderer kompatibler oder äquivalenter Typen herausgefiltert. Standardwert ist false.

```cpp
bool Aspose::BarCode::BarCodeRecognition::BarcodeSettings::get_OnlyRequestedTypes() const
```

## Hinweise


Dieses Beispiel zeigt, wie man Erkennungsergebnisse ausschließlich auf angeforderte Barcode‑Typen beschränkt
```cpp
[C#]
//EAN13-Barcode erzeugen
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//Nur UPCA-Barcodes erkennen (keine Ergebnisse, weil die Quelle EAN13 ist)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//Kompatible Typen erkennen: EAN13, UPCA, ISSN, ISMN, ISBN (EAN13 wird als UPCA-Äquivalent zurückgegeben)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```


Gibt nur Barcode‑Typen zurück, die ausdrücklich für die Erkennung angegeben wurden. Der Standardwert ist false.
## Siehe auch

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
