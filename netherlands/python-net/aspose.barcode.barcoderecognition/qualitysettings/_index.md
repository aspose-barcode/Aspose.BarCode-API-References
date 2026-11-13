---
title: "QualitySettings"
second_title: "Aspose.BarCode voor Python via .NET API-referentie"
description: 
type: docs
url: /nl/python-net/aspose.barcode.barcoderecognition/qualitysettings/
---

## QualitySettings class

QualitySettings maakt het mogelijk om de herkenningskwaliteit en -snelheid handmatig te configureren.<br/>            U kunt QualitySettings snel instellen met ingebouwde presets: HighPerformance, NormalQuality, HighQuality, MaxQuality of u kunt handmatig afzonderlijke opties configureren.<br/>            Standaardwaarde van QualitySettings is NormalQuality.

Het type QualitySettings bevat de volgende leden:
## Properties
| Name | Beschrijving |
| :- | :- |
| high_performance | HighPerformance herkenningskwaliteitspreset. Barcodes van hoge kwaliteit worden goed herkend in deze modus. |
| normal_quality | NormalQuality herkenningskwaliteitsvoorinstelling. Geschikt voor de meeste barcodes |
| high_quality | HighQuality herkenningskwaliteitsvoorinstelling. Deze voorinstelling is ontwikkeld voor barcodes van lage kwaliteit. Maakt het mogelijk om sterk beschadigde barcodes te detecteren. |
| max_quality | MaxQuality herkenningskwaliteitsvoorinstelling. Deze voorinstelling is ontwikkeld om alle mogelijke barcodes te herkennen, zelfs onjuiste barcodes. |
| x_dimension | Herkenningsmodus die de grootte (van 1 tot oneindig) van het minimale barcodelelement instelt: matrixcel of balk. |
| minimal_x_dimension | Minimale grootte van XDimension in pixels die wordt gebruikt met UseMinimalXDimension. |
| barcode_quality | Modus die methoden inschakelt om barcodellementen met de geselecteerde kwaliteit te herkennen. Een barcodellement met lagere kwaliteit vereist meer intensieve methoden, wat de herkenning vertraagt. |
| deconvolution | Deconvolutie (beeldherstel) modus die het niveau van beelddegradatie definieert. Oorspronkelijk is deconvolutie een functie die een door <br/>            (geconvolueerd) natuurlijke functie zoals vervaging, verkregen via een camera, gedegradeerd beeld kan herstellen. Omdat we de beeldfunctie die het beeld corrumpeert niet kunnen detecteren, <br/>            moeten we de meest bekende functies zoals scherpte of wiskundige morfologie controleren. |
| inverse_image | Modus die extra herkenning van barcodes op afbeeldingen met omgekeerde kleuren (luminantie) in- of uitschakelt. |
| complex_background | Modus die extra herkenning van gekleurde barcodes op gekleurde afbeeldingen in- of uitschakelt. |
| allow_incorrect_barcodes | Staat de engine toe barcodes te herkennen die een onjuiste controlesom of onjuiste waarden hebben. Deze modus kan worden gebruikt om beschadigde barcodes met onjuiste tekst te herkennen. |

### Zie ook

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

