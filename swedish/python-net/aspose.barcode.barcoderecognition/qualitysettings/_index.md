---
title: "QualitySettings"
second_title: "Aspose.BarCode för Python via .NET API-referens"
description: 
type: docs
url: /sv/python-net/aspose.barcode.barcoderecognition/qualitysettings/
---

## QualitySettings class

QualitySettings tillåter att konfigurera igenkänningskvalitet och hastighet manuellt.<br/>            Du kan snabbt ställa in QualitySettings med inbyggda förinställningar: HighPerformance, NormalQuality, HighQuality, MaxQuality eller så kan du manuellt konfigurera separata alternativ.<br/>            Standardvärdet för QualitySettings är NormalQuality.

Typen QualitySettings exponerar följande medlemmar:
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| high_performance | HighPerformance förinställning för igenkänningskvalitet. Högkvalitativa staplar känns igen väl i detta läge. |
| normal_quality | NormalQuality igenkänningskvalitetsförinställning. Lämplig för de flesta streckkoder |
| high_quality | HighQuality igenkänningskvalitetsförinställning. Denna förinställning är utvecklad för streckkoder med låg kvalitet. Gör det möjligt att upptäcka kraftigt skadade streckkoder. |
| max_quality | MaxQuality igenkänningskvalitetsförinställning. Denna förinställning är utvecklad för att känna igen alla möjliga streckkoder, även felaktiga streckkoder. |
| x_dimension | Igenkänningsläge som anger storlek (från 1 till oändlig) på streckkodens minsta element: matriscell eller stapel. |
| minimal_x_dimension | Minsta storlek på XDimension i pixlar som används med UseMinimalXDimension. |
| barcode_quality | Läge som möjliggör metoder för att känna igen streckkodsdelar med den valda kvaliteten. Streckkodsdel med lägre kvalitet kräver mer krävande metoder vilket saktar ner igenkänningen. |
| deconvolution | Deconvolution (bildåterställning) läge som definierar nivån av bildnedbrytning. Ursprungligen är deconvolution en funktion som kan återställa en bild som har försämrats <br/> (konvolverad) av någon naturlig funktion som oskärpa, vid bildtagning med kamera. Eftersom vi inte kan upptäcka bildfunktionen som korrumperar bilden, <br/> måste vi kontrollera de mest välkända funktionerna som skärpa eller matematisk morfologi. |
| inverse_image | Läge som aktiverar eller inaktiverar ytterligare igenkänning av streckkoder på bilder med inverterade färger (luminans). |
| complex_background | Läge som aktiverar eller inaktiverar ytterligare igenkänning av färgstreckkoder på färgbilder. |
| allow_incorrect_barcodes | Tillåter motorn att känna igen streckkoder som har felaktig kontrollsumma eller felaktiga värden. Läge kan användas för att känna igen skadade streckkoder med felaktig text. |

### Se även

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

