---
title: "enum"
linktitle: "ComplexBackgroundMode"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Come utilizzare l'enumerazione in C++."
type: docs
weight: 3700
url: /it/cpp/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enum




```cpp
enum class ComplexBackgroundMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Auto | 0 | Al momento è lo stesso di Disabled. Disabilita il riconoscimento aggiuntivo di codici a barre colorati su immagini a colori. |
| Disabilitato | 1 | Disabilita il riconoscimento aggiuntivo di codici a barre colorati su immagini a colori. |
| Abilitato | 2 | Abilita il riconoscimento aggiuntivo di codici a barre colorati su immagini a colori. |

## Osservazioni


Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre a colori su immagini a colori.

Questo esempio mostra come utilizzare la modalità ComplexBackground
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Vedi anche

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
