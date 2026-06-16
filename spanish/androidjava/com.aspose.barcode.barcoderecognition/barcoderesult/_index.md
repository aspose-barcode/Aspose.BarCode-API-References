---
title: BarCodeResult
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Almacena los datos del código de barras reconocido como SingleDecodeType tipo cadena codetext BarCodeRegionParameters región y otros parámetros
type: docs
weight: 18
url: /es/androidjava/com.aspose.barcode.barcoderecognition/barcoderesult/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeResult
```

Almacena datos del código de barras reconocido como tipo SingleDecodeType, cadena codetext, BarCodeRegionParameters region y otros parámetros

--------------------

> ```
> This sample shows how to obtain BarCodeResult.
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("BarCode Confidence: " + result.getConfidence());
>      System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>  }
> ```
## Constructors

| Constructor | Descripción |
| --- | --- |
| [BarCodeResult(BarCodeResult result)](#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-) | Crea una copia de la clase BarCodeResult. |
## Methods

| Method | Descripción |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia de la clase BarCodeResult. |
| [equals(Object obj)](#equals-java.lang.Object-) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de BarCodeResult. |
| [getClass()](#getClass--) |  |
| [getCodeBytes()](#getCodeBytes--) | Obtiene los bytes codificados del código |
| [getCodeText()](#getCodeText--) | Obtiene el texto del código |
| [getCodeText(Charset encoding)](#getCodeText-java.nio.charset.Charset-) | Obtiene el texto del código con codificación. |
| [getCodeType()](#getCodeType--) | Obtiene el tipo de código de barras |
| [getCodeTypeName()](#getCodeTypeName--) | Obtiene el nombre del tipo de código de barras |
| [getConfidence()](#getConfidence--) | Obtiene el nivel de confianza del reconocimiento del código de barras reconocido |
| [getExtended()](#getExtended--) | Obtiene los parámetros extendidos del código de barras reconocido |
| [getReadingQuality()](#getReadingQuality--) | Obtiene la calidad de lectura. |
| [getRegion()](#getRegion--) | Obtiene la región del código de barras |
| [hashCode()](#hashCode--) | Devuelve el código hash para esta instancia. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Devuelve una representación de cadena legible por humanos de este BarCodeResult. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeResult(BarCodeResult result) {#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-}
```
public BarCodeResult(BarCodeResult result)
```


Crea una copia de la clase BarCodeResult.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| result | [BarCodeResult](../../com.aspose.barcode.barcoderecognition/barcoderesult) | Una copia de la instancia BarCodeResult. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea una copia de la clase BarCodeResult.

**Returns:**
java.lang.Object - Devuelve una copia de la clase BarCodeResult.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Devuelve un valor que indica si esta instancia es igual a un valor especificado de BarCodeResult.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | Un valor BarCodeResult para comparar con esta instancia. |

**Returns:**
boolean -  **true**  si obj tiene el mismo valor que esta instancia; de lo contrario,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodeBytes() {#getCodeBytes--}
```
public byte[] getCodeBytes()
```


Obtiene los bytes codificados del código

Valor: Los bytes del código del código de barras

**Returns:**
byte[]
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


Obtiene el texto del código

Valor: El texto del código de barras

**Returns:**
java.lang.String
### getCodeText(Charset encoding) {#getCodeText-java.nio.charset.Charset-}
```
public String getCodeText(Charset encoding)
```


Obtiene el texto del código con codificación.

--------------------

> ```
> This example shows how to use ```
> GetCodeText
> ```:
>   
>   BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	gen.setCodeText("\u8eca\u7a2e\u540d", Charset.forName("932"));
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DATA_MATRIX);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText(Charset.forName("932")));
> ```

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| codificación | java.nio.charset.Charset | La codificación para el texto del código. |

**Returns:**
java.lang.String - Una cadena que contiene el texto del código reconocido.
### getCodeType() {#getCodeType--}
```
public SingleDecodeType getCodeType()
```


Obtiene el tipo de código de barras

Valor: La información del tipo del código de barras reconocido

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getCodeTypeName() {#getCodeTypeName--}
```
public String getCodeTypeName()
```


Obtiene el nombre del tipo de código de barras

Valor: El nombre del tipo del código de barras reconocido

**Returns:**
java.lang.String
### getConfidence() {#getConfidence--}
```
public int getConfidence()
```


Obtiene el nivel de confianza del reconocimiento del código de barras reconocido

Valor:  BarCodeConfidence.Strong  no tiene falsos ni errores de reconocimiento,  BarCodeConfidence.Moderate  a veces puede tener falsos o texto de código incorrecto porque este nivel de confianza es para códigos de barras con checksum débil o incluso sin él,  BarCodeConfidence.None  siempre tiene texto de código incorrecto y podría ser reconocimientos falsos

**Returns:**
int
### getExtended() {#getExtended--}
```
public BarCodeExtendedParameters getExtended()
```


Obtiene los parámetros extendidos del código de barras reconocido

Valor: Los parámetros extendidos del código de barras reconocido

**Returns:**
[BarCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/barcodeextendedparameters)
### getReadingQuality() {#getReadingQuality--}
```
public double getReadingQuality()
```


Obtiene la calidad de lectura. Funciona para códigos de barras 1D y postales.

Valor: El porcentaje de calidad de lectura

**Returns:**
double
### getRegion() {#getRegion--}
```
public BarCodeRegionParameters getRegion()
```


Obtiene la región del código de barras

Valor: La región del código de barras reconocido

**Returns:**
[BarCodeRegionParameters](../../com.aspose.barcode.barcoderecognition/barcoderegionparameters)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve el código hash para esta instancia.

**Returns:**
int - Un código hash entero con signo de 32 bits.
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


Devuelve una representación de cadena legible por humanos de este BarCodeResult.

**Returns:**
java.lang.String - Una cadena que representa este  BarCodeResult .
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

