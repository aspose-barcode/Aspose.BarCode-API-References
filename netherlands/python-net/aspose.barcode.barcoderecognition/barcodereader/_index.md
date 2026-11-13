---
title: "BarCodeReader"
second_title: "Aspose.BarCode voor Python via .NET API-referentie"
description: 
type: docs
url: /nl/python-net/aspose.barcode.barcoderecognition/barcodereader/
---

## BarCodeReader class

BarCodeReader omvat een afbeelding die één of meerdere barcodes kan bevatten; deze kan vervolgens de ReadBarCodes‑bewerking uitvoeren om barcodes te detecteren.

Het BarCodeReader-type geeft de volgende leden weer:
## Constructors
| Name | Beschrijving |
| :- | :- |
| BarCodeReader() | Initialiseert een nieuw exemplaar van de [BarCodeReader](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) klasse met standaardwaarden.<br/>            Vereist dat er een afbeelding wordt ingesteld (SetBitmapImage()) voordat de ReadBarCodes()‑methode wordt aangeroepen. |
| BarCodeReader(image) | Initialiseert een nieuw exemplaar van de BarCodeReader‑klasse |
| BarCodeReader(image, decode_types) | Initialiseert een nieuw exemplaar van de BarCodeReader‑klasse |
| BarCodeReader(image, type) | Initialiseert een nieuw exemplaar van de BarCodeReader‑klasse |
| BarCodeReader(image, area, decode_types) | Initialiseert een nieuw exemplaar van de BarCodeReader‑klasse |
| BarCodeReader(image, area, type) | Initialiseert een nieuw exemplaar van de BarCodeReader‑klasse |
| BarCodeReader(image, areas, decode_types) | Initialiseert een nieuw exemplaar van de BarCodeReader‑klasse |
| BarCodeReader(image, areas, type) | Initialiseert een nieuw exemplaar van de BarCodeReader‑klasse |
| BarCodeReader(filename) | Initialiseert een nieuw exemplaar van de BarCodeReader‑klasse |
| BarCodeReader(filename, decode_types) | Initialiseert een nieuw exemplaar van de BarCodeReader‑klasse |
| BarCodeReader(filename, type) | Initialiseert een nieuw exemplaar van de BarCodeReader‑klasse |
| BarCodeReader(stream) | Initialiseert een nieuw exemplaar van de BarCodeReader‑klasse |
| BarCodeReader(stream, type) | Initialiseert een nieuw exemplaar van de BarCodeReader‑klasse |
| BarCodeReader(stream, decode_types) | Initialiseert een nieuw exemplaar van de BarCodeReader‑klasse |
| BarCodeReader(frame, areas, type) | Initialiseert een nieuw exemplaar van de BarCodeReader‑klasse |
| BarCodeReader(frame, areas, decode_types) | Initialiseert een nieuw exemplaar van de BarCodeReader‑klasse |
| BarCodeReader(frame, area, type) | Initialiseert een nieuw exemplaar van de BarCodeReader‑klasse |
| BarCodeReader(frame, area, decode_types) | Initialiseert een nieuw exemplaar van de BarCodeReader‑klasse |
| BarCodeReader(frame, type) | Initialiseert een nieuw exemplaar van de BarCodeReader‑klasse |
| BarCodeReader(frame, decode_types) | Initialiseert een nieuw exemplaar van de BarCodeReader‑klasse |
| BarCodeReader(frame) | Initialiseert een nieuw exemplaar van de BarCodeReader‑klasse |
## Properties
| Name | Beschrijving |
| :- | :- |
| processor_settings | Haalt een instelling op voor het gebruik van processorcores. |
| timeout | Haalt of stelt de time-out van het herkenningsproces in milliseconden in. |
| found_bar_codes | Haalt de array met herkende [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/)s op |
| found_count | Haalt het aantal herkende barcodes op |
| quality_settings | QualitySettings maakt het mogelijk om de herkenningskwaliteit en -snelheid handmatig te configureren.<br/>            U kunt QualitySettings snel instellen met ingebouwde presets: HighPerformance, NormalQuality, <br/>            HighQuality, MaxBarCodes of u kunt handmatig afzonderlijke opties configureren.<br/>            Standaardwaarde van QualitySettings is NormalQuality. |
| barcode_settings | De belangrijkste BarCode-decoderingparameters. Bevat parameters die invloed hebben op de herkende gegevens. |
| bar_code_read_type | Haalt of stelt het barcode-decoderingstype in dat wordt gebruikt voor herkenning.<br/>            Moet worden ingesteld vóór het aanroepen van [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
## Methods
| Name | Beschrijving |
| :- | :- |
| set_bar_code_image(value) | Stelt bitmapafbeelding in voor herkenning. <br/>            Moet worden aangeroepen vóór de ReadBarCodes()-methode. |
| set_bar_code_image(value, areas) | Stelt bitmapafbeelding en gebieden in voor herkenning. <br/>            Moet worden aangeroepen vóór de ReadBarCodes()-methode. |
| set_bar_code_image(value, area) | Stelt bitmapafbeelding en gebieden in voor herkenning. <br/>            Moet worden aangeroepen vóór de ReadBarCodes()-methode. |
| set_bar_code_image(filename) | Stelt afbeeldingsbestand in voor herkenning. <br/>            Moet worden aangeroepen vóór de ReadBarCodes()-methode. |
| set_bar_code_image(stream) | Stelt afbeeldingsstroom in voor herkenning. <br/>            Moet worden aangeroepen vóór de ReadBarCodes()-methode. |
| set_bar_code_image(frame, area) | Stelt het luminantiekader en gebied in voor herkenning. Moet worden aangeroepen vóór de [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) methode. |
| set_bar_code_image(frame, areas) | Stelt het luminantiekader en gebieden in voor herkenning. Moet worden aangeroepen vóór de [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) methode. |
| set_bar_code_image(frame) | Stelt het luminantiekader en gebied in voor herkenning. Moet worden aangeroepen vóór de [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) methode. |
| export_to_xml(xml_file) | Exporteert BarCode-eigenschappen naar het opgegeven xml-bestand |
| export_to_xml(xml_stream) | Exporteert BarCode-eigenschappen naar de opgegeven xml-stroom |
| import_from_xml(xml_file) | Importeert BarCode-eigenschappen uit het opgegeven xml-bestand en past ze toe op de huidige BarCodeReader‑instantie. |
| import_from_xml(xml_stream) | Importeert BarCode-eigenschappen uit de opgegeven xml-stroom en past ze toe op de huidige BarCodeReader‑instantie. |
| abort() | Functie vraagt om beëindiging van de huidige herkenningssessie vanuit een andere thread. Abort is een onblokkerebare methode en geeft de controle terug direct na het aanroepen. <br/>            De methode moet worden gebruikt wanneer het herkenningsproces te lang duurt. |
| read_bar_codes() | Leest [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/)s van de afbeelding. |
| set_bar_code_read_type(barcode_types) | Stelt [SingleDecodeType](/barcode/python-net/aspose.barcode.barcoderecognition/singledecodetype/) type-array in voor herkenning. <br/>            Moet worden aangeroepen vóór de ReadBarCodes() methode. |

### Zie ook

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

