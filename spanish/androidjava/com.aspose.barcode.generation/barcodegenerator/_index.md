---
title: BarcodeGenerator
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: BarcodeGenerator para la generación de imágenes de códigos de barras en el backend.
type: docs
weight: 13
url: /es/androidjava/com.aspose.barcode.generation/barcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeGenerator
```

BarcodeGenerator para la generación de imágenes de códigos de barras en el backend.

simbologías compatibles: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>          generator.setCodeText("123ABC");
>          generator.save("code128.png");
> ```
## Constructors

| Constructor | Descripción |
| --- | --- |
| [BarcodeGenerator(BaseEncodeType type)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-) | Crea una instancia de BarcodeGenerator. |
| [BarcodeGenerator(BaseEncodeType type, String codeText)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-) | Crea una instancia de BarcodeGenerator. |
## Methods

| Method | Descripción |
| --- | --- |
| [dispose()](#dispose--) | Limpia cualquier recurso que se esté utilizando. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xml)](#exportToXml-java.io.OutputStream-) | Exporta las propiedades de BarCode al xml-stream especificado |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | Exporta las propiedades de BarCode al xml-file especificado |
| [generateBarCodeImage()](#generateBarCodeImage--) | Genera la imagen del código de barras con la configuración actual. |
| [getBarcodeType()](#getBarcodeType--) | Tipo de simbología de código de barras. |
| [getClass()](#getClass--) |  |
| [getCodeText()](#getCodeText--) | Texto a codificar. |
| [getParameters()](#getParameters--) | Parámetros de generación. |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xml)](#importFromXml-java.io.InputStream-) | Importa las propiedades de BarCode del xml-stream especificado y crea una instancia de BarcodeGenerator. |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | Importa las propiedades de BarCode del xml-file especificado y crea una instancia de BarcodeGenerator. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | Guarda BarCodeImage en un stream en un formato específico. |
| [save(String filename)](#save-java.lang.String-) | Guarda la imagen del código de barras en un archivo específico. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | Guarda la imagen del código de barras en un archivo específico en un formato específico. |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Tipo de simbología de código de barras. |
| [setCodeText(byte[] codeBytes)](#setCodeText-byte---) | Establece codetext como una secuencia de bytes. |
| [setCodeText(String value)](#setCodeText-java.lang.String-) | Texto a codificar. |
| [setCodeText(String codeText, Charset encoding)](#setCodeText-java.lang.String-java.nio.charset.Charset-) |  |
| [setCodeText(String codeText, Charset encoding, boolean insertBOM)](#setCodeText-java.lang.String-java.nio.charset.Charset-boolean-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarcodeGenerator(BaseEncodeType type) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-}
```
public BarcodeGenerator(BaseEncodeType type)
```


Crea una instancia de BarcodeGenerator.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Tipo de simbología de código de barras. Use la clase EncodeTypes para configurar una simbología. |

### BarcodeGenerator(BaseEncodeType type, String codeText) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-}
```
public BarcodeGenerator(BaseEncodeType type, String codeText)
```


Crea una instancia de BarcodeGenerator.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Tipo de simbología de código de barras. Use la clase EncodeTypes para configurar una simbología. |
| codeText | java.lang.String | Texto a codificar. |

### dispose() {#dispose--}
```
public void dispose()
```


Limpia cualquier recurso que se esté utilizando.

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
### exportToXml(OutputStream xml) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xml)
```


Exporta las propiedades de BarCode al xml-stream especificado

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| xml | java.io.OutputStream | El xml‑stream |

**Returns:**
boolean - Indica si la exportación se completó con éxito o no. Devuelve **True** en caso de éxito; **False** de lo contrario
### exportToXml(String xmlFile) {#exportToXml-java.lang.String-}
```
public boolean exportToXml(String xmlFile)
```


Exporta las propiedades de BarCode al xml-file especificado

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| xmlFile | java.lang.String | The name of the file |

**Returns:**
boolean - Whether or not export completed successfully.

Returns  **True**  in case of success;  **False**  Otherwise
### generateBarCodeImage() {#generateBarCodeImage--}
```
public Bitmap generateBarCodeImage()
```


Genera la imagen del código de barras con la configuración actual.

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>          File outputFile = new File("test.png");
>          OutputStream os = new FileOutputStream(outputFile);
>          Bitmap generatedBitmap = generator.generateBarCodeImage();
>          generatedBitmap.compress(Bitmap.CompressFormat.PNG, 100, os);
>          os.flush();
>          os.close();
> ```

**Returns:**
android.graphics.Bitmap - Imagen de código de barras. Ver Bitmap.
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Tipo de simbología de código de barras.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


Texto a codificar.

**Returns:**
java.lang.String
### getParameters() {#getParameters--}
```
public BaseGenerationParameters getParameters()
```


Parámetros de generación.

**Returns:**
[BaseGenerationParameters](../../com.aspose.barcode.generation/basegenerationparameters)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### importFromXml(InputStream xml) {#importFromXml-java.io.InputStream-}
```
public static BarcodeGenerator importFromXml(InputStream xml)
```


Importa las propiedades de BarCode del xml-stream especificado y crea una instancia de BarcodeGenerator.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| xml | java.io.InputStream | El xml‑stream |

**Returns:**
[BarcodeGenerator](../../com.aspose.barcode.generation/barcodegenerator) - BarcodeGenerator instance
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarcodeGenerator importFromXml(String xmlFile)
```


Importa las propiedades de BarCode del xml-file especificado y crea una instancia de BarcodeGenerator.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| xmlFile | java.lang.String | The name of the file |

**Returns:**
[BarcodeGenerator](../../com.aspose.barcode.generation/barcodegenerator) - BarcodeGenerator instance
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(OutputStream stream, BarCodeImageFormat format) {#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(OutputStream stream, BarCodeImageFormat format)
```


Guarda BarCodeImage en un stream en un formato específico.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| flujo | java.io.OutputStream |  |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) |  |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


Guarda la imagen del código de barras en un archivo específico.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| filename | java.lang.String | Ruta donde guardar. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


Guarda la imagen del código de barras en un archivo específico en un formato específico.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| filename | java.lang.String | Ruta donde guardar. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Especifica el formato de archivo de la imagen de salida. |

### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


Tipo de simbología de código de barras.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setCodeText(byte[] codeBytes) {#setCodeText-byte---}
```
public void setCodeText(byte[] codeBytes)
```


Establece codetext como una secuencia de bytes.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| codeBytes | byte[] | Bytes de codetext |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public void setCodeText(String value)
```


Texto a codificar.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setCodeText(String codeText, Charset encoding) {#setCodeText-java.lang.String-java.nio.charset.Charset-}
```
public void setCodeText(String codeText, Charset encoding)
```


Codifica el Unicode **codeText** en una secuencia de bytes usando la **encoding** especificada. UTF-8 es la codificación más utilizada. Si la codificación lo admite, la función inserta automáticamente una [byte order mark (BOM)][byte order mark _BOM].

Esta función está destinada solo para su uso con códigos de barras 2D (p. ej., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, etc.). Permite la codificación manual de texto Unicode usando codificaciones nacionales o especiales; sin embargo, este método se considera obsoleto en aplicaciones modernas. Para casos de uso actuales, se recomienda la codificación [ECI][] para datos Unicode.

El uso de esta función con códigos de barras 1D, códigos de barras compatibles con GS1 (incluidos los 2D) o códigos de barras HIBC (incluidos los 2D) no está soportado por las normas de códigos de barras correspondientes y puede producir resultados impredecibles.

--------------------

> ```
> This example shows how to use ```
> SetCodeText
> ``` setting Unicode-encoded text for 2D barcodes using different encodings:
>   
>   //Encode QR Code text using UTF-8 with BOM
>   BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR);
>   gen.setCodeText("\u8eca\u7a2e\u540d", StandardCharsets.UTF_8;
>   gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR);
>  	for(BarCodeResult result : reader.readBarCodes())
>  	   System.out.println("BarCode CodeText: " + result.getCodeText());
> 
>  	//Encode DataMatrix text using Shift-JIS (Japanese encoding)
>  	BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	gen.setCodeText("\u8eca\u7a2e\u540d", Charset.forName("932"));
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DATA_MATRIX);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText(Charset.forName("932")));
> ```


[byte order mark _BOM]: https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding
[ECI]: https://en.wikipedia.org/wiki/Extended_Channel_Interpretation

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| codeText | java.lang.String | Cadena CodeText |
| codificación | java.nio.charset.Charset | Codificación aplicada |

### setCodeText(String codeText, Charset encoding, boolean insertBOM) {#setCodeText-java.lang.String-java.nio.charset.Charset-boolean-}
```
public void setCodeText(String codeText, Charset encoding, boolean insertBOM)
```


Codifica el Unicode **codeText** en una secuencia de bytes usando la **encoding** especificada. UTF-8 es la codificación más utilizada. Si la codificación lo admite y **insertBOM** está configurado a true, la función incluye una [byte order mark (BOM)][byte order mark _BOM].

Esta función está destinada solo para su uso con códigos de barras 2D (p. ej., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, etc.). Permite la codificación manual de texto Unicode usando codificaciones nacionales o especiales; sin embargo, este método se considera obsoleto en aplicaciones modernas. Para casos de uso actuales, se recomienda la codificación [ECI][] para datos Unicode.

El uso de esta función con códigos de barras 1D, códigos de barras compatibles con GS1 (incluidos los 2D) o códigos de barras HIBC (incluidos los 2D) no está soportado por las normas de códigos de barras correspondientes y puede producir resultados impredecibles.

--------------------

> ```
> This example shows how to use ```
> SetCodeText
> ``` with or without a BOM for 2D barcodes.
>   
>  	//Encode codetext using UTF-8 with BOM
>  	BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR);
>   gen.setCodeText("\u8eca\u7a2e\u540d", StandardCharsets.UTF_8, true);
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR);
>  	for(BarCodeResult result : reader.readBarCodes())
>  	   System.out.println("BarCode CodeText: " + result.getCodeText());
> 
>  	//Encode codetext using UTF-8 without BOM
>  	BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR);
>   gen.setCodeText("\u8eca\u7a2e\u540d", StandardCharsets.UTF_8, false);
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR);
>  	for(BarCodeResult result : reader.readBarCodes())
>  	   System.out.println("BarCode CodeText: " + result.getCodeText());
> ```


[byte order mark _BOM]: https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding
[ECI]: https://en.wikipedia.org/wiki/Extended_Channel_Interpretation

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| codeText | java.lang.String | Cadena CodeText |
| codificación | java.nio.charset.Charset | Codificación aplicada |
| insertBOM | boolean | Indica si se debe insertar una marca de orden de bytes (BOM) cuando la codificación especificada lo admite (p. ej., UTF-8, UTF-16, UTF-32). Si se establece a true, se agrega el BOM; si se establece a false, el BOM se omite incluso si la codificación normalmente lo utiliza. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

