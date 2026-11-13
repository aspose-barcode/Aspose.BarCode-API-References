---
title: "BarCodeReader"
second_title: "Référence de l'API Aspose.BarCode pour Python via .NET"
description: 
type: docs
url: /fr/python-net/aspose.barcode.barcoderecognition/barcodereader/
---

## BarCodeReader class

BarCodeReader encapsule une image qui peut contenir un ou plusieurs codes-barres, puis peut exécuter l'opération ReadBarCodes pour détecter les codes-barres.

Le type BarCodeReader expose les membres suivants :
## Constructeurs
| Name | Description |
| :- | :- |
| BarCodeReader() | Initialise une nouvelle instance de la classe [BarCodeReader](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) avec les valeurs par défaut.<br/>            Nécessite de définir l'image (SetBitmapImage()) avant d'appeler la méthode ReadBarCodes(). |
| BarCodeReader(image) | Initialise une nouvelle instance de la classe BarCodeReader |
| BarCodeReader(image, decode_types) | Initialise une nouvelle instance de la classe BarCodeReader |
| BarCodeReader(image, type) | Initialise une nouvelle instance de la classe BarCodeReader |
| BarCodeReader(image, area, decode_types) | Initialise une nouvelle instance de la classe BarCodeReader |
| BarCodeReader(image, area, type) | Initialise une nouvelle instance de la classe BarCodeReader |
| BarCodeReader(image, areas, decode_types) | Initialise une nouvelle instance de la classe BarCodeReader |
| BarCodeReader(image, areas, type) | Initialise une nouvelle instance de la classe BarCodeReader |
| BarCodeReader(filename) | Initialise une nouvelle instance de la classe BarCodeReader |
| BarCodeReader(filename, decode_types) | Initialise une nouvelle instance de la classe BarCodeReader |
| BarCodeReader(filename, type) | Initialise une nouvelle instance de la classe BarCodeReader |
| BarCodeReader(stream) | Initialise une nouvelle instance de la classe BarCodeReader |
| BarCodeReader(stream, type) | Initialise une nouvelle instance de la classe BarCodeReader |
| BarCodeReader(stream, decode_types) | Initialise une nouvelle instance de la classe BarCodeReader |
| BarCodeReader(frame, areas, type) | Initialise une nouvelle instance de la classe BarCodeReader |
| BarCodeReader(frame, areas, decode_types) | Initialise une nouvelle instance de la classe BarCodeReader |
| BarCodeReader(frame, area, type) | Initialise une nouvelle instance de la classe BarCodeReader |
| BarCodeReader(frame, area, decode_types) | Initialise une nouvelle instance de la classe BarCodeReader |
| BarCodeReader(frame, type) | Initialise une nouvelle instance de la classe BarCodeReader |
| BarCodeReader(frame, decode_types) | Initialise une nouvelle instance de la classe BarCodeReader |
| BarCodeReader(frame) | Initialise une nouvelle instance de la classe BarCodeReader |
## Properties
| Name | Description |
| :- | :- |
| processor_settings | Obtient les paramètres d'utilisation des cœurs du processeur. |
| timeout | Obtient ou définit le délai d'attente du processus de reconnaissance en millisecondes. |
| found_bar_codes | Obtient le tableau des [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/)s reconnus |
| found_count | Obtient le nombre de codes-barres reconnus |
| quality_settings | QualitySettings permet de configurer manuellement la qualité et la vitesse de la reconnaissance.<br/>            Vous pouvez rapidement configurer QualitySettings à l'aide de préréglages intégrés : HighPerformance, NormalQuality, <br/>            HighQuality, MaxBarCodes ou vous pouvez configurer manuellement des options séparées.<br/>            La valeur par défaut de QualitySettings est NormalQuality. |
| barcode_settings | Les principaux paramètres de décodage BarCode. Contient des paramètres qui influencent les données reconnues. |
| bar_code_read_type | Obtient ou définit le type de décodage du code-barres utilisé pour la reconnaissance.<br/>            Doit être défini avant d'appeler [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
## Methods
| Name | Description |
| :- | :- |
| set_bar_code_image(value) | Définit l'image bitmap pour la reconnaissance. <br/>            Doit être appelé avant la méthode ReadBarCodes(). |
| set_bar_code_image(value, areas) | Définit l'image bitmap et les zones pour la reconnaissance. <br/>            Doit être appelé avant la méthode ReadBarCodes(). |
| set_bar_code_image(value, area) | Définit l'image bitmap et les zones pour la reconnaissance. <br/>            Doit être appelé avant la méthode ReadBarCodes(). |
| set_bar_code_image(filename) | Définit le fichier image pour la reconnaissance. <br/>            Doit être appelé avant la méthode ReadBarCodes(). |
| set_bar_code_image(stream) | Définit le flux d'image pour la reconnaissance. <br/>            Doit être appelé avant la méthode ReadBarCodes(). |
| set_bar_code_image(frame, area) | Définit le cadre de luminance et la zone pour la reconnaissance. Doit être appelé avant la méthode [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
| set_bar_code_image(frame, areas) | Définit le cadre de luminance et les zones pour la reconnaissance. Doit être appelé avant la méthode [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
| set_bar_code_image(frame) | Définit le cadre de luminance et la zone pour la reconnaissance. Doit être appelé avant la méthode [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
| export_to_xml(xml_file) | Exporte les propriétés BarCode vers le fichier xml spécifié |
| export_to_xml(xml_stream) | Exporte les propriétés BarCode vers le flux xml spécifié |
| import_from_xml(xml_file) | Importe les propriétés BarCode depuis le fichier xml spécifié et les applique à l'instance actuelle de BarCodeReader. |
| import_from_xml(xml_stream) | Importe les propriétés BarCode depuis le flux xml spécifié et les applique à l'instance actuelle de BarCodeReader. |
| abort() | La fonction demande la terminaison de la session de reconnaissance en cours depuis un autre thread. Abort est une méthode non bloquante et rend le contrôle immédiatement après l'appel. <br/>            La méthode doit être utilisée lorsque le processus de reconnaissance est trop long. |
| read_bar_codes() | Lit [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/)s depuis l'image. |
| set_bar_code_read_type(barcode_types) | Définit le tableau de type [SingleDecodeType](/barcode/python-net/aspose.barcode.barcoderecognition/singledecodetype/) pour la reconnaissance. <br/>            Doit être appelé avant la méthode ReadBarCodes(). |

### Voir aussi

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

