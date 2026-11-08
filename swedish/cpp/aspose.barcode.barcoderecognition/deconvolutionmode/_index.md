---
title: "enum"
linktitle: "DeconvolutionMode"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Hur man använder enum i C++."
type: docs
weight: 3800
url: /sv/cpp/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enum




```cpp
enum class DeconvolutionMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Snabb | 0 | Aktiverar snabba dekonvolutionsmetoder för högkvalitativa bilder. |
| Normal | 1 | Aktiverar normala dekonvolutionsmetoder för vanliga bilder. |
| Långsam | 2 | Aktiverar långsamma dekonvolutionsmetoder för lågkvalitativa bilder. |

## Anmärkningar


Deconvolution (bildåterställning) läge som definierar nivån av bildnedbrytning. Ursprungligen är dekonvolution en funktion som kan återställa en bild som har försämrats (konvolverats) av någon naturlig funktion som oskärpa, vid bildtagning med kamera. Eftersom vi inte kan upptäcka den bildfunktion som korrumperar bilden, måste vi testa de mest välkända funktionerna som skärpning eller matematisk morfologi.

Detta exempel visar hur man använder Deconvolution-läget
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Se även

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
