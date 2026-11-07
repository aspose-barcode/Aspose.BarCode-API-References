---
title: "method"
linktitle: "get_OnlyRequestedTypes"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Restituisce solo i tipi di codice a barre specificati esplicitamente per il riconoscimento. Quando abilitato, i codici a barre riconosciuti di altri tipi compatibili o equivalenti vengono filtrati. Il valore predefinito è false in C++."
type: docs
weight: 500
url: /it/cpp/aspose.barcode.barcoderecognition/barcodesettings/get_onlyrequestedtypes/
---
## BarcodeSettings::get_OnlyRequestedTypes method


Restituisce solo i tipi di codice a barre esplicitamente specificati per il riconoscimento. Quando abilitato, i codici a barre riconosciuti di altri tipi compatibili o equivalenti vengono filtrati. Il valore predefinito è false.

```cpp
bool Aspose::BarCode::BarCodeRecognition::BarcodeSettings::get_OnlyRequestedTypes() const
```

## Osservazioni


Questo esempio mostra come limitare i risultati del riconoscimento solo ai tipi di codice a barre richiesti
```cpp
[C#]
//genera codice a barre EAN13
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//riconosci solo codici a barre UPCA (nessun risultato, perché la sorgente è EAN13)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//riconosci tipi compatibili: EAN13, UPCA, ISSN, ISMN, ISBN (EAN13 verrà restituito come equivalente UPCA)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```


Restituisce solo i tipi di codice a barre specificati esplicitamente per il riconoscimento. Il valore predefinito è false.
## Vedi anche

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
