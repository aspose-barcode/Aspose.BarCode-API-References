---
title: "Pdf417Parameters"
second_title: "Referencia de API de Aspose.BarCode para Python a través de .NET"
description: 
type: docs
url: /es/python-net/aspose.barcode.generation/pdf417parameters/
---

## Pdf417Parameters class

Parámetros de PDF417. Contiene los parámetros PDF417, MacroPDF417, MicroPDF417 y GS1MicroPdf417.<br/>            MacroPDF417 requiere dos campos: Pdf417MacroFileID y Pdf417MacroSegmentID. Todos los demás campos son opcionales.<br/>            MicroPDF417 en modo Structured Append (igual que el modo MacroPDF417) requiere dos campos: Pdf417MacroFileID y Pdf417MacroSegmentID. Todos los demás campos son opcionales.

El tipo Pdf417Parameters expone los siguientes miembros:
## Propiedades
| Nombre | Descripción |
| :- | :- |
| encode_mode | Identifica el modo de codificación Pdf417. <br/>            Valor predeterminado: Auto. |
| error_level | Obtiene o establece el tipo de simbología Pdf417 del nivel de corrección de errores del código de barras<br/>            que varía de level0 a level8, level0 significa sin información de corrección de errores,<br/>            level8 significa la mejor corrección de errores, lo que implica una imagen más grande. |
| truncate | Indica si el tipo de simbología Pdf417 del código de barras está truncado (para reducir espacio). <br/>            También conocido como CompactPDF417. El indicador de fila derecha y el patrón de parada derecha se eliminan en este modo. |
| columnas | Recuento de columnas. |
| filas | Recuento de filas. |
| aspect_ratio | Relación altura/ancho del módulo de código de barras 2D. |
| macro_pdf_417_file_id | ID de archivo del código de barras MacroPdf417 (campo obligatorio).<br/>            ID de archivo del código de barras MicroPDF417 (campo obligatorio para el modo Structured Append) |
| macro_pdf_417_segment_id | ID de segmento del código de barras MacroPdf417 (campo obligatorio), que comienza en 0, hasta MacroSegmentsCount - 1.<br/>            ID de segmento del código de barras MicroPDF417 (campo obligatorio para el modo Structured Append) |
| macro_pdf_417_segments_count | Recuento de segmentos del código de barras MacroPdf417 (campo opcional).<br/>            Recuento de segmentos del código de barras MicroPDF417 (campo opcional para el modo Structured Append) |
| macro_pdf_417_file_name | Nombre de archivo del código de barras MacroPdf417 (campo opcional).<br/>            Nombre de archivo del código de barras MicroPDF417 (campo opcional para el modo Structured Append) |
| macro_pdf_417_time_stamp | Marca de tiempo del código de barras MacroPdf417 (campo opcional).<br/>            Marca de tiempo del código de barras MicroPDF417 (campo opcional para el modo Structured Append) |
| macro_pdf_417_sender | Nombre del remitente del código de barras MacroPdf417 (campo opcional).<br/>            Nombre del remitente del código de barras MicroPDF417 (campo opcional para el modo Structured Append) |
| macro_pdf_417_addressee | Nombre del destinatario del código de barras MacroPdf417 (campo opcional).<br/>            Nombre del destinatario del código de barras MicroPDF417 (campo opcional para el modo Structured Append) |
| macro_pdf_417_file_size | Tamaño de archivo MacroPdf417 (campo opcional).<br/>            Tamaño de archivo MicroPDF417 (campo opcional para el modo Structured Append)<br/>            El campo de tamaño de archivo contiene el tamaño en bytes de todo el archivo fuente. |
| macro_pdf_417_checksum | Checksum de código de barras MacroPdf417 (campo opcional).<br/>            Checksum de código de barras MicroPDF417 (campo opcional para el modo Structured Append)<br/>            El campo de checksum contiene el valor del checksum CRC de 16 bits (2 bytes) usando el polinomio CCITT-16. x^16 + x^12 + x^5 + 1 |
| eci_encoding | Identificadores de Interpretación de Canal Extendido. Se utiliza para indicar al lector de códigos de barras detalles<br/>            sobre las referencias usadas para codificar los datos en el símbolo. No se aplica a los campos de texto Macro PDF417.<br/>            La implementación actual incluye todas las codificaciones de conjunto de caracteres conocidas. |
| macro_pdf_417eci_encoding | Identificadores de Interpretación de Canal Extendido. Se aplica a los campos de texto Macro PDF417. |
| macro_pdf_417_terminator | Se usa para indicar al codificador si debe agregar el Terminador Macro PDF417 (código de palabra 922) al segmento. <br/>            Aplicado solo para Macro PDF417. |
| is_reader_initialization | Se utiliza para indicar al lector que interprete los datos contenidos dentro del símbolo<br/>            como programación para la inicialización del lector. |
| macro_characters | Los valores de los caracteres Macro 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales.<br/>            Solo se puede usar con MicroPdf417 y codifica los modos MicroPdf417 916 y 917<br/>            Valor predeterminado: MacroCharacters.None. |
| is_linked | Define modos vinculados con códigos de barras GS1MicroPdf417, MicroPdf417 y Pdf417<br/>            Con la simbología GS1MicroPdf417 codifica los modos UCC/EAN-128 “Linked” 906, 907, 912, 913, 914, 915<br/>            Con las simbologías MicroPdf417 y Pdf417 codifica la bandera de enlace 918 al componente lineal asociado que no sea un EAN.UCC |
| is_code_128_emulation | Solo se puede usar con MicroPdf417 y codifica modos de emulación Code 128<br/>            Puede codificar FNC1 en modos de segunda posición 908 y 909, también puede codificar 910 y 911 que solo indican que el MicroPdf417 reconocido puede interpretarse como Code 128 |

### Ver también

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

