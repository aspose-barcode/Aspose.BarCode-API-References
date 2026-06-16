---
title: ComplexBarcodeGenerator
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: ComplexBarcodeGenerator para códigos de barras complejos en el backend, p. ej.
type: docs
weight: 12
url: /es/androidjava/com.aspose.barcode.complexbarcode/complexbarcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class ComplexBarcodeGenerator
```

ComplexBarcodeGenerator para generación de imágenes de códigos de barras complejos en el backend (p. ej. SwissQR).

--------------------

> ```
> This sample shows how to create and save a SwissQR image.
>   
>     SwissQRCodetext swissQRCodetext = new SwissQRCodetext();
>     swissQRCodetext.getBill().setAccount("Account");
>     swissQRCodetext.getBill().setBillInformation("BillInformation");
>     // init rest of the fields
>     ComplexBarcodeGenerator cg = new ComplexBarcodeGenerator(swissQRCodetext);
>     BufferedImage res = cg.generateBarCodeImage();
> ```
## Constructors

| Constructor | Descripción |
| --- | --- |
| [ComplexBarcodeGenerator(IComplexCodetext complexCodetext)](#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-) | Crea una instancia de ComplexBarcodeGenerator. |
## Methods

| Method | Descripción |
| --- | --- |
| [dispose()](#dispose--) | Limpia cualquier recurso que se esté utilizando. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateBarCodeImage()](#generateBarCodeImage--) | Genera una imagen de código de barras complejo con la configuración actual. |
| [getClass()](#getClass--) |  |
| [getParameters()](#getParameters--) | Parámetros de generación. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | Genera y guarda una imagen de código de barras complejo con la configuración actual. |
| [save(String filename)](#save-java.lang.String-) | Genera y guarda una imagen de código de barras complejo con la configuración actual. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | Genera y guarda una imagen de código de barras complejo con la configuración actual. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ComplexBarcodeGenerator(IComplexCodetext complexCodetext) {#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-}
```
public ComplexBarcodeGenerator(IComplexCodetext complexCodetext)
```


Crea una instancia de ComplexBarcodeGenerator.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| complexCodetext | [IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext) | Texto de código complejo |

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
### generateBarCodeImage() {#generateBarCodeImage--}
```
public Bitmap generateBarCodeImage()
```


Genera una imagen de código de barras complejo con la configuración actual.

**Returns:**
android.graphics.Bitmap - Imagen de código de barras. Ver Bitmap.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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


Genera y guarda una imagen de código de barras complejo con la configuración actual.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| flujo | java.io.OutputStream | Salida System.IO.Stream. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Especifica el formato de archivo de la imagen de salida. |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


Genera y guarda una imagen de código de barras complejo con la configuración actual.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| filename | java.lang.String | Ruta donde guardar. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


Genera y guarda una imagen de código de barras complejo con la configuración actual.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| filename | java.lang.String | Ruta donde guardar. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Especifica el formato de archivo de la imagen de salida. |

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

