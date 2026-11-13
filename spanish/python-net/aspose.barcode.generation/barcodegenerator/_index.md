---
title: "BarcodeGenerator"
second_title: "Referencia de API de Aspose.BarCode para Python a través de .NET"
description: 
type: docs
url: /es/python-net/aspose.barcode.generation/barcodegenerator/
---

## BarcodeGenerator class

BarcodeGenerator para la generación de imágenes de códigos de barras en el backend.

El tipo BarcodeGenerator expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| BarcodeGenerator(type) | Inicializa una nueva instancia de la clase BarcodeGenerator |
| BarcodeGenerator(type, code_text) | Inicializa una nueva instancia de la clase BarcodeGenerator |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| parámetros | Parámetros de generación. |
| barcode_type | Tipo de simbología de código de barras. |
| code_text | Texto a codificar. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| set_code_text(code_bytes) | Establece el texto del código como una secuencia de bytes. |
| set_code_text(code_text, encoding) |  |
| set_code_text(code_text, encoding, insert_bom) |  |
| save(stream, format) | Guarda la imagen del código de barras en un flujo en un formato específico. |
| save(filename, format) | Guarda la imagen del código de barras en un archivo específico en un formato específico. |
| save(filename) | Guarda la imagen del código de barras en un archivo específico en un formato específico. |
| export_to_xml(xml_file) | Exporta las propiedades de BarCode al archivo xml especificado |
| export_to_xml(xml) | Exporta las propiedades de BarCode al flujo xml especificado |
| import_from_xml(xml_file) | Importa las propiedades de BarCode del archivo xml especificado y crea una instancia de BarcodeGenerator. |
| import_from_xml(xml) | Importa las propiedades de BarCode del flujo xml especificado y crea una instancia de BarcodeGenerator. |
| generate_bar_code_image() | Genera la imagen del código de barras con la configuración actual. |

### Ver también

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

