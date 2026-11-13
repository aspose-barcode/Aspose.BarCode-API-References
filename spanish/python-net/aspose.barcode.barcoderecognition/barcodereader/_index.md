---
title: "BarCodeReader"
second_title: "Referencia de API de Aspose.BarCode para Python a través de .NET"
description: 
type: docs
url: /es/python-net/aspose.barcode.barcoderecognition/barcodereader/
---

## BarCodeReader class

BarCodeReader encapsula una imagen que puede contener uno o varios códigos de barras, y luego puede ejecutar la operación ReadBarCodes para detectar códigos de barras.

El tipo BarCodeReader expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| BarCodeReader() | Inicializa una nueva instancia de la clase [BarCodeReader](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) con valores predeterminados.<br/>            Requiere establecer la imagen (SetBitmapImage()) antes de llamar al método ReadBarCodes(). |
| BarCodeReader(image) | Inicializa una nueva instancia de la clase BarCodeReader |
| BarCodeReader(image, decode_types) | Inicializa una nueva instancia de la clase BarCodeReader |
| BarCodeReader(image, type) | Inicializa una nueva instancia de la clase BarCodeReader |
| BarCodeReader(image, area, decode_types) | Inicializa una nueva instancia de la clase BarCodeReader |
| BarCodeReader(image, area, type) | Inicializa una nueva instancia de la clase BarCodeReader |
| BarCodeReader(image, areas, decode_types) | Inicializa una nueva instancia de la clase BarCodeReader |
| BarCodeReader(image, areas, type) | Inicializa una nueva instancia de la clase BarCodeReader |
| BarCodeReader(filename) | Inicializa una nueva instancia de la clase BarCodeReader |
| BarCodeReader(filename, decode_types) | Inicializa una nueva instancia de la clase BarCodeReader |
| BarCodeReader(filename, type) | Inicializa una nueva instancia de la clase BarCodeReader |
| BarCodeReader(stream) | Inicializa una nueva instancia de la clase BarCodeReader |
| BarCodeReader(stream, type) | Inicializa una nueva instancia de la clase BarCodeReader |
| BarCodeReader(stream, decode_types) | Inicializa una nueva instancia de la clase BarCodeReader |
| BarCodeReader(frame, areas, type) | Inicializa una nueva instancia de la clase BarCodeReader |
| BarCodeReader(frame, areas, decode_types) | Inicializa una nueva instancia de la clase BarCodeReader |
| BarCodeReader(frame, area, type) | Inicializa una nueva instancia de la clase BarCodeReader |
| BarCodeReader(frame, area, decode_types) | Inicializa una nueva instancia de la clase BarCodeReader |
| BarCodeReader(frame, type) | Inicializa una nueva instancia de la clase BarCodeReader |
| BarCodeReader(frame, decode_types) | Inicializa una nueva instancia de la clase BarCodeReader |
| BarCodeReader(frame) | Inicializa una nueva instancia de la clase BarCodeReader |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| processor_settings | Obtiene una configuración para usar los núcleos del procesador. |
| timeout | Obtiene o establece el tiempo de espera del proceso de reconocimiento en milisegundos. |
| found_bar_codes | Obtiene la matriz de [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/)s |
| found_count | Obtiene la cantidad de códigos de barras reconocidos |
| quality_settings | QualitySettings permite configurar manualmente la calidad y velocidad del reconocimiento.<br/>            Puedes configurar rápidamente QualitySettings mediante presets integrados: HighPerformance, NormalQuality, <br/>            HighQuality, MaxBarCodes o puedes configurar manualmente opciones separadas.<br/>            El valor predeterminado de QualitySettings es NormalQuality. |
| barcode_settings | Los principales parámetros de decodificación de BarCode. Contiene parámetros que influyen en los datos reconocidos. |
| bar_code_read_type | Obtiene o establece el tipo de decodificación de código de barras utilizado para el reconocimiento.<br/>            Debe establecerse antes de llamar a [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
## Métodos
| Nombre | Descripción |
| :- | :- |
| set_bar_code_image(value) | Establece la imagen bitmap para el reconocimiento. <br/>            Debe llamarse antes del método ReadBarCodes(). |
| set_bar_code_image(value, areas) | Establece la imagen bitmap y las áreas para el reconocimiento. <br/>            Debe llamarse antes del método ReadBarCodes(). |
| set_bar_code_image(value, area) | Establece la imagen bitmap y las áreas para el reconocimiento. <br/>            Debe llamarse antes del método ReadBarCodes(). |
| set_bar_code_image(filename) | Establece el archivo de imagen para el reconocimiento. <br/>            Debe llamarse antes del método ReadBarCodes(). |
| set_bar_code_image(stream) | Establece el flujo de imagen para el reconocimiento. <br/>            Debe llamarse antes del método ReadBarCodes(). |
| set_bar_code_image(frame, area) | Establece el marco de luminancia y el área para el reconocimiento. Debe llamarse antes del método [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
| set_bar_code_image(frame, areas) | Establece el marco de luminancia y las áreas para el reconocimiento. Debe llamarse antes del método [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
| set_bar_code_image(frame) | Establece el marco de luminancia y el área para el reconocimiento. Debe llamarse antes del método [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
| export_to_xml(xml_file) | Exporta las propiedades de BarCode al archivo xml especificado |
| export_to_xml(xml_stream) | Exporta las propiedades de BarCode al flujo xml especificado |
| import_from_xml(xml_file) | Importa las propiedades de BarCode desde el archivo xml especificado y las aplica a la instancia actual de BarCodeReader. |
| import_from_xml(xml_stream) | Importa las propiedades de BarCode desde el flujo xml especificado y las aplica a la instancia actual de BarCodeReader. |
| abort() | La función solicita la terminación de la sesión de reconocimiento actual desde otro hilo. Abort es un método no bloqueable y devuelve el control justo después de llamarse. <br/>            El método debe usarse cuando el proceso de reconocimiento es demasiado largo. |
| read_bar_codes() | Lee [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/)s de la imagen. |
| set_bar_code_read_type(barcode_types) | Establece la matriz de tipo [SingleDecodeType](/barcode/python-net/aspose.barcode.barcoderecognition/singledecodetype/) para el reconocimiento. <br/>            Debe llamarse antes del método ReadBarCodes(). |

### Ver también

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

