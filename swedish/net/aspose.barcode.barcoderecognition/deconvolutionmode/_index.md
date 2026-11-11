---
title: "Enum DeconvolutionMode"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.BarCodeRecognition.DeconvolutionMode enum. Deconvolution‑läge för bildåterställning som definierar graden av bildförsämring. Ursprungligen är dekonvolution en funktion som kan återställa en bild som har försämrats och konvolverats av någon naturlig funktion som oskärpa vid bildtagning med kamera. Eftersom vi inte kan upptäcka den bildfunktion som korrumperar bilden måste vi kontrollera de mest välkända funktionerna som skärpa eller matematisk morfologi"
type: docs
weight: 240
url: /sv/net/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enumeration

Deconvolution (bildåterställning)‑läge som definierar graden av bildförsämring. Ursprungligen är dekonvolution en funktion som kan återställa en bild som har försämrats (konvolverats) av någon naturlig funktion som oskärpa, vid bildtagning med kamera. Eftersom vi inte kan upptäcka den bildfunktion som korrumperar bilden måste vi kontrollera de mest välkända funktionerna som skärpa eller matematisk morfologi.

```csharp
public enum DeconvolutionMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Fast | `0` | Möjliggör snabba dekonvolutionsmetoder för högkvalitativa bilder. |
| Normal | `1` | Möjliggör normala dekonvolutionsmetoder för vanliga bilder. |
| Slow | `2` | Möjliggör långsamma dekonvolutionsmetoder för lågkvalitativa bilder. |

## Exempel

Detta exempel visar hur man använder Deconvolution‑läget

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Se även

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


