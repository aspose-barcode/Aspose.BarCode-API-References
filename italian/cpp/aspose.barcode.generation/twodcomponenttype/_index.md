---
title: "enum"
linktitle: "TwoDComponentType"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " enum. Tipo di componente 2D in C++."
type: docs
weight: 8700
url: /it/cpp/aspose.barcode.generation/twodcomponenttype/
---
## TwoDComponentType enum


Tipo di componente 2D

```cpp
enum class TwoDComponentType
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Auto | 0 | Seleziona automaticamente il tipo di componente 2D |
| CC_A | 1 | Tipo di componente 2D CC-A. È una variante strutturale di MicroPDF417 |
| CC_B | 2 | Tipo di componente 2D CC-B. È un simbolo MicroPDF417. |
| CC_C | 3 | Tipo di componente 2D CC-C. È un simbolo PDF417. |

## Osservazioni


Questo esempio mostra come creare e salvare un'immagine GS1 Composite Bar. Nota che il codetext 1D e il codetext 2D sono separati dal simbolo '/'
```cpp
[C#]
var codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
    using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
    {
    generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
    generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;

    // Rapporto d'aspetto del componente 2D
    generator.Parameters.Barcode.Pdf417.AspectRatio = 3;

    // Dimensione X dei componenti 1D e 2D
    generator.Parameters.Barcode.XDimension.Pixels = 3;

    // Altezza del componente 1D
    generator.Parameters.Barcode.BarHeight.Pixels = 100;

    generator.Save("test.png");
}
```

## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
