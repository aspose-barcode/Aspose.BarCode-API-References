---
title: "metod"
linktitle: "get_OnlyRequestedTypes"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Returnerar endast streckkodstyper som uttryckligen specificerats för igenkänning. När den är aktiverad filtreras erkända streckkoder av andra kompatibla eller motsvarande typer bort. Standardvärdet är falskt i C++."
type: docs
weight: 500
url: /sv/cpp/aspose.barcode.barcoderecognition/barcodesettings/get_onlyrequestedtypes/
---
## BarcodeSettings::get_OnlyRequestedTypes method


Returnerar endast streckkodstyper som uttryckligen specificerats för igenkänning. När den är aktiverad filtreras igenkända streckkoder av andra kompatibla eller motsvarande typer bort. Standardvärdet är false.

```cpp
bool Aspose::BarCode::BarCodeRecognition::BarcodeSettings::get_OnlyRequestedTypes() const
```

## Anmärkningar


Det här exemplet visar hur man begränsar igenkänningsresultat till endast begärda streckkodstyper
```cpp
[C#]
//generera EAN13-streckkod
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//känn igen endast UPCA-streckkoder (inga resultat, eftersom källan är EAN13)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//känn igen kompatibla typer: EAN13, UPCA, ISSN, ISMN, ISBN (EAN13 kommer att returneras som UPCA-ekvivalent)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```


Returnerar endast streckkodstyper som uttryckligen specificerats för igenkänning. Standardvärdet är falskt.
## Se även

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
