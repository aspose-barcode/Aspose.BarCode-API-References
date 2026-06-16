---
title: Pdf417ExtendedParameters
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Almacena información de metadatos MacroPdf417 del código de barras reconocido
type: docs
weight: 40
url: /es/androidjava/com.aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class Pdf417ExtendedParameters extends BaseExtendedParameters
```

Almacena información de metadatos MacroPdf417 del código de barras reconocido

--------------------

> ```
> This sample shows how to get Macro Pdf417 metadata
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MACRO_PDF_417);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
>      System.out.println("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
>      System.out.println("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
>  }
> ```
## Methods

| Method | Descripción |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de Pdf417ExtendedParameters. |
| [getClass()](#getClass--) |  |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Nombre del destinatario Macro PDF417 (opcional). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Checksum de Macro PDF417 (opcional). |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Obtiene el ID de archivo del código de barras, solo disponible con MacroPdf417. |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Nombre de archivo Macro PDF417 (opcional). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Tamaño de archivo Macro PDF417 (opcional). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Obtiene el ID del segmento del código de barras, solo disponible con MacroPdf417. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Obtiene el recuento de segmentos del código de barras macro pdf417. |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Nombre del remitente Macro PDF417 (opcional). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Indica si el segmento es el último segmento de un archivo Macro PDF417. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Marca de tiempo Macro PDF417 (opcional). |
| [hashCode()](#hashCode--) | Devuelve el código hash para esta instancia. |
| [isCode128Emulation()](#isCode128Emulation--) | Indicador que muestra que el código de barras MicroPdf417 está codificado con palabras de código de emulación Code 128 908, 909, 910 o 911. |
| [isEmpty()](#isEmpty--) | Comprueba si todos los parámetros tienen solo valores predeterminados |
| [isLinked()](#isLinked--) | Indicador que muestra que el código de barras debe estar vinculado a un código de barras 1D. |
| [isReaderInitialization()](#isReaderInitialization--) | Utilizado para instruir al lector a interpretar los datos contenidos en el símbolo como programación para la inicialización del lector. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Devuelve una representación de cadena legible por humanos de este Pdf417ExtendedParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Devuelve un valor que indica si esta instancia es igual a un valor especificado de Pdf417ExtendedParameters.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | Un valor System.Object para comparar con esta instancia. |

**Returns:**
boolean -  **true**  si obj tiene el mismo valor que esta instancia; de lo contrario,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public String getMacroPdf417Addressee()
```


Nombre del destinatario Macro PDF417 (opcional).

**Returns:**
java.lang.String - Nombre del destinatario.
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public int getMacroPdf417Checksum()
```


Checksum de Macro PDF417 (opcional).

**Returns:**
int - Checksum.
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public String getMacroPdf417FileID()
```


Obtiene el ID de archivo del código de barras, solo disponible con MacroPdf417.

Valor: El ID de archivo para MacroPdf417

**Returns:**
java.lang.String
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public String getMacroPdf417FileName()
```


Nombre de archivo Macro PDF417 (opcional).

**Returns:**
java.lang.String - Nombre de archivo.
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public int getMacroPdf417FileSize()
```


Tamaño de archivo Macro PDF417 (opcional).

**Returns:**
int - Tamaño de archivo.
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public int getMacroPdf417SegmentID()
```


Obtiene el ID del segmento del código de barras, solo disponible con MacroPdf417.

Valor: El ID del segmento del código de barras.

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public int getMacroPdf417SegmentsCount()
```


Obtiene el recuento de segmentos del código de barras macro pdf417. El valor predeterminado es -1.

Valor: Recuento de segmentos.

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public String getMacroPdf417Sender()
```


Nombre del remitente Macro PDF417 (opcional).

**Returns:**
java.lang.String - Nombre del remitente
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public boolean getMacroPdf417Terminator()
```


Indica si el segmento es el último segmento de un archivo Macro PDF417.

**Returns:**
boolean - Terminador.
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public LocalDateTime getMacroPdf417TimeStamp()
```


Marca de tiempo Macro PDF417 (opcional).

**Returns:**
java.time.LocalDateTime - Time stamp.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve el código hash para esta instancia.

**Returns:**
int - Un código hash entero con signo de 32 bits.
### isCode128Emulation() {#isCode128Emulation--}
```
public boolean isCode128Emulation()
```


Indicador que muestra que el código de barras MicroPdf417 está codificado con palabras de código de emulación Code 128 908, 909, 910 o 911.

**Returns:**
boolean - Code 128 emulation flag
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Comprueba si todos los parámetros tienen solo valores predeterminados

Valor: Devuelve  **true**  si todos los parámetros tienen solo valores predeterminados; de lo contrario,  **false** .

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public boolean isLinked()
```


Indicador que muestra que el código de barras debe estar vinculado a un código de barras 1D.

Value: Linkage flag

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


Utilizado para instruir al lector a interpretar los datos contenidos en el símbolo como programación para la inicialización del lector.

Value: Reader initialization flag

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




### toString() {#toString--}
```
public String toString()
```


Devuelve una representación de cadena legible por humanos de este Pdf417ExtendedParameters.

**Returns:**
java.lang.String - A string that represents this  Pdf417ExtendedParameters .
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

