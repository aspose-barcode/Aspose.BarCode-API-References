---
title: "Clase Aspose::BarCode::Generation::Pdf417Parameters"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Clase Aspose::BarCode::Generation::Pdf417Parameters. Parámetros PDF417. Contiene los parámetros PDF417, MacroPDF417, MicroPDF417 y GS1MicroPdf417. MacroPDF417 requiere dos campos: Pdf417MacroFileID y Pdf417MacroSegmentID. Todos los demás campos son opcionales. MicroPDF417 en modo Structured Append (igual que el modo MacroPDF417) requiere dos campos: Pdf417MacroFileID y Pdf417MacroSegmentID. Todos los demás campos son opcionales en C++."
type: docs
weight: 4000
url: /es/cpp/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class


Parámetros de PDF417. Contiene los parámetros PDF417, MacroPDF417, MicroPDF417 y GS1MicroPdf417. MacroPDF417 requiere dos campos: Pdf417MacroFileID y Pdf417MacroSegmentID. Todos los demás campos son opcionales. MicroPDF417 en modo Structured Append (igual que el modo MacroPDF417) requiere dos campos: Pdf417MacroFileID y Pdf417MacroSegmentID. Todos los demás campos son opcionales.

```cpp
class Pdf417Parameters : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Relación altura/ancho del módulo 2D [BarCode](../../aspose.barcode/). |
| [get_Columns](./get_columns/)() const | Recuento de columnas. |
| [get_ECIEncoding](./get_eciencoding/)() const | Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. No se aplican a los campos de texto Macro PDF417. La implementación actual incluye todas las codificaciones de conjuntos de caracteres conocidas. |
| [get_EncodeMode](./get_encodemode/)() const | Identifica el modo de codificación Pdf417. Valor predeterminado: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() const | Obtiene el tipo de simbología Pdf417 del nivel de corrección de errores de [BarCode](../../aspose.barcode/), que varía de level0 a level8; level0 significa sin información de corrección de errores, level8 significa la mejor corrección de errores, lo que implica una imagen más grande. |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | Solo se puede usar con MicroPdf417 y codifica modos de emulación Code 128. Puede codificar FNC1 en los modos de segunda posición 908 y 909, también puede codificar 910 y 911, que solo indican que el MicroPdf417 reconocido puede interpretarse como Code 128. |
| [get_IsLinked](./get_islinked/)() const | Define modos vinculados con los códigos de barras GS1MicroPdf417, MicroPdf417 y Pdf417. Con la simbología GS1MicroPdf417 codifica los modos UCC/EAN-128 “Linked” 906, 907, 912, 913, 914, 915. Con las simbologías MicroPdf417 y Pdf417 codifica la bandera de enlace 918 al componente lineal asociado, distinto de un EAN.UCC. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Utilizado para instruir al lector a interpretar los datos contenidos en el símbolo como programación para la inicialización del lector. |
| [get_MacroCharacters](./get_macrocharacters/)() const | Los valores de los caracteres macro 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales. Solo se pueden usar con MicroPdf417 y codifica los modos MicroPdf417 916 y 917. Valor predeterminado: [MacroCharacters.None](../barcodeclassifications/). |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | Nombre del destinatario del código de barras MacroPdf417 (campo opcional). Nombre del destinatario del código de barras MicroPDF417 (campo opcional para el modo Structured Append). |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | Suma de verificación del código de barras MacroPdf417 (campo opcional). Suma de verificación del código de barras MicroPDF417 (campo opcional para el modo Structured Append). El campo de suma de verificación contiene el valor de la suma de verificación CRC de 16 bits (2 bytes) usando el polinomio CCITT-16. x^16 + x^12 + x^5 + 1 |
| [get_MacroPdf417ECIEncoding](./get_macropdf417eciencoding/)() const | Identificadores de Interpretación de Canal Extendido. Se aplican a los campos de texto Macro PDF417. |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | ID de archivo del código de barras MacroPdf417 (campo obligatorio). ID de archivo del código de barras MicroPDF417 (campo obligatorio para el modo Structured Append). |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | Nombre de archivo del código de barras MacroPdf417 (campo opcional). Nombre de archivo del código de barras MicroPDF417 (campo opcional para el modo Structured Append). |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | Tamaño de archivo MacroPdf417 (campo opcional). Tamaño de archivo MicroPDF417 (campo opcional para el modo Structured Append). El campo de tamaño de archivo contiene el tamaño en bytes del archivo fuente completo. |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | ID de segmento del código de barras MacroPdf417 (campo obligatorio), que va de 0 a MacroSegmentsCount - 1. ID de segmento del código de barras MicroPDF417 (campo obligatorio para el modo Structured Append). |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | Recuento de segmentos del código de barras MacroPdf417 (campo opcional). Recuento de segmentos del código de barras MicroPDF417 (campo opcional para el modo Structured Append). |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | Nombre del remitente del código de barras MacroPdf417 (campo opcional). Nombre del remitente del código de barras MicroPDF417 (campo opcional para el modo Structured Append). |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | Se utiliza para indicar al codificador si debe agregar el terminador Macro PDF417 (código de palabra 922) al segmento. Aplicado solo para Macro PDF417. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | Marca de tiempo del código de barras MacroPdf417 (campo opcional). Marca de tiempo del código de barras MicroPDF417 (campo opcional para el modo Structured Append). |
| [get_Rows](./get_rows/)() const | Recuento de filas. |
| [get_Truncate](./get_truncate/)() const | Indica si el tipo de simbología Pdf417 de [BarCode](../../aspose.barcode/) está truncado (para reducir espacio). También conocido como CompactPDF417. En este modo se eliminan el indicador de fila derecha y el patrón de parada derecha. |
| [set_AspectRatio](./set_aspectratio/)(float) | Relación altura/ancho del módulo 2D [BarCode](../../aspose.barcode/). |
| [set_Columns](./set_columns/)(int32_t) | Recuento de columnas. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. No se aplican a los campos de texto Macro PDF417. La implementación actual incluye todas las codificaciones de conjuntos de caracteres conocidas. |
| [set_EncodeMode](./set_encodemode/)(Pdf417EncodeMode) | Identifica el modo de codificación Pdf417. Valor predeterminado: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(Pdf417ErrorLevel) | Establece el tipo de simbología Pdf417 del nivel de corrección de errores de [BarCode](../../aspose.barcode/) que varía de level0 a level8, level0 significa sin información de corrección de errores, level8 significa la mejor corrección de errores lo que implica una imagen más grande. |
| [set_IsCode128Emulation](./set_iscode128emulation/)(bool) | Solo se puede usar con MicroPdf417 y codifica modos de emulación Code 128. Puede codificar FNC1 en los modos de segunda posición 908 y 909, también puede codificar 910 y 911, que solo indican que el MicroPdf417 reconocido puede interpretarse como Code 128. |
| [set_IsLinked](./set_islinked/)(bool) | Define modos vinculados con los códigos de barras GS1MicroPdf417, MicroPdf417 y Pdf417. Con la simbología GS1MicroPdf417 codifica los modos UCC/EAN-128 “Linked” 906, 907, 912, 913, 914, 915. Con las simbologías MicroPdf417 y Pdf417 codifica la bandera de enlace 918 al componente lineal asociado, distinto de un EAN.UCC. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Utilizado para instruir al lector a interpretar los datos contenidos en el símbolo como programación para la inicialización del lector. |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | Los valores de los caracteres macro 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales. Solo se pueden usar con MicroPdf417 y codifica los modos MicroPdf417 916 y 917. Valor predeterminado: [MacroCharacters.None](../barcodeclassifications/). |
| [set_MacroPdf417Addressee](./set_macropdf417addressee/)(System::String) | Nombre del destinatario del código de barras MacroPdf417 (campo opcional). Nombre del destinatario del código de barras MicroPDF417 (campo opcional para el modo Structured Append). |
| [set_MacroPdf417Checksum](./set_macropdf417checksum/)(int32_t) | Suma de verificación del código de barras MacroPdf417 (campo opcional). Suma de verificación del código de barras MicroPDF417 (campo opcional para el modo Structured Append). El campo de suma de verificación contiene el valor de la suma de verificación CRC de 16 bits (2 bytes) usando el polinomio CCITT-16. x^16 + x^12 + x^5 + 1 |
| [set_MacroPdf417ECIEncoding](./set_macropdf417eciencoding/)(ECIEncodings) | Identificadores de Interpretación de Canal Extendido. Se aplican a los campos de texto Macro PDF417. |
| [set_MacroPdf417FileID](./set_macropdf417fileid/)(int32_t) | ID de archivo del código de barras MacroPdf417 (campo obligatorio). ID de archivo del código de barras MicroPDF417 (campo obligatorio para el modo Structured Append). |
| [set_MacroPdf417FileName](./set_macropdf417filename/)(System::String) | Nombre de archivo del código de barras MacroPdf417 (campo opcional). Nombre de archivo del código de barras MicroPDF417 (campo opcional para el modo Structured Append). |
| [set_MacroPdf417FileSize](./set_macropdf417filesize/)(int32_t) | Tamaño de archivo MacroPdf417 (campo opcional). Tamaño de archivo MicroPDF417 (campo opcional para el modo Structured Append). El campo de tamaño de archivo contiene el tamaño en bytes del archivo fuente completo. |
| [set_MacroPdf417SegmentID](./set_macropdf417segmentid/)(int32_t) | ID de segmento del código de barras MacroPdf417 (campo obligatorio), que va de 0 a MacroSegmentsCount - 1. ID de segmento del código de barras MicroPDF417 (campo obligatorio para el modo Structured Append). |
| [set_MacroPdf417SegmentsCount](./set_macropdf417segmentscount/)(int32_t) | Recuento de segmentos del código de barras MacroPdf417 (campo opcional). Recuento de segmentos del código de barras MicroPDF417 (campo opcional para el modo Structured Append). |
| [set_MacroPdf417Sender](./set_macropdf417sender/)(System::String) | Nombre del remitente del código de barras MacroPdf417 (campo opcional). Nombre del remitente del código de barras MicroPDF417 (campo opcional para el modo Structured Append). |
| [set_MacroPdf417Terminator](./set_macropdf417terminator/)(Pdf417MacroTerminator) | Se utiliza para indicar al codificador si debe agregar el terminador Macro PDF417 (código de palabra 922) al segmento. Aplicado solo para Macro PDF417. |
| [set_MacroPdf417TimeStamp](./set_macropdf417timestamp/)(System::DateTime) | Marca de tiempo del código de barras MacroPdf417 (campo opcional). Marca de tiempo del código de barras MicroPDF417 (campo opcional para el modo Structured Append). |
| [set_Rows](./set_rows/)(int32_t) | Recuento de filas. |
| [set_Truncate](./set_truncate/)(bool) | Indica si el tipo de simbología Pdf417 de [BarCode](../../aspose.barcode/) está truncado (para reducir espacio). También conocido como CompactPDF417. En este modo se eliminan el indicador de fila derecha y el patrón de parada derecha. |
| [ToString](./tostring/)() const override | Devuelve una representación en cadena legible por humanos de este [Pdf417Parameters](./). |
## Observaciones


Estos ejemplos muestran cómo codificar los modos no vinculados UCC/EAN-128 en GS1MicroPdf417
```cpp
[C#]
//Codifica el modo no vinculado 905 de GS1 UCC/EAN-128 con AI 01 (GTIN)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Codifica los modos no vinculados 903, 904 de GS1 UCC/EAN-128 con cualquier AI
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
