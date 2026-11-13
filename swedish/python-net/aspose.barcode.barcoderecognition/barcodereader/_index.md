---
title: "BarCodeReader"
second_title: "Aspose.BarCode för Python via .NET API-referens"
description: 
type: docs
url: /sv/python-net/aspose.barcode.barcoderecognition/barcodereader/
---

## BarCodeReader class

BarCodeReader kapslar in en bild som kan innehålla en eller flera streckkoder, och kan sedan utföra ReadBarCodes‑operationen för att upptäcka streckkoder.

BarCodeReader-typen exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| BarCodeReader() | Initierar en ny instans av klassen [BarCodeReader](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) med standardvärden.<br/> Kräver att en bild (SetBitmapImage()) sätts innan ReadBarCodes()-metoden anropas. |
| BarCodeReader(image) | Initierar en ny instans av BarCodeReader-klassen |
| BarCodeReader(image, decode_types) | Initierar en ny instans av BarCodeReader-klassen |
| BarCodeReader(image, type) | Initierar en ny instans av BarCodeReader-klassen |
| BarCodeReader(image, area, decode_types) | Initierar en ny instans av BarCodeReader-klassen |
| BarCodeReader(image, area, type) | Initierar en ny instans av BarCodeReader-klassen |
| BarCodeReader(image, areas, decode_types) | Initierar en ny instans av BarCodeReader-klassen |
| BarCodeReader(image, areas, type) | Initierar en ny instans av BarCodeReader-klassen |
| BarCodeReader(filename) | Initierar en ny instans av BarCodeReader-klassen |
| BarCodeReader(filename, decode_types) | Initierar en ny instans av BarCodeReader-klassen |
| BarCodeReader(filename, type) | Initierar en ny instans av BarCodeReader-klassen |
| BarCodeReader(stream) | Initierar en ny instans av BarCodeReader-klassen |
| BarCodeReader(stream, type) | Initierar en ny instans av BarCodeReader-klassen |
| BarCodeReader(stream, decode_types) | Initierar en ny instans av BarCodeReader-klassen |
| BarCodeReader(frame, areas, type) | Initierar en ny instans av BarCodeReader-klassen |
| BarCodeReader(frame, areas, decode_types) | Initierar en ny instans av BarCodeReader-klassen |
| BarCodeReader(frame, area, type) | Initierar en ny instans av BarCodeReader-klassen |
| BarCodeReader(frame, area, decode_types) | Initierar en ny instans av BarCodeReader-klassen |
| BarCodeReader(frame, type) | Initierar en ny instans av BarCodeReader-klassen |
| BarCodeReader(frame, decode_types) | Initierar en ny instans av BarCodeReader-klassen |
| BarCodeReader(frame) | Initierar en ny instans av BarCodeReader-klassen |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| processor_settings | Hämtar en inställning för att använda processorkärnor. |
| timeout | Hämtar eller anger tidsgränsen för igenkänningsprocessen i millisekunder. |
| found_bar_codes | Hämtar en array med igenkända [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/) |
| found_count | Hämtar antalet igenkända streckkoder |
| quality_settings | QualitySettings låter dig konfigurera igenkänningskvalitet och hastighet manuellt.<br/>            Du kan snabbt ställa in QualitySettings med inbyggda förinställningar: HighPerformance, NormalQuality, <br/>            HighQuality, MaxBarCodes eller så kan du manuellt konfigurera separata alternativ.<br/>            Standardvärdet för QualitySettings är NormalQuality. |
| barcode_settings | De huvudsakliga BarCode-avkodningsparametrarna. Innehåller parametrar som påverkar den igenkända datan. |
| bar_code_read_type | Hämtar eller anger den streckkodstyp som används för avkodning vid igenkänning.<br/>            Måste anges innan anrop av [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| set_bar_code_image(value) | Ställer in bitmap-bild för igenkänning. <br/>            Måste anropas innan metoden ReadBarCodes(). |
| set_bar_code_image(value, areas) | Ställer in bitmap-bild och områden för igenkänning. <br/>            Måste anropas innan metoden ReadBarCodes(). |
| set_bar_code_image(value, area) | Ställer in bitmap-bild och områden för igenkänning. <br/>            Måste anropas innan metoden ReadBarCodes(). |
| set_bar_code_image(filename) | Ställer in bildfil för igenkänning. <br/>            Måste anropas innan metoden ReadBarCodes(). |
| set_bar_code_image(stream) | Ställer in bildström för igenkänning. <br/>            Måste anropas innan metoden ReadBarCodes(). |
| set_bar_code_image(frame, area) | Ställer in luminansramen och området för igenkänning. Måste anropas innan [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) metoden. |
| set_bar_code_image(frame, areas) | Ställer in luminansramen och områdena för igenkänning. Måste anropas innan [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) metoden. |
| set_bar_code_image(frame) | Ställer in luminansramen och området för igenkänning. Måste anropas innan [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) metoden. |
| export_to_xml(xml_file) | Exporterar BarCode-egenskaper till den angivna xml-filen |
| export_to_xml(xml_stream) | Exporterar BarCode-egenskaper till den angivna xml-strömmen |
| import_from_xml(xml_file) | Importerar BarCode-egenskaper från den angivna xml-filen och tillämpar dem på den aktuella BarCodeReader-instansen. |
| import_from_xml(xml_stream) | Importerar BarCode-egenskaper från den angivna xml-strömmen och tillämpar dem på den aktuella BarCodeReader-instansen. |
| abort() | Funktionen begär att den aktuella igenkänningssessionen avslutas från en annan tråd. Abort är en metod som inte kan blockeras och återgår till kontrollen omedelbart efter anropet. <br/>            Metoden bör användas när igenkänningsprocessen är för lång. |
| read_bar_codes() | Läser [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/) från bilden. |
| set_bar_code_read_type(barcode_types) | Ställer in [SingleDecodeType](/barcode/python-net/aspose.barcode.barcoderecognition/singledecodetype/) typarray för igenkänning. <br/>            Måste anropas innan ReadBarCodes() metoden. |

### Se även

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

