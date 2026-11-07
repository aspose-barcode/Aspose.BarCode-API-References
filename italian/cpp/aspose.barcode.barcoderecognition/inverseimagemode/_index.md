---
title: "enum"
linktitle: "InverseImageMode"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Come utilizzare l'enumerazione in C++."
type: docs
weight: 3900
url: /it/cpp/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enum




```cpp
enum class InverseImageMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Auto | 0 | Disabilita il riconoscimento aggiuntivo dei codici a barre su immagini inverse per tutti i tipi di codici a barre tranne il codice [QR](../../aspose.barcode.barcoderecognition.qr/). |
| Disabilitato | 1 | Disabilita il riconoscimento aggiuntivo dei codici a barre su immagini inverse. |
| Abilitato | 2 | Abilita il riconoscimento aggiuntivo dei codici a barre su immagini inverse |

## Osservazioni


Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre su immagini con colori invertiti (luminanza).

Questo esempio mostra come utilizzare la modalità InverseImage
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Vedi anche

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
