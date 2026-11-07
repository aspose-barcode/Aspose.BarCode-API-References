---
title: "methode"
linktitle: "get_OnlyRequestedTypes"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. Retourneert alleen barcode-typen die expliciet zijn opgegeven voor herkenning. Wanneer ingeschakeld, worden herkende barcodes van andere compatibele of equivalente typen gefilterd. Standaardwaarde is false in C++."
type: docs
weight: 500
url: /nl/cpp/aspose.barcode.barcoderecognition/barcodesettings/get_onlyrequestedtypes/
---
## BarcodeSettings::get_OnlyRequestedTypes method


Retourneert alleen barcode‑typen die expliciet zijn opgegeven voor herkenning. Wanneer ingeschakeld, worden herkende barcodes van andere compatibele of equivalente typen gefilterd. Standaardwaarde is false.

```cpp
bool Aspose::BarCode::BarCodeRecognition::BarcodeSettings::get_OnlyRequestedTypes() const
```

## Opmerkingen


Dit voorbeeld toont hoe je herkenningsresultaten kunt beperken tot alleen de gevraagde barcode-typen.
```cpp
[C#]
//genereer EAN13-barcode
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//herken alleen UPCA-barcodes (geen resultaten, omdat de bron EAN13 is)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//herken compatibele typen: EAN13, UPCA, ISSN, ISMN, ISBN (EAN13 wordt geretourneerd als UPCA-equivalent)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```


Retourneert alleen barcode-typen die expliciet zijn opgegeven voor herkenning. Standaardwaarde is false.
## Zie ook

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
