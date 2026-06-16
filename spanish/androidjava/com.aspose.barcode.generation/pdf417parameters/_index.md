---
title: Pdf417Parameters
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Parámetros de PDF417.
type: docs
weight: 60
url: /es/androidjava/com.aspose.barcode.generation/pdf417parameters/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417Parameters
```

Parámetros PDF417. Contiene los parámetros PDF417, MacroPDF417, MicroPDF417 y GS1MicroPdf417. MacroPDF417 requiere dos campos: Pdf417MacroFileID y Pdf417MacroSegmentID. Todos los demás campos son opcionales. MicroPDF417 en modo Structured Append (igual que el modo MacroPDF417) requiere dos campos: Pdf417MacroFileID y Pdf417MacroSegmentID. Todos los demás campos son opcionales.

Estos ejemplos muestran cómo codificar modos no vinculados UCC/EAN-128 en GS1MicroPdf417

```

 [C#]
 //Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes GS1 UCC/EAN-128 non Linked modes 903, 904 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```
## Methods

| Method | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Relación altura/ancho del módulo de código de barras 2D. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Recuento de columnas. |
| [getECIEncoding()](#getECIEncoding--) | Identificadores de Interpretación de Canal Extendido. |
| [getEncodeMode()](#getEncodeMode--) | Identifica el modo de codificación Pdf417. |
| [getErrorLevel()](#getErrorLevel--) | Obtiene el tipo de simbología Pdf417 del nivel de corrección de errores del código de barras, que varía de level0 a level8; level0 significa sin información de corrección de errores, level8 significa la mejor corrección de errores, lo que implica una imagen más grande. |
| [getMacroCharacters()](#getMacroCharacters--) | Los valores de los caracteres macro 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Nombre del destinatario del código de barras MacroPdf417 (campo opcional). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Suma de verificación del código de barras MacroPdf417 (campo opcional). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | Identificadores de Interpretación de Canal Extendido. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | ID de archivo del código de barras MacroPdf417 (campo requerido). |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Nombre de archivo del código de barras MacroPdf417 (campo opcional). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Tamaño del archivo MacroPdf417 (campo opcional). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | ID del segmento del código de barras MacroPdf417 (campo obligatorio), que comienza en 0, hasta MacroSegmentsCount - 1. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Recuento de segmentos del código de barras MacroPdf417 (campo opcional). |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Nombre del remitente del código de barras MacroPdf417 (campo opcional). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Se utiliza para indicar al codificador si debe agregar el Terminador Macro PDF417 (código de palabra 922) al segmento. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Marca de tiempo del código de barras MacroPdf417 (campo opcional). |
| [getPdf417CompactionMode()](#getPdf417CompactionMode--) | Tipo de simbología Pdf417 del modo de compactación del código de barras. |
| [getPdf417ECIEncoding()](#getPdf417ECIEncoding--) | Identificadores de Interpretación de Canal Extendido. |
| [getPdf417EncodeMode()](#getPdf417EncodeMode--) | Identifica el modo de codificación Pdf417. |
| [getPdf417ErrorLevel()](#getPdf417ErrorLevel--) | Obtiene el tipo de simbología Pdf417 del nivel de corrección de errores del código de barras, que varía de level0 a level8; level0 significa sin información de corrección de errores, level8 significa la mejor corrección de errores, lo que implica una imagen más grande. |
| [getPdf417MacroAddressee()](#getPdf417MacroAddressee--) | Nombre del destinatario del código de barras MacroPdf417 (campo opcional). |
| [getPdf417MacroChecksum()](#getPdf417MacroChecksum--) | Suma de verificación del código de barras MacroPdf417 (campo opcional). |
| [getPdf417MacroECIEncoding()](#getPdf417MacroECIEncoding--) | Identificadores de Interpretación de Canal Extendido. |
| [getPdf417MacroFileID()](#getPdf417MacroFileID--) | ID de archivo del código de barras MacroPdf417 (campo requerido). |
| [getPdf417MacroFileName()](#getPdf417MacroFileName--) | Nombre de archivo del código de barras MacroPdf417 (campo opcional). |
| [getPdf417MacroFileSize()](#getPdf417MacroFileSize--) | Tamaño del archivo MacroPdf417 (campo opcional). |
| [getPdf417MacroSegmentID()](#getPdf417MacroSegmentID--) | ID del segmento del código de barras MacroPdf417 (campo obligatorio), que comienza en 0, hasta MacroSegmentsCount - 1. |
| [getPdf417MacroSegmentsCount()](#getPdf417MacroSegmentsCount--) | Recuento de segmentos del código de barras MacroPdf417 (campo opcional). |
| [getPdf417MacroSender()](#getPdf417MacroSender--) | Nombre del remitente del código de barras MacroPdf417 (campo opcional). |
| [getPdf417MacroTerminator()](#getPdf417MacroTerminator--) | Se utiliza para indicar al codificador si debe agregar el Terminador Macro PDF417 (código de palabra 922) al segmento. |
| [getPdf417MacroTimeStamp()](#getPdf417MacroTimeStamp--) | Marca de tiempo del código de barras MacroPdf417 (campo opcional). |
| [getPdf417Truncate()](#getPdf417Truncate--) | Si el tipo de simbología Pdf417 del código de barras está truncado (para reducir espacio). |
| [getRows()](#getRows--) | Recuento de filas. |
| [getTruncate()](#getTruncate--) | Si el tipo de simbología Pdf417 del código de barras está truncado (para reducir espacio). |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | Solo se puede usar con MicroPdf417 y codifica modos de emulación Code 128. Puede codificar FNC1 en la segunda posición en los modos 908 y 909, también puede codificar 910 y 911, que solo indican que el MicroPdf417 reconocido puede interpretarse como Code 128. |
| [isLinked()](#isLinked--) | Define modos vinculados con los códigos de barras GS1MicroPdf417, MicroPdf417 y Pdf417. Con la simbología GS1MicroPdf417 codifica los modos UCC/EAN-128 906, 907, 912, 913, 914, 915 \u201cLinked\u201d. Con las simbologías MicroPdf417 y Pdf417 codifica la bandera de enlace 918 al componente lineal asociado que no sea un EAN.UCC. |
| [isReaderInitialization()](#isReaderInitialization--) | Utilizado para instruir al lector a interpretar los datos contenidos en el símbolo como programación para la inicialización del lector. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Relación altura/ancho del módulo de código de barras 2D. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | Solo se puede usar con MicroPdf417 y codifica modos de emulación Code 128. Puede codificar FNC1 en la segunda posición en los modos 908 y 909, también puede codificar 910 y 911, que solo indican que el MicroPdf417 reconocido puede interpretarse como Code 128. |
| [setColumns(int value)](#setColumns-int-) | Recuento de columnas. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identificadores de Interpretación de Canal Extendido. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Identifica el modo de codificación Pdf417. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Establece el nivel de corrección de errores del tipo de simbología Pdf417 del código de barras, que varía de level0 a level8; level0 significa sin información de corrección de errores, level8 significa la mejor corrección de errores, lo que implica una imagen más grande. |
| [setLinked(boolean value)](#setLinked-boolean-) | Define modos vinculados con los códigos de barras GS1MicroPdf417, MicroPdf417 y Pdf417. Con la simbología GS1MicroPdf417 codifica los modos UCC/EAN-128 906, 907, 912, 913, 914, 915 \u201cLinked\u201d. Con las simbologías MicroPdf417 y Pdf417 codifica la bandera de enlace 918 al componente lineal asociado que no sea un EAN.UCC. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Los valores de los caracteres macro 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | Nombre del destinatario del código de barras MacroPdf417 (campo opcional). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | Suma de verificación del código de barras MacroPdf417 (campo opcional). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | Identificadores de Interpretación de Canal Extendido. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | ID de archivo del código de barras MacroPdf417 (campo requerido). |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | Nombre de archivo del código de barras MacroPdf417 (campo opcional). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | Tamaño del archivo MacroPdf417 (campo opcional). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | ID del segmento del código de barras MacroPdf417 (campo obligatorio), que comienza en 0, hasta MacroSegmentsCount - 1. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | Recuento de segmentos del código de barras MacroPdf417 (campo opcional). |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | Nombre del remitente del código de barras MacroPdf417 (campo opcional). |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Se utiliza para indicar al codificador si debe agregar el Terminador Macro PDF417 (código de palabra 922) al segmento. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | Marca de tiempo del código de barras MacroPdf417 (campo opcional). |
| [setPdf417CompactionMode(Pdf417CompactionMode value)](#setPdf417CompactionMode-com.aspose.barcode.generation.Pdf417CompactionMode-) | Tipo de simbología Pdf417 del modo de compactación del código de barras. |
| [setPdf417ECIEncoding(int value)](#setPdf417ECIEncoding-int-) | Identificadores de Interpretación de Canal Extendido. |
| [setPdf417EncodeMode(Pdf417EncodeMode value)](#setPdf417EncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Identifica el modo de codificación Pdf417. |
| [setPdf417ErrorLevel(Pdf417ErrorLevel value)](#setPdf417ErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Establece el nivel de corrección de errores del tipo de simbología Pdf417 del código de barras, que varía de level0 a level8; level0 significa sin información de corrección de errores, level8 significa la mejor corrección de errores, lo que implica una imagen más grande. |
| [setPdf417MacroAddressee(String value)](#setPdf417MacroAddressee-java.lang.String-) | Nombre del destinatario del código de barras MacroPdf417 (campo opcional). |
| [setPdf417MacroChecksum(int value)](#setPdf417MacroChecksum-int-) | Suma de verificación del código de barras MacroPdf417 (campo opcional). |
| [setPdf417MacroECIEncoding(int value)](#setPdf417MacroECIEncoding-int-) | Identificadores de Interpretación de Canal Extendido. |
| [setPdf417MacroFileID(int value)](#setPdf417MacroFileID-int-) | ID de archivo del código de barras MacroPdf417 (campo requerido). |
| [setPdf417MacroFileName(String value)](#setPdf417MacroFileName-java.lang.String-) | Nombre de archivo del código de barras MacroPdf417 (campo opcional). |
| [setPdf417MacroFileSize(int value)](#setPdf417MacroFileSize-int-) | Tamaño del archivo MacroPdf417 (campo opcional). |
| [setPdf417MacroSegmentID(int value)](#setPdf417MacroSegmentID-int-) | ID del segmento del código de barras MacroPdf417 (campo obligatorio), que comienza en 0, hasta MacroSegmentsCount - 1. |
| [setPdf417MacroSegmentsCount(int value)](#setPdf417MacroSegmentsCount-int-) | Recuento de segmentos del código de barras MacroPdf417 (campo opcional). |
| [setPdf417MacroSender(String value)](#setPdf417MacroSender-java.lang.String-) | Nombre del remitente del código de barras MacroPdf417 (campo opcional). |
| [setPdf417MacroTerminator(Pdf417MacroTerminator value)](#setPdf417MacroTerminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Se utiliza para indicar al codificador si debe agregar el Terminador Macro PDF417 (código de palabra 922) al segmento. |
| [setPdf417MacroTimeStamp(LocalDateTime value)](#setPdf417MacroTimeStamp-java.time.LocalDateTime-) | Marca de tiempo del código de barras MacroPdf417 (campo opcional). |
| [setPdf417Truncate(boolean value)](#setPdf417Truncate-boolean-) | Si el tipo de simbología Pdf417 del código de barras está truncado (para reducir espacio). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Utilizado para instruir al lector a interpretar los datos contenidos en el símbolo como programación para la inicialización del lector. |
| [setRows(int value)](#setRows-int-) | Recuento de filas. |
| [setTruncate(boolean value)](#setTruncate-boolean-) | Si el tipo de simbología Pdf417 del código de barras está truncado (para reducir espacio). |
| [toString()](#toString--) | Devuelve una representación en cadena legible por humanos de este [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Relación altura/ancho del módulo de código de barras 2D.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumns() {#getColumns--}
```
public final int getColumns()
```


Recuento de columnas.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. No se aplican a los campos de texto Macro PDF417. La implementación actual incluye todas las codificaciones de conjunto de caracteres conocidas.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


Identifica el modo de codificación Pdf417. Valor predeterminado: Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


Obtiene el tipo de simbología Pdf417 del nivel de corrección de errores del código de barras, que varía de level0 a level8; level0 significa sin información de corrección de errores, level8 significa la mejor corrección de errores, lo que implica una imagen más grande.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Los valores de los caracteres macro 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales. Solo se pueden usar con MicroPdf417 y codifica los modos MicroPdf417 916 y 917. Valor predeterminado: MacroCharacters.None.

Estos ejemplos muestran cómo codificar caracteres macro en MicroPdf417.

```

 [C#]
 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
     using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
       foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


Nombre del destinatario del código de barras MacroPdf417 (campo opcional). Nombre del destinatario del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


Suma de verificación del código de barras MacroPdf417 (campo opcional). Suma de verificación del código de barras MicroPDF417 (campo opcional para el modo Structured Append). El campo de suma de verificación contiene el valor de la suma de verificación CRC de 16 bits (2 bytes) usando el polinomio CCITT-16. x^16 + x^12 + x^5 + 1

**Returns:**
int
### getMacroPdf417ECIEncoding() {#getMacroPdf417ECIEncoding--}
```
public final int getMacroPdf417ECIEncoding()
```


Identificadores de Interpretación de Canal Extendido. Se aplican a los campos de texto Macro PDF417.

**Returns:**
int
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


ID de archivo del código de barras MacroPdf417 (campo obligatorio). ID de archivo del código de barras MicroPDF417 (campo obligatorio para el modo Structured Append).

**Returns:**
int
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


Nombre de archivo del código de barras MacroPdf417 (campo opcional). Nombre de archivo del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public final int getMacroPdf417FileSize()
```


Tamaño del archivo MacroPdf417 (campo opcional). Tamaño del archivo MicroPDF417 (campo opcional para el modo Structured Append). El campo de tamaño del archivo contiene el tamaño en bytes de todo el archivo fuente.

**Returns:**
int
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


ID del segmento del código de barras MacroPdf417 (campo obligatorio), que comienza en 0, hasta MacroSegmentsCount - 1. ID del segmento del código de barras MicroPDF417 (campo obligatorio para el modo Structured Append).

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


Recuento de segmentos del código de barras MacroPdf417 (campo opcional). Recuento de segmentos del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


Nombre del remitente del código de barras MacroPdf417 (campo opcional). Nombre del remitente del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


Se utiliza para indicar al codificador si debe agregar el terminador Macro PDF417 (código 922) al segmento. Se aplica solo para Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


Marca de tiempo del código de barras MacroPdf417 (campo opcional). Marca de tiempo del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

**Returns:**
java.time.LocalDateTime
### getPdf417CompactionMode() {#getPdf417CompactionMode--}
```
public final Pdf417CompactionMode getPdf417CompactionMode()
```


Tipo de simbología Pdf417 del modo de compactación del código de barras. Valor predeterminado: Pdf417CompactionMode.Auto.

**Returns:**
[Pdf417CompactionMode](../../com.aspose.barcode.generation/pdf417compactionmode)
### getPdf417ECIEncoding() {#getPdf417ECIEncoding--}
```
public final int getPdf417ECIEncoding()
```


Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. No se aplican a los campos de texto Macro PDF417. La implementación actual incluye todas las codificaciones de conjunto de caracteres conocidas.

**Returns:**
int
### getPdf417EncodeMode() {#getPdf417EncodeMode--}
```
public final Pdf417EncodeMode getPdf417EncodeMode()
```


Identifica el modo de codificación Pdf417. Valor predeterminado: Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getPdf417ErrorLevel() {#getPdf417ErrorLevel--}
```
public final Pdf417ErrorLevel getPdf417ErrorLevel()
```


Obtiene el tipo de simbología Pdf417 del nivel de corrección de errores del código de barras, que varía de level0 a level8; level0 significa sin información de corrección de errores, level8 significa la mejor corrección de errores, lo que implica una imagen más grande.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getPdf417MacroAddressee() {#getPdf417MacroAddressee--}
```
public final String getPdf417MacroAddressee()
```


Nombre del destinatario del código de barras MacroPdf417 (campo opcional). Nombre del destinatario del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

**Returns:**
java.lang.String
### getPdf417MacroChecksum() {#getPdf417MacroChecksum--}
```
public final int getPdf417MacroChecksum()
```


Suma de verificación del código de barras MacroPdf417 (campo opcional). Suma de verificación del código de barras MicroPDF417 (campo opcional para el modo Structured Append). El campo de suma de verificación contiene el valor de la suma de verificación CRC de 16 bits (2 bytes) usando el polinomio CCITT-16. x^16 + x^12 + x^5 + 1

**Returns:**
int
### getPdf417MacroECIEncoding() {#getPdf417MacroECIEncoding--}
```
public final int getPdf417MacroECIEncoding()
```


Identificadores de Interpretación de Canal Extendido. Se aplican a los campos de texto Macro PDF417.

**Returns:**
int
### getPdf417MacroFileID() {#getPdf417MacroFileID--}
```
public final int getPdf417MacroFileID()
```


ID de archivo del código de barras MacroPdf417 (campo obligatorio). ID de archivo del código de barras MicroPDF417 (campo obligatorio para el modo Structured Append).

**Returns:**
int
### getPdf417MacroFileName() {#getPdf417MacroFileName--}
```
public final String getPdf417MacroFileName()
```


Nombre de archivo del código de barras MacroPdf417 (campo opcional). Nombre de archivo del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

**Returns:**
java.lang.String
### getPdf417MacroFileSize() {#getPdf417MacroFileSize--}
```
public final int getPdf417MacroFileSize()
```


Tamaño del archivo MacroPdf417 (campo opcional). Tamaño del archivo MicroPDF417 (campo opcional para el modo Structured Append). El campo de tamaño del archivo contiene el tamaño en bytes de todo el archivo fuente.

**Returns:**
int
### getPdf417MacroSegmentID() {#getPdf417MacroSegmentID--}
```
public final int getPdf417MacroSegmentID()
```


ID del segmento del código de barras MacroPdf417 (campo obligatorio), que comienza en 0, hasta MacroSegmentsCount - 1. ID del segmento del código de barras MicroPDF417 (campo obligatorio para el modo Structured Append).

**Returns:**
int
### getPdf417MacroSegmentsCount() {#getPdf417MacroSegmentsCount--}
```
public final int getPdf417MacroSegmentsCount()
```


Recuento de segmentos del código de barras MacroPdf417 (campo opcional). Recuento de segmentos del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

**Returns:**
int
### getPdf417MacroSender() {#getPdf417MacroSender--}
```
public final String getPdf417MacroSender()
```


Nombre del remitente del código de barras MacroPdf417 (campo opcional). Nombre del remitente del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

**Returns:**
java.lang.String
### getPdf417MacroTerminator() {#getPdf417MacroTerminator--}
```
public final Pdf417MacroTerminator getPdf417MacroTerminator()
```


Se utiliza para indicar al codificador si debe agregar el terminador Macro PDF417 (código 922) al segmento. Se aplica solo para Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getPdf417MacroTimeStamp() {#getPdf417MacroTimeStamp--}
```
public final LocalDateTime getPdf417MacroTimeStamp()
```


Marca de tiempo del código de barras MacroPdf417 (campo opcional). Marca de tiempo del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

**Returns:**
java.time.LocalDateTime
### getPdf417Truncate() {#getPdf417Truncate--}
```
public final boolean getPdf417Truncate()
```


Indica si el tipo de simbología Pdf417 del código de barras está truncado (para reducir espacio). También conocido como CompactPDF417. El indicador de fila derecha y el patrón de parada derecha se eliminan en este modo.

**Returns:**
boolean
### getRows() {#getRows--}
```
public final int getRows()
```


Recuento de filas.

**Returns:**
int
### getTruncate() {#getTruncate--}
```
public final boolean getTruncate()
```


Indica si el tipo de simbología Pdf417 del código de barras está truncado (para reducir espacio). También conocido como CompactPDF417. El indicador de fila derecha y el patrón de parada derecha se eliminan en este modo.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCode128Emulation() {#isCode128Emulation--}
```
public final boolean isCode128Emulation()
```


Solo se puede usar con MicroPdf417 y codifica modos de emulación Code 128. Puede codificar FNC1 en la segunda posición en los modos 908 y 909, también puede codificar 910 y 911, que solo indican que el MicroPdf417 reconocido puede interpretarse como Code 128.

Estos ejemplos muestran cómo codificar los modos de emulación Code 128 con FNC1 en segunda posición y sin él. De esta manera MicroPdf417 puede decodificarse como código de barras Code 128.

```

 [C#]
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a1222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "991222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 
```

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


Define modos vinculados con los códigos de barras GS1MicroPdf417, MicroPdf417 y Pdf417. Con la simbología GS1MicroPdf417 codifica los modos UCC/EAN-128 906, 907, 912, 913, 914, 915 \u201cLinked\u201d. Con las simbologías MicroPdf417 y Pdf417 codifica la bandera de enlace 918 al componente lineal asociado que no sea un EAN.UCC.

Estos ejemplos muestran cómo codificar los modos \"Linked\" UCC/EAN-128 en GS1MicroPdf417 y la bandera de enlace (Linkage Flag) (918) en los códigos de barras MicroPdf417 y Pdf417.

```

 [C#]
 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked modes 906, 907 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 
```

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Utilizado para instruir al lector a interpretar los datos contenidos en el símbolo como programación para la inicialización del lector.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


Relación altura/ancho del módulo de código de barras 2D.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


Solo se puede usar con MicroPdf417 y codifica modos de emulación Code 128. Puede codificar FNC1 en la segunda posición en los modos 908 y 909, también puede codificar 910 y 911, que solo indican que el MicroPdf417 reconocido puede interpretarse como Code 128.

Estos ejemplos muestran cómo codificar los modos de emulación Code 128 con FNC1 en segunda posición y sin él. De esta manera MicroPdf417 puede decodificarse como código de barras Code 128.

```

 [C#]
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a1222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "991222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 
```

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Recuento de columnas.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. No se aplican a los campos de texto Macro PDF417. La implementación actual incluye todas las codificaciones de conjunto de caracteres conocidas.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


Identifica el modo de codificación Pdf417. Valor predeterminado: Auto.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


Establece el nivel de corrección de errores del tipo de simbología Pdf417 del código de barras, que varía de level0 a level8; level0 significa sin información de corrección de errores, level8 significa la mejor corrección de errores, lo que implica una imagen más grande.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Tipo de simbología Pdf417 del nivel de corrección de errores del código de barras, que varía de level0 a level8; level0 significa sin información de corrección de errores, level8 significa la mejor corrección de errores, lo que implica una imagen más grande. |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Define modos vinculados con los códigos de barras GS1MicroPdf417, MicroPdf417 y Pdf417. Con la simbología GS1MicroPdf417 codifica los modos UCC/EAN-128 906, 907, 912, 913, 914, 915 \u201cLinked\u201d. Con las simbologías MicroPdf417 y Pdf417 codifica la bandera de enlace 918 al componente lineal asociado que no sea un EAN.UCC.

Estos ejemplos muestran cómo codificar los modos \"Linked\" UCC/EAN-128 en GS1MicroPdf417 y la bandera de enlace (Linkage Flag) (918) en los códigos de barras MicroPdf417 y Pdf417.

```

 [C#]
 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked modes 906, 907 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 
```

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Los valores de los caracteres macro 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales. Solo se pueden usar con MicroPdf417 y codifica los modos MicroPdf417 916 y 917. Valor predeterminado: MacroCharacters.None.

Estos ejemplos muestran cómo codificar caracteres macro en MicroPdf417.

```

 [C#]
 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
     using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
       foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


Nombre del destinatario del código de barras MacroPdf417 (campo opcional). Nombre del destinatario del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


Suma de verificación del código de barras MacroPdf417 (campo opcional). Suma de verificación del código de barras MicroPDF417 (campo opcional para el modo Structured Append). El campo de suma de verificación contiene el valor de la suma de verificación CRC de 16 bits (2 bytes) usando el polinomio CCITT-16. x^16 + x^12 + x^5 + 1

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


Identificadores de Interpretación de Canal Extendido. Se aplican a los campos de texto Macro PDF417.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


ID de archivo del código de barras MacroPdf417 (campo obligatorio). ID de archivo del código de barras MicroPDF417 (campo obligatorio para el modo Structured Append).

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


Nombre de archivo del código de barras MacroPdf417 (campo opcional). Nombre de archivo del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


Tamaño del archivo MacroPdf417 (campo opcional). Tamaño del archivo MicroPDF417 (campo opcional para el modo Structured Append). El campo de tamaño del archivo contiene el tamaño en bytes de todo el archivo fuente.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


ID del segmento del código de barras MacroPdf417 (campo obligatorio), que comienza en 0, hasta MacroSegmentsCount - 1. ID del segmento del código de barras MicroPDF417 (campo obligatorio para el modo Structured Append).

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


Recuento de segmentos del código de barras MacroPdf417 (campo opcional). Recuento de segmentos del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


Nombre del remitente del código de barras MacroPdf417 (campo opcional). Nombre del remitente del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


Se utiliza para indicar al codificador si debe agregar el terminador Macro PDF417 (código 922) al segmento. Se aplica solo para Macro PDF417.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


Marca de tiempo del código de barras MacroPdf417 (campo opcional). Marca de tiempo del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.time.LocalDateTime |  |

### setPdf417CompactionMode(Pdf417CompactionMode value) {#setPdf417CompactionMode-com.aspose.barcode.generation.Pdf417CompactionMode-}
```
public final void setPdf417CompactionMode(Pdf417CompactionMode value)
```


Tipo de simbología Pdf417 del modo de compactación del código de barras. Valor predeterminado: Pdf417CompactionMode.Auto.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [Pdf417CompactionMode](../../com.aspose.barcode.generation/pdf417compactionmode) |  |

### setPdf417ECIEncoding(int value) {#setPdf417ECIEncoding-int-}
```
public final void setPdf417ECIEncoding(int value)
```


Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. No se aplican a los campos de texto Macro PDF417. La implementación actual incluye todas las codificaciones de conjunto de caracteres conocidas.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setPdf417EncodeMode(Pdf417EncodeMode value) {#setPdf417EncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setPdf417EncodeMode(Pdf417EncodeMode value)
```


Identifica el modo de codificación Pdf417. Valor predeterminado: Auto.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setPdf417ErrorLevel(Pdf417ErrorLevel value) {#setPdf417ErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setPdf417ErrorLevel(Pdf417ErrorLevel value)
```


Establece el nivel de corrección de errores del tipo de simbología Pdf417 del código de barras, que varía de level0 a level8; level0 significa sin información de corrección de errores, level8 significa la mejor corrección de errores, lo que implica una imagen más grande.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Tipo de simbología Pdf417 del nivel de corrección de errores del código de barras, que varía de level0 a level8; level0 significa sin información de corrección de errores, level8 significa la mejor corrección de errores, lo que implica una imagen más grande. |

### setPdf417MacroAddressee(String value) {#setPdf417MacroAddressee-java.lang.String-}
```
public final void setPdf417MacroAddressee(String value)
```


Nombre del destinatario del código de barras MacroPdf417 (campo opcional). Nombre del destinatario del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setPdf417MacroChecksum(int value) {#setPdf417MacroChecksum-int-}
```
public final void setPdf417MacroChecksum(int value)
```


Suma de verificación del código de barras MacroPdf417 (campo opcional). Suma de verificación del código de barras MicroPDF417 (campo opcional para el modo Structured Append). El campo de suma de verificación contiene el valor de la suma de verificación CRC de 16 bits (2 bytes) usando el polinomio CCITT-16. x^16 + x^12 + x^5 + 1

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setPdf417MacroECIEncoding(int value) {#setPdf417MacroECIEncoding-int-}
```
public final void setPdf417MacroECIEncoding(int value)
```


Identificadores de Interpretación de Canal Extendido. Se aplican a los campos de texto Macro PDF417.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setPdf417MacroFileID(int value) {#setPdf417MacroFileID-int-}
```
public final void setPdf417MacroFileID(int value)
```


ID de archivo del código de barras MacroPdf417 (campo obligatorio). ID de archivo del código de barras MicroPDF417 (campo obligatorio para el modo Structured Append).

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setPdf417MacroFileName(String value) {#setPdf417MacroFileName-java.lang.String-}
```
public final void setPdf417MacroFileName(String value)
```


Nombre de archivo del código de barras MacroPdf417 (campo opcional). Nombre de archivo del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setPdf417MacroFileSize(int value) {#setPdf417MacroFileSize-int-}
```
public final void setPdf417MacroFileSize(int value)
```


Tamaño del archivo MacroPdf417 (campo opcional). Tamaño del archivo MicroPDF417 (campo opcional para el modo Structured Append). El campo de tamaño del archivo contiene el tamaño en bytes de todo el archivo fuente.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setPdf417MacroSegmentID(int value) {#setPdf417MacroSegmentID-int-}
```
public final void setPdf417MacroSegmentID(int value)
```


ID del segmento del código de barras MacroPdf417 (campo obligatorio), que comienza en 0, hasta MacroSegmentsCount - 1. ID del segmento del código de barras MicroPDF417 (campo obligatorio para el modo Structured Append).

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setPdf417MacroSegmentsCount(int value) {#setPdf417MacroSegmentsCount-int-}
```
public final void setPdf417MacroSegmentsCount(int value)
```


Recuento de segmentos del código de barras MacroPdf417 (campo opcional). Recuento de segmentos del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setPdf417MacroSender(String value) {#setPdf417MacroSender-java.lang.String-}
```
public final void setPdf417MacroSender(String value)
```


Nombre del remitente del código de barras MacroPdf417 (campo opcional). Nombre del remitente del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setPdf417MacroTerminator(Pdf417MacroTerminator value) {#setPdf417MacroTerminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setPdf417MacroTerminator(Pdf417MacroTerminator value)
```


Se utiliza para indicar al codificador si debe agregar el terminador Macro PDF417 (código 922) al segmento. Se aplica solo para Macro PDF417.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setPdf417MacroTimeStamp(LocalDateTime value) {#setPdf417MacroTimeStamp-java.time.LocalDateTime-}
```
public final void setPdf417MacroTimeStamp(LocalDateTime value)
```


Marca de tiempo del código de barras MacroPdf417 (campo opcional). Marca de tiempo del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.time.LocalDateTime |  |

### setPdf417Truncate(boolean value) {#setPdf417Truncate-boolean-}
```
public final void setPdf417Truncate(boolean value)
```


Indica si el tipo de simbología Pdf417 del código de barras está truncado (para reducir espacio). También conocido como CompactPDF417. El indicador de fila derecha y el patrón de parada derecha se eliminan en este modo.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Utilizado para instruir al lector a interpretar los datos contenidos en el símbolo como programación para la inicialización del lector.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Recuento de filas.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


Indica si el tipo de simbología Pdf417 del código de barras está truncado (para reducir espacio). También conocido como CompactPDF417. El indicador de fila derecha y el patrón de parada derecha se eliminan en este modo.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Devuelve una representación en cadena legible por humanos de este [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).

**Returns:**
java.lang.String - Una cadena que representa este [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |
| arg1 | int |  |

